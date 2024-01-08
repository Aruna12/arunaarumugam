---
layout: post
title:  "What is Media Mix Modeling?"
date:   2022-01-16 10:00:40
blurb: "A look at an example post using Bay Jekyll theme."
og_image: /assets/img/content/post-example/post_3.webp
---

<img src="{{ "/assets/img/content/post-example/post_4.webp" | absolute_url }}" alt="bay" class="post-pic"/>
<br />
<br />

<p>Which channels should we invest in for our marketing activities? How have the different media channels contributed to our sales in the past? Should we continue marketing through Facebook? These are questions every marketing and strategy team in an organization would look to answer to be able measure the effectiveness of their marketing activities and future planning.
<p>Media Mix Modeling, can help your business answer these questions towards your past and future marketing activities. The Media Mix Model uses statistical analysis to estimate the impact of your past media activities — through a time series data of your spends and impressions on various media channels. It helps quantify the contributions from various marketing activities towards your sales or conversions.</p>


<h2>1. Data Requirements:</h2>
<p>The first step to performing the media mix modeling is data preparation.</p>

<h3>Media Data or Incremental Drivers:</h3>
<p><b>Offline Media:</b> This includes spends on TV, radio, press, billboards and so on. When it comes to offline media, there is no way to judge if someone has converted because of the advertisement seen or heard through these channels. This completely depends on the product and the business. The aim of offline ads is to create awareness, which can further get the customer moving ahead in the purchase funnel. We use the spends in the corresponding day or week for each media channel in our media mix model.</p>
<p><b>Digital Media:</b> This includes platforms such as facebook, instagram, twitter, linkedin, programmatic ads, etc. In addition to the corresponding daily or weekly spends on the respective platforms, in most cases, we can also obtain the corresponding impressions, views and clicks, based on the platform type. Use of impressions as opposed to spends can given a more accurate number on how many people have interacted or seen the advertisement.</p>
<p><b>Promotions and discounts:</b> Having the corresponding spends and periods of the sales, promotions, short term campaigns or events can add more story and capture any additional conversions in the data.</p>

<h3>Base Sales Data:</h3>
<p>This includes data on brand quity such as your brand awareness, quality, value and so on, which has been built over the years. It also includes other factors such as pricing points, seasonality and macroeconomic factors. Each of these variables have different behaviours towards yours sales. They either drive or pull down your sales without any marketing activities.</p>

<h2>2. Modeling:</h2>
<p>Upon collecting and preprocessing the data, we then go ahead and build our model.</p>


<h3>Multi-Linear Regression:</h3>
<p>MMM uses the principle of multi-linear regression. Your dependent variable is sales count or value. The independent variables are those mentioned in the data requirements section. The equation now formed can have a linear or non-linear relationship to the dependent variable. Advertisements over time will tend to saturate with no incremental impact. Thus, we use variable transformations to account for the non-linear relationships. I will discuss this in detail on my next post.</p>
<p>The coefficients of the model quantify the impact of the media activities. The avantage of using a linear regression is the interpretebility. Therefore, one unit increase in the spend or impression, results in one unit increase in sales count or value by keeping all other activities constant.</p>

<h3>Contributions:</h3>
<p>As a next step, to see the impacts of various media activities, we calculate the respective contributions.</p>
<img src="{{ "/assets/img/content/post-example/post_4_1.webp" | absolute_url }}" alt="bay" class="post-pic"/>

<p>The MMM is a good exercise to understand the performance of various marketing efforts. Post this, the team can create what-if scenerios to perform optimizations and budget allocation.</p>