<h1 align="center">Australian Politicians Twitter Data Analysis Using Python<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="55" height="40"/> </a> </h1>


<p align="center">
  <img width="640" height="360" src="https://raw.githubusercontent.com/vinhphuphan/Tweets-Analysis/main/images/79592twitter.jpg">
</p>

## Introduction
Social media platforms, especially Twitter, have become a significant channel for politicians to communicate with the public and share their views on various issues. In the context of Australian politics, two prominent figures, Kevin Rudd and Scott Morrison, have leveraged Twitter to engage with the public, express their opinions, and influence political discourse.
### The Dataset
The dataset that contains 200 tweets of Kevin Rudd and 200 tweets of Scott Morrison in 2021 from Twitter API for developer.
<pre class="line-numbers language-json">      <code class="t05__copy language-json"><span class="token punctuation">{</span>
  <span class="token property">"created_at"</span><span class="token operator">:</span> <span class="token string">"Thu Apr 06 15:24:15 +0000 2017"</span><span class="token punctuation">,</span>
  <span class="token property">"id_str"</span><span class="token operator">:</span> <span class="token string">"850006245121695744"</span><span class="token punctuation">,</span>
  <span class="token property">"text"</span><span class="token operator">:</span> <span class="token string">"1\/ Today we\u2019re sharing our vision for the future of the Twitter API platform!\nhttps:\/\/t.co\/XweGngmxlP"</span><span class="token punctuation">,</span>
  <span class="token property">"user"</span><span class="token operator">:</span> <span class="token punctuation">{</span>
    <span class="token property">"id"</span><span class="token operator">:</span> <span class="token number">2244994945</span><span class="token punctuation">,</span>
    <span class="token property">"name"</span><span class="token operator">:</span> <span class="token string">"Twitter Dev"</span><span class="token punctuation">,</span>
    <span class="token property">"screen_name"</span><span class="token operator">:</span> <span class="token string">"TwitterDev"</span><span class="token punctuation">,</span>
    <span class="token property">"location"</span><span class="token operator">:</span> <span class="token string">"Internet"</span><span class="token punctuation">,</span>
    <span class="token property">"url"</span><span class="token operator">:</span> <span class="token string">"https:\/\/dev.twitter.com\/"</span><span class="token punctuation">,</span>
    <span class="token property">"description"</span><span class="token operator">:</span> <span class="token string">"Your official source for Twitter Platform news, updates &amp; events. Need technical help? Visit https:\/\/twittercommunity.com\/ \u2328\ufe0f #TapIntoTwitter"</span>
  <span class="token punctuation">}</span><span class="token punctuation">,</span>
  <span class="token property">"place"</span><span class="token operator">:</span> <span class="token punctuation">{</span>   
  <span class="token punctuation">}</span><span class="token punctuation">,</span>
  <span class="token property">"entities"</span><span class="token operator">:</span> <span class="token punctuation">{</span>
    <span class="token property">"hashtags"</span><span class="token operator">:</span> <span class="token punctuation">[</span>      
    <span class="token punctuation">]</span><span class="token punctuation">,</span>
    <span class="token property">"urls"</span><span class="token operator">:</span> <span class="token punctuation">[</span>
      <span class="token punctuation">{</span>
        <span class="token property">"url"</span><span class="token operator">:</span> <span class="token string">"https:\/\/t.co\/XweGngmxlP"</span><span class="token punctuation">,</span>
        <span class="token property">"unwound"</span><span class="token operator">:</span> <span class="token punctuation">{</span>
          <span class="token property">"url"</span><span class="token operator">:</span> <span class="token string">"https:\/\/cards.twitter.com\/cards\/18ce53wgo4h\/3xo1c"</span><span class="token punctuation">,</span>
          <span class="token property">"title"</span><span class="token operator">:</span> <span class="token string">"Building the Future of the Twitter API Platform"</span>
        <span class="token punctuation">}</span>
      <span class="token punctuation">}</span>
    <span class="token punctuation">]</span><span class="token punctuation">,</span>
    <span class="token property">"user_mentions"</span><span class="token operator">:</span> <span class="token punctuation">[</span>     
    <span class="token punctuation">]</span>
  <span class="token punctuation">}</span>
<span class="token punctuation">}</span><span aria-hidden="true" class="line-numbers-rows"><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span></span></code>
    </pre>
