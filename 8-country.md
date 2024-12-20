---
layout: default
title: "Sickada"
banner_header: "Which country is the smartest...."
subtitle: ".... or How does learning content is modulated by the location of creators?"
---

## **A little bit of geography first**
Now we know you are tired from going from one clickbait 'video' to another. So let's just give you some eye candy.

First of all let us explore where our teachers come from: 

<div>
  <iframe src="assets/plots/country_channel.html" width="100%" height="500px" style="border:none;"></iframe>
</div>

> Figure 1: Channels distribution over the globe

We see straight away that English speaking countries represent the majority of the Youtube channels of our dataset, followed by countries that are known to have good English skills (Central Europe and Nordics or South Africa). We see with surprise that the French actually know how to speak english???. Take the time to explore the map, you might notice that Antartida actually has educational youtubers!

## Video Categories are country dependent

Next up we take a closer look at the proportion of video categories in a given country: 

<div>
  <center>
    <iframe src="assets/plots/country_sunburst.html" width="100%" height="500px" style="border:none;"></iframe>
  </center>
</div>

Differences might be more apparent if we split this plot as so : 





## Which countries receive the most love ❤️

In a school there are always cool teachers and teachers no one likes. We asked ourselves, which countries received the most likes and dislikes. For that we plot likes per video as a metric of appreciation and dislikes per video as a metric of disapproval. We represent the median number of views for each country witht the size of the bubble.

<div>
  <center>
    <iframe src="assets/plots/country_likes_dislikes.html" width="100%" height="500px" style="border:none;"></iframe>
  </center>
</div>

In the lower right quadrant we have the most appreciated countries in terms of likes per video. We see that there are no polarizing teachers at the country level, generating lots of likes and dislikes at the same time. 




  

> A brief introduction explaining the purpose of the analysis and the key questions being explored. Keep it simple, clear, and engaging.

**Example:**
*Have you ever wondered why sales spike during certain months? This report uncovers trends, patterns, and insights from our latest dataset.*

---

## **Key Findings**
### **Top Insights:**
- **Sales Growth:** Sales increased by **25%** in Q3 compared to Q2.
- **Product Performance:** **Product A** outperformed others in urban markets.
- **Web Traffic:** Website traffic surged following the new marketing campaign.

> Use **bold text** for key points and *italics* for clarifications.

---

## **Visual Insights**
### **Centered Image**
![Sales Trends Chart](assets/images/banner.jpeg)
> *Figure 1: Sales trends across quarters.*

---

### **Image with Text Alignment**
#### Image to the Left
<div style="display: flex; align-items: center; margin-bottom: 1.5rem;">
    <img src="assets/images/profile.jpeg" alt="Urban Market Performance" width="40%" style="margin-right: 1rem;">
    <p>
        **Observation:** *Product A demonstrated remarkable performance in urban markets during the campaign. This suggests a need to further target similar demographics for sustained growth.*
    </p>
</div>

---

#### Image to the Right
<div style="display: flex; align-items: center; margin-bottom: 1.5rem;">
    <p style="margin-right: 1rem;">
        **Insight:** *Website traffic surged after the new campaign launch, highlighting strong audience engagement. Future campaigns can capitalize on this trend to drive conversions.*
    </p>
    <img src="assets/images/profile.jpeg" alt="Website Traffic Growth" width="40%">
</div>

---

## **Deep Dive Analysis**
Break down each key finding with deeper analysis, supported by visuals and data tables.

### **Sales Analysis**
- **Observation:** The highest sales occurred in **July**, driven by a summer promotion.
- **Details:** The promotion contributed to a **50% growth rate** in sales.

| Month      | Sales ($)   | Growth Rate |
|------------|-------------|-------------|
| June       | 10,000      | +5%         |
| July       | 15,000      | +50%        |
| August     | 12,000      | -20%        |

> *July's promotion was highly successful, but August showed a decline, indicating the need for follow-up strategies.*

---

## **Interactive Plotly Visualization**
Below is an interactive Plotly chart embedded directly into this Markdown file using HTML:

<div>
  <iframe src="assets/plot.html" width="100%" height="500px" style="border:none;"></iframe>
  <p style="text-align: center;">Figure 1: Dummy Plotly Chart</p>
</div>

### **Plotly Chart with Text on the Right**
<div style="display: flex; align-items: center; margin-bottom: 2rem;">
  <!-- Plot -->
  <div style="flex: 1; margin-right: 1rem;">
    <iframe src="assets/plot.html" width="100%" height="500" frameborder="0"></iframe>
  </div>
  <!-- Text -->
  <div style="flex: 1;">
    <h3>Insights</h3>
    <p>
      This Plotly chart highlights the performance of various categories over time. Use it to analyze trends and identify key areas for improvement or further study.
    </p>
    <p>
      The data indicates significant growth in Q3, with certain categories outperforming others due to targeted strategies.
    </p>
  </div>
</div>

---

### **Plotly Chart with Text on the Left**
<div style="display: flex; align-items: center; margin-bottom: 2rem;">
  <!-- Text -->
  <div style="flex: 1; margin-right: 1rem;">
    <h3>Analysis</h3>
    <p>
      This visualization compares multiple metrics across different months. It reveals seasonal trends and helps in understanding variations in performance across quarters.
    </p>
    <p>
      The results emphasize the importance of summer promotions and their impact on overall sales growth.
    </p>
  </div>
  <!-- Plot -->
  <div style="flex: 1;">
    <iframe src="assets/plot.html" width="100%" height="500" frameborder="0"></iframe>
  </div>
</div>

---

## **Embedded Videos**
You can embed videos directly into your report using HTML. For example:

### **Marketing Campaign Video**
<div style="text-align: center;">
  <iframe
    width="560"
    height="315"
    src="https://www.youtube.com/embed/tiEPzEp2T4A"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
  ></iframe>
</div>
<p style="text-align: center;">Figure 3: Overview of our marketing campaign strategy.</p>

---

## **Conclusions**
> *In summary, our analysis shows that targeted promotions in urban areas drive significant sales growth. However, maintaining momentum after campaigns remains a challenge.*

---

## **Next Steps and Recommendations**
### **Actionable Recommendations:**
1. Launch a **follow-up campaign** in **August** to sustain sales momentum.
2. Focus on urban markets for **Product A**, as they demonstrate the highest potential.
3. Leverage website analytics to identify trends and optimize future marketing campaigns.

---

## **Additional Notes**
- **Dataset:** [View Dataset](https://github.com/epfl-dlab/YouNiverse)
- **Tools Used:** *Python, pandas, Matplotlib*
- **References:** Internal sales records and web traffic data.

---

*Thank you for reading! Feel free to reach out for further information or collaboration opportunities.*
