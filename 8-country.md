---
layout: default
title: "Sickada"
banner_header: "Which country is the smartest...."
subtitle: ".... or How does learning content is modulated by the location of creators?"
---

## **A little bit of geography first**
Now we know you are tired from going from one clickbait 'video' to another. So let's just give you some eye candy 🍬 

Let us ask ourselves the questions: Where do our teachers come from? And how do their content vary depending on their country of origin ? We start with the Youtube channels distribution over the globe:

<div>
  <iframe src="assets/plots/country_channel.html" width="100%" height="500px" style="border:none;"></iframe>
</div>



We see straight away that, as expected, English speaking countries represent the majority of the Youtube channels of our dataset, followed by countries that are known to have good English skills (Central Europe, Nordics or South Africa). We observe with astonishment that the French actually know how to speak english (immunity granted by our french team members)! In general we see that most countries do not have a lot of channels. Also beware that this information is entered by the users so it might not be totally accurate. Take your time to explore the map, check the end of the page for a meme on this plot !

## Video Categories are country dependent

Next up we take a closer look at the proportion of video categories in a given country.

<div>
  <center>
    <iframe src="assets/plots/country_sunburst.html" width="100%" height="800px" style="border:none;"></iframe>
  </center>
</div>

We take a closer look at the big contributors and some other interesting ones: 

<div>
  <center>
    <iframe src="assets/plots/country_pie_EN.html" width="100%" height="1200px" style="border:none;"></iframe>
  </center>
</div>

First of all, teachers from all countries share a big interest in spiritual themes. This is surprising and might be due to a classification that was too generous or to hidden subgenres of Youtube unknown to us. More specifically we see that cliches are partly true and that India has a passion for Programming and Science & tech (categories 4 and 61). Brits are worldwide known to be very bad at languages but their teachers interest the whole world. Who hasn't wished to have a perrrfect british accent ? They also have a big presence in Music which is no surprise given their cultural monuments like The Beatles, David Bowie or Queen.

Canada does not stand out in terms of categories, neutral as usual but is the first to show cryptocurrency in its top 5. Finally our data confirms the US as leaders in terms of Music and Sports (we think of american football, basketball or fitness influencers), with a rich History section. 
 

<div>
  <center>
    <iframe src="assets/plots/country_pie_CH.html" width="100%" height="1000px" style="border:none;"></iframe>
  </center>
</div>

Switzerland does not share the preference for spirituality of others, contradicting its lutheran roots. It is however surprisingly a reference in terms of Dancing and Philosophy. Who knew we had among us so many dance teachers ! Finally South Africa impresses by its presence in History, surely influenced by its colonial past and great figures like Nelson Mandela.

## Which countries receive the most love ❤️

In a school there are always cool teachers and teachers no one likes. We asked ourselves, which countries receive the most likes and dislikes per video. For that we plot likes per video as a metric of appreciation and dislikes per video as a metric of disapproval. Bubble size represents the median number of views for each country and the color scheme relates to regions of the world.

<div>
  <center>
    <iframe src="assets/plots/country_likes_dislikes.html" width="100%" height="500px" style="border:none;"></iframe>
  </center>
</div>


In the lower right quadrant we have the most appreciated nationalities in terms of likes per video. These include Austria and Japan (with lots of confidence ie bubble size). We note that there are no polarizing teachers at the country level, generating lots of likes and dislikes at the same time. This is yet another proof that Youtube is a good teacher.

The distribution of this data seems to be twofold at first, with one trend going steeper into negativity while another follows a flatter trajectory. This effect might be induced by the different ranges of the two axis, so caution is needed. Nevertheless Serbia and Vietnam have a like/dislike ratio close to 0.3 while Romania and Austria are at more or less 0.03, which shows us that there is indeed a trend toward more negativity in these countries. Japan is at 0.08 which is normal since Japanese culture is worldwide appreciated (think sushi and anime).


### Bonus meme

<center>
<img src="assets/images/polar_bear.jpg" alt="ColdTube" width="300" height="200">
</center>