----------------------------------------------
## Result

#### Posting Times
<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/Tweets-Analysis/main/images/posting_time.png" width=640></p>
<h4 align="center">Figure 1. Tweet Activity by Hour of the Day</h4>
The data reveals differences in the tweeting habits of Kevin Rudd and Scott Morrison throughout the day. Notably, Kevin Rudd is more active in the morning, with a peak around 6 AM, while Scott Morrison's activity is more evenly distributed, with a prominent peak around 9 AM and another in the afternoon. From 12PM - 15PM, both of them are usually quite on Twitter. These variations in posting times can be attributed to their individual routines and communication styles.


#### Top Words Analysis
<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/Tweets-Analysis/main/images/Top_20.png" width=100%></p>
<h4 align="center">Figure 2. Top 20 Words Most Strongly Associated with Each of the Two Users.</h4>

The top 20 words most strongly associated with each of the two users, Kevin Rudd and Scott Morrison, provide insights into their distinct communication styles and the topics they frequently address.Tweets data was collected in 2021, so Kevin Rudd and Scott Morrison's words suggest a focus on covid-19 pandemic and public health. These word associations can help identify the key themes and interests of the two politicians based on their Twitter activity.

#### Tweet Sentiment Analysis
<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/Tweets-Analysis/main/images/sentiment_analysis.png" width=100%></p>
<h4 align="center">Figure 3. The Proportions of Tweets Compound Sentiment for Two Users.</h4>

Investigating the sentiment of tweets by Kevin Rudd and Scott Morrison reveals differences in sentiment proportions. While Scott Morrison's tweets tend to be more positive, Kevin Rudd's tweets have a higher negative sentiment.

## Conclusion

Our analysis provides valuable insights into the Twitter activities of Kevin Rudd and Scott Morrison, shedding light on their tweeting behavior, sentiments, and language patterns. We hope this analysis contributes to a better understanding of the digital presence of these Australian politicians.

## Related Projects:question: 👨‍💻 🛰️

**Data Analysis**

<code>[Olympic-Weightlifting-Data-Analysis Using R](https://github.com/vinhphuphan/Olympic-Weightlifting-Data-Analysis)</code> 📊

<code>[Australia Road Deaths Statistic Report Using Excel](https://github.com/vinhphuphan/Australia-Road-Deaths-Statistic)</code> 📊

<code>[Titanic - Machine Learning from Disaster using Python](https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster)</code> 📊

<code>[Australian Politicians Twitter Data Analysis Using Python](https://github.com/vinhphuphan/Tweets-Analysis)</code> 📊

**Data Science Applications**

<code>[Text Classification With Movie Reviews](https://github.com/vinhphuphan/Text-Classification-With-Movie-Reviews/)</code> 📊

<code>[Living Species Image Classification using Python](https://github.com/vinhphuphan/Living-Species-Image-Classification)</code> 📊

<code>[Name Entity Recognition](https://github.com/vinhphuphan/Name-Entity-Recognition)</code> 📊

**Website Front End Practice**

<code>[Hospital-Landing-Page](https://github.com/vinhphuphan/Hospital-Landing-Page/)</code> 📊

<code>[LaslesVPN Landing Page](https://github.com/vinhphuphan/Lasles-VPN-Landing-Page)</code> 📊

<code>[Frontend Mentor Challenge Submission Using HTML&CSS](https://github.com/vinhphuphan/Frontendmentor-Challenge-HTML-CSS)</code> 📊

**Have fun building!** 🚀




