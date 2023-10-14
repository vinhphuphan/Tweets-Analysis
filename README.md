<h1 align="center">Australian Politicians Twitter Data Analysis Using Python<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="55" height="40"/> </a> </h1>


<p align="center">
  <img width="640" height="360" src="https://raw.githubusercontent.com/vinhphuphan/Tweets-Analysis/main/images/79592twitter.jpg">
</p>

## Introduction
Social media platforms, especially Twitter, have become a significant channel for politicians to communicate with the public and share their views on various issues. In the context of Australian politics, two prominent figures, Kevin Rudd and Scott Morrison, have leveraged Twitter to engage with the public, express their opinions, and influence political discourse.
### The Dataset
The dataset that contains 200 tweets of Kevin Rudd and 200 tweets of Scott Morrison from Twitter API for developer.
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


#### 🛠 Technologies and Tools 🛠
[![My Skills](https://skillicons.dev/icons?i=py,numpy)](https://skillicons.dev)
## Result
**Posting Times**
<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/Tweets-Analysis/main/images/posting_time.png" width=640></p>
<h4 align="center">Figure 1. The Trend of Road Accident Deaths over decade</h4>
The data reveals differences in the tweeting habits of Kevin Rudd and Scott Morrison throughout the day. Notably, Kevin Rudd is more active in the morning, with a peak around 6 AM, while Scott Morrison's activity is more evenly distributed, with a prominent peak around 9 AM and another in the afternoon. From 12PM - 15PM, both of them are usually quite on Twitter. These variations in posting times can be attributed to their individual routines and communication styles.

### Top Words Analysis

We calculated log odds ratios for words used in the tweets to identify the 20 words most strongly associated with each politician. This analysis helps reveal the unique language patterns of Kevin Rudd and Scott Morrison.

### Tweet Sentiment Analysis

We employed the VADER sentiment analysis tool to assess the sentiment of each tweet, resulting in the categorization of tweets as positive, negative, or neutral.

## Data Visualization

The project includes various data visualizations using Python libraries such as Matplotlib and Seaborn. The visualizations help us better understand the data and present our findings in an accessible manner.

## Usage

You can access the Jupyter Notebook containing the code for this analysis in the 'analysis.ipynb' file.

## Conclusion

Our analysis provides valuable insights into the Twitter activities of Kevin Rudd and Scott Morrison, shedding light on their tweeting behavior, sentiments, and language patterns. We hope this analysis contributes to a better understanding of the digital presence of these Australian politicians.
