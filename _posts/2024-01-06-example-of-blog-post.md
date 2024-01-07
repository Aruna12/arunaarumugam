---
layout: post
title:  "Designing and Evaluating an A/B test"
date:   2023-07-27 10:00:40
blurb: "A look at an example post using Bay Jekyll theme."
og_image: /assets/img/content/post-example/post_2.png
---

<img src="{{ "/assets/img/content/post-example/post_2.png" | absolute_url }}" alt="bay" class="post-pic"/>
<br />
<br />


<p>A/B testing is a methodologyused online when you want to test a new product or feature. We would generally consider 2 group of users, namely, the control group and the treatment group. We then measure how the two groups respond. </p>

<p>When you do this experiment, it is key that you make only one change at a time. It is also key to have the right amount of users the two groups. For an experiment where the number of users change over time, it is important to determine the timeframe of the experiement too. </p>

<h2>Designing an experiment</h2>

<h3>Step 1: Choose your experiment</h3>

First and foremost, you need to make a decision on what we would like to experiment. That is, changing the color of the button, changing the location of the button from one part of the page to another, using an alternative campaign title etc. When there are multiple changes you want to test, it is required to prioritize the order of experiments and test them only one at a time.

<h3>Step 2: Defining your success metric and hypothesis</h3>

<p>An AB test can provide you with multiple metrics to look at. But you need to define your primary metric. This can be the number of clicks, click through rate, click through probability and so on. In this step, we also define the null and alternate hypothesis. </p>

<p>For example, we want experiment if the click through probability of a button increases when we change it from red to green color. </p>

<p>Null hypothesis: Changing the button from red to green does not change the click through probability </p>
<b>Alternate hypothesis: Changing the button from red to green will increase the click through probability</b>
 

<h3>Step 3: Create your test</h3>

<p>Now that we have chose our experiment and defined the hypothesis, it is time to create different versions of the page. The only difference between the two pages would be the color of the button. One version would have it red while the other has it green.</p>

<h3>Step 4: Run the test</h3>

<p>At this point, when we have the two different versions of the pages for test, we then split our users into the control and the treatment group. This spit has to be completely random inorder to avoid any kind of bias in the experiment. The interaction of the users with the different pages is measured and counted.</p>

<h3>Step 5: Analyzing the data — statistical hypothesis testing</h3>

<p>You can now look at the difference in conversion rates between the treatment and the control groups. Now, there will be a number of observations we could make from the two groups, such as, time on page, interations with the page etc. But our main focus here would be to see how many users eventually clicked on the button to go to the next page.</p>

<p>To see if there is a change in the click through probability between the two groups, you can define a significance level and perform a t-test to see if or we reject the null hypothesis or accept the alternate hypothesis.</p>

<h3>Step 6: Concluding you test and next steps</h3>

Based on the results you obtain, if there is no significance difference between the two groups, you can choose a different variant and repeat the test to observe alternate results. Else, if you are satisfied with the test results, you can evaluate what you need to do to make required changes to the website.

<h3>Points to consider while designing an A/B test</h3>

<ul>
<li>Although the two groups created are required to be random, it is important that the participant groups are similar to each other based on demographics, geography, age groups etc.</li>
<li>It is important to determine your sample size but this is variant to the experiment and cannot be fixed. Although having a large sample size would provide us a more reliable result, obtaining 1000 customers in each group is not the same obtaining a similar number in different parts of the world.</li>
<li>It is a good practice to perform your test multiple times to obtain a better overall accuracy.</li>
</ul>
