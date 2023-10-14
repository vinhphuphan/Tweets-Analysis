<h1 align="center">Australian Politicians Twitter Data Analysis Using Python<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="55" height="40"/> </a> </h1>

<p align="center">
  <img width="600" height="200" src="[https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Titanic.png](https://raw.githubusercontent.com/vinhphuphan/Tweets-Analysis/main/images/79592twitter.jpg)">
</p>

## The Dataset
I download the dataset that contains 200 tweets of Kevin Rudd and 200 tweets of Scott Morrison from Twitter API for developer.
<pre class="line-numbers language-json">      <code tabindex="0" class="t05__copy language-json"><span class="token punctuation">{</span>
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
## Data Analysis

### Posting Times Analysis



### Hashtag and Link Analysis

We investigated the use of hashtags and links in their tweets to understand their engagement with various topics and external content.

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
