---
layout: default
title: "Sickada"
banner_header: "How You Became Smarter ...."
subtitle: ".... or how has the volume of educational content changed over time"
---

In the last 15 years, YouTube has emerged as a powerhouse for educational content, revolutionizing how knowledge is shared and consumed globally. From tutorials to in-depth lectures, the platform has become a go-to resource for learning. But how did the volume of educational content on Youtube evolved over time ? We will explore the trends in the number of educational videos uploaded each year alongside the growth in the number of educational channels created annually.

## **Educational videos over the years**
To begin with, let's look at the volume of videos and channels categorized as Educational in the dataset.
<div>
  <iframe src="assets/plots/educational_videos_number_proportion_per_year.html" width="100%" height="500" frameborder="0"></iframe>
  <p style="text-align: center;">Figure 1: Dummy Plotly Chart</p>
</div>
The data reveals an intriguing contrast: while the number of educational videos uploaded has grown exponentially, their proportion relative to all uploaded content has steadily declined since peaking in the early 2010s. This downward trend in proportion began after 2010, even as the absolute numbers continued to rise, indicating that the overall expansion of content categories on YouTube has far outpaced the growth of educational content. It is important to note that the years 2005, 2006, and 2007 shows a very little number of videos that could affect the statistics. This could be the reason why we see a growing trend in the proportion of videos at the earliest years.

Fitting an OLS to the data (starting from 2008) show that there is a statistical significant relationship between the proportion of eduational videos and the year. 

|R²|p-value|slope|
|--|-------|-----|
|0.631|0.00203|-0.1688|

Following the model results, there is a 0.16% decrease in the volume of educational content per year.

<!-- What about the number of educational channels ? -->
<!-- <div>
  <iframe src="assets/educational_channel_number_proportion_per_year.html" width="100%" height="500" frameborder="0"></iframe>
  <p style="text-align: center;">Figure 1: Dummy Plotly Chart</p>
</div>
This plot highlight a reccuring trend: while the number of educational channels created per year is growing, the proportion of educational channels is decreasing. A particularly striking observation is the sharp decline in both the absolute number and the proportion of educational channels created in 2018, marking a challenging year for the creation of educational content. This could suggests a significant shift in the platform's dynamics or external factors influencing creators’ decisions during this year. -->

>*Note: The year 2019 is not fully accounted for in the dataset, so the absolute number of videos and channels for this year is incomplete and not representative of the full annual trend.*

## **Academic VS Edutainement**
As said earlier, these are the videos and channels categorized as Educational in the dataset, based on self-definition by the content creator. The term "Educational" can encompass a wide range of interpretations, including content such as children's songs, or tutorials on various subjects which may not align with the more focused educational topics we are specifically interested in analyzing.

For this reason, we decided re-classify the videos using BART, a natural language processing model capable of performing sentiment analysis. We asked the model to classify a sample of 50000 "Educational" videos into 3 categories: 'academic', 'edutainement or science popularization' and 'hobby'.
<div>
  <iframe src="assets/plots/proportion_video_type_per_year.html" width="100%" height="500" frameborder="0"></iframe>
  <p style="text-align: center;">Figure 1: Dummy Plotly Chart</p>
</div>

The data reveals a clear shift in the type of educational content on YouTube, with a decline in academic videos and a rise in edutainment content over time. Between 2008 and 2013, there is a noticeable increase in edutainment videos, signaling its growing popularity during the early years of YouTube. This early rise in popularity could reflect the novelty of the platform and the unmet demand for new and accessible educational content. We see that academic videos became less and less popular reaching a plateau at around 2011. We could argue that youtube introduced a new type of educational content that is easier to consume and fits YouTube’s informal and entertainment-focused culture better. The transition from academic to edutainment content reflects changing consumer preferences. Viewers on YouTube may prefer content that simplifies complex topics, incorporates storytelling, and uses visuals and humor to maintain engagement.

Fitting an OLS to the data shows that there is a statistically significant relationship between the porportion of academic or edutainement videos and the year. Here are the important results :

| Type      | R²   | p-value | Slope |
|-----------|------|---------|-------|
| Academic | 0.733 | 0.000188 | -0.0185 |
| Edutainement | 0.792 | 4.63e-05 | 0.0174 |

We see that following this model, there is a 1.85% decrease of academic videos per year and a 1.74% increse of edutainement videos per year.

## **What did we learn**
We learned that YouTube's educational content has changed a lot over the years. While the number of videos and channels has grown, their share of total content has decreased as the platform expanded into other. We also see a shift from academic videos to edutainment. Viewers seem to prefer content that is easier to understand, fun, and engaging. This shows how YouTube has adapted to meet changing audience preferences, making education more accessible and entertaining.