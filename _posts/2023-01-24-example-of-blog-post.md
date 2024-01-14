---
layout: post
title:  "Jaccard coefficient to measure Incremental Lift"
date:   2023-01-24 10:00:40
blurb: "A look at an example post using Bay Jekyll theme."
og_image: /assets/img/content/post-example/post_5.webp
---
<!--
<img src="{{ "/assets/img/content/post-example/post_6.webp" | absolute_url }}" alt="bay" class="post-pic"/>  -->

<p>The Jaccard similarity index, also known as the similarity coefficient, compared members for two set o see which members are shared and which are distinct. The measure is a similarity of two sets that range from a 0% to 100%. Higher the percentage, higher the similarity.</p>

<h2>Incremental Lift</h2>

<p>An incremental test is performed to understand the uplift in your ad recall, awareness levels or conversion numbers post an ad exposure. The test is set up in the following ways:</p>
<ol>
<li>Identify your target audience who have a homogeneous set of characteristics. This is to ensure there is no bias in the experiment and we can be more confident that the ad exposure cause the lift in KPI.</li>
<li>Divide the target audience in test and control groups.</li>
<li>The ad is exposed to only the test group.</li>
<li>Run the test for a duration of 2–8 weeks and continue measuring the impact on KPI at the respondent level.</li>
</ol>

<h2>Using Jaccard Index to test the Incrementality</h2>
<p>Upon ending the experiment, the data can be arranged in the following way:
<br />
X = {1, 3, 4, 6, 8, 9}
<br />
Y = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
<br /> 
<br />
X is the set of customer ids from the test group, who have contributed towards the KPI post ad exposure. Y is the set of all customer ids in the test group.
<br />
<br />
<b>Jaccard Index = (the customer id in X and Y) / (the customer id in X or Y) * 100 </b>
<br />
<br />
<b>J(X,Y) = |X∩Y| / |X∪Y|</b>
<br />
<br />
J(X,Y) = 6/10 = 60%
<br />
<img src="{{ "/assets/img/content/post-example/post_6_1.webp" | absolute_url }}" alt="bay" class="post-pic"/> 
<br />
<br />
Therefore, the percentage of respondents who either recalled your ad or purchased your product is 60% post being exposed to the advertisement.
</p>

<h2>Limitations</h2>
<p>Although the above method is quick and easy to interpret, it can be extremely sensitive to small sample sizes or missing observations, giving misleading results.</p>