---
layout: post
title:  "Data Science Use Cases in 5 Stages of Customer Lifecycle Journey"
date:   2021-12-04 10:00:40
blurb: "A look at an example post using Bay Jekyll theme."
og_image: /assets/img/content/post-example/post_3.webp
---

<img src="{{ "/assets/img/content/post-example/post_3.webp" | absolute_url }}" alt="bay" class="post-pic"/>
<br />
<br />


<p>At every stage of the customer journey, there are plenty of touchpoints between the business and the customer. Each touchpoint gives business an opportunity to touch base with the customer either directly or indirectly. Looking at the touchpoint from a data perspective, each point generates data which can be categorized into a approximately 4 types:</p>

<ul>
<li>Behavioural data, which collects the behavioural signals</li>
<li>Demographic data, which includes the customer’s demographic and personal information</li>
<li>Customer data, which is the data collected when customers interact with your product</li>
<li>Product usage, which tracks the behaviour of the customer on how and how much they use your product or service</li>
</ul>

<p>And ofcourse, there is no fixed customer journey map. This varies from business to business. But here I discuss a customer journey from the perspective of ecommerce business.</p>

<p>Some of the key stages of the custoner lifecycle are:</p>

<img src="{{ "/assets/img/content/post-example/post_3_2.webp" | absolute_url }}" alt="bay" class="post-pic"/>

<p>As mentioned previously, each stage of the customer journey has multiple touchpoints between the business and the customer. Here I’ve mentioned a few key touchpoints at each stage.</p>

<img src="{{ "/assets/img/content/post-example/post_3_3.webp" | absolute_url }}" alt="bay" class="post-pic"/>

<p>So we start with the awareness stage. At this stage, we have a customer who has a need for a product. They decide to do a little research on the product they want. They could go up on google to perform a search, look through social media pages, advertisements, blogs or hear it through word of mouth. At this point, the goal is that the customer simply becomes aware of what the business has to offer.</p>

<p>Upon doing their initial research, the customer would narrow down to certain products and brands that they think is what they are looking for. This is known as the consideration stage. At this point the customer could sign up with the business, look more deeply into the landing page, product page, price offering, visit a local store or look through forums to see what other customers are talking about the brands and product.</p>

<p>Following this, is the acquisition stage. If a customer has made it till here, the main goal is to make the first transaction happen or in other words, have a conversion. In this process, the customer would add products to the cart, check out products, perform a payment and receive emails. In some cases they would also receive a follow up offer or coupon.</p>

<p>Although, acquiring a customer is one of the most important step in the customer journey, the most important is retaining the acquired customer. By research, it is found that acquiring a new customer is 5x more expensive than retaining one. On the other hand, retaining a customer can boost revenue by 25–95%. Therefore, the touchpoints in maintaining a customer would be through online or on call customer service, FAQ pages or offline store visits.</p>

<p>Finally, we have the loyalty stage. This is the most important step where the business has the opportunity to create a personal connect with the customer and make them feel valuable. Hence, you can send them personalized emails to keep them updated of new products and offers and keep them coming back to purchase products. So some of the touchpoints include the reorder page, collecting customer reviews, social media mentions and surveys.</p>

<p>Next, we will look at each stage in more detail to analyze what data is available at each stage, the usecases we can develop using this data and how they can impact the business goals.</p>

<h3>Awareness</h3>

<p>So in the awareness stage, the goal is to increase awareness of the brand and product to the customers and have a first look into the customer. This would include information on website cookies and give information on advertisement data, traffic data, the type of browser the customer uses, location data, and finally the sessions and pages data.</p>
<p>A business can initially target and experiement on platforms to advertise on when they have minimal information about their audience. But when enough data is collected about the performance of ads and observe which platforms are gaining more traction, it can help streamline the marketing strategy and reduce cost on ads.</p>
<p>Next, using the geographic data, we can target customers with location based notifications, for example, on content and time.</p>
<p>On plotting the session and page traffic data we can understand what the customer is looking for, what pages they spent most time on and so on.</p>
<p>Hence, using tools such as google analytics and google data studio, we can create dashboards which can be shared with multifunctional teams to show the various metrics on ads, search volume and traffic.</p>

<h3>Consideration</h3>
<p>Next, moving onto the consideration stage, the customer is trying to make a decision on if they want to purchase from your brand or a competitor. Hence the main goal is to get the customer to the acquisition stage.</p>
<p>So, in some cases, customers can sign up to the website to gain more information on initial product offerings. This allows us to collect data on the customer name, email-id, contact number, age group and gender. As the customer makes their way through the website, we can also collect data on page navigations, click on links, the products the customer explores and the wish list. Using these information, we can perform customer segmentation in two ways — demographic based segmentation vs a behavioural based segmentation. Another usecase would be to perform a path analysis to look for any broken links, understand where customers drop off, what leads customers to the next stage in the journey and the steps leading to it.</p>
<p>Additionally, when there is presence of multiple local stores for the business, we can perform a trend test such as the cochran armitage test to identify the popular stores within the business.</p>
<p>Hence the business impact here would be to create a smooth customer journey by reducing friction. This would help enhace customer experience, which would in turn enhance the customer lifetime value later on.</p>

<h3>Acquisition</h3>
<p>The customer has finally decided to purchase your product. The goal now can depend on the type of customer. If they are a new customer, we would ideally like them to buy products for the first time. But if they are returning customers, then apart from just buying a certain product, we would also aim to increase the average order value.</p>
<p>So to take a look at the data collected and its usecases at this stage, we would have the cart information: such as the the products purchased, the quantity and the order value, offers used and the type of payment method. These data points can be used to perform a customer segmentation based on customer purchasing behaviour. We can also perform a recommendation system to up sell or cross sell products to the returning customers.</p>
<p>In some cases there would be customers who have products in their wishlist and cart but still have not checked out. In this case, we can set up retargeting ads to encourage the customers to come back to complete the transaction.</p>
<p>At this point in the journey, we have collected the entire set of data points all the way from awareness till conversion. Hence, we can analyze the path of the converted customers and identify where they came from. This again gives us an opportunity to create strategies that can guide other customers to follow this path, leading to an increased conversion rate and reduced cost of acquisition.</p>

<h3>Service</h3>
<p>Now, upon acquiring the customer, the next step is to retain the customers. Like said before, retaining a customer can boost the customer lifetime value and hence the revenue for the business.</p>
<p>The data collected here would be on the satisfaction of the product and service, delivery window chosen by customers and additional payment information.</p>
<p>This is also the point in the journey where customers contact for customer service and maintenance. Hence, we can collect data on the number of customer service front such as the medium of contact, number of tickets raised, calls made, information on the issue and the experience rating. Using this, we can build classification models to identify patterns in the raised issues and take preventive actions. The type of issues can also be segmented and directed to specific customer service teams to handle more efficiently thus enhancing the customer experience. We can build chatbots to answer basic questions that do not require human intervention.</p>
<p>To evaluate the customer’s experience up until this point in the journey, we can create surveys and request customers to take part for a small incentive. The survey can consist of questions relating to satifaction rate, NPS and the intention variable with a score on a scale of 0–10. Combining the customer survey data along with the survey data and using the intention variable as a dependent variable, a regression analysis can be performed to identify factors that are driving customer retention.</p>
<p>The usecases here aim at increasing the retention of the customer.</p>

<h3>Loyalty</h3>
<p>And finally we have the customer loyalty stage. This is a stage that can sometimes make or break the brand. If the business does a good job of delivering what was promised it will only attract more customers.</p>
<p>We can perform a cohort analysis on the customers based the recency, frequency and the monetary value.</p>
<p>The customers would also be talking about your products either on your website, marketplace, forums or social media. We can collect these reviews and perform a sentiment analysis to understand what the customers are saying and the emotions towards those aspects. This would provide the business with where they need to improve on.</p>
<p>Next, it is important to make the customers feel valued. Hence, one way to do this is performing a conjoint analysis with your customers to better learn about their product preferences. This makes the customers feel heard and they would want to come back to purchase over and over.</p>

<h3>Conclusion</h3>
<p>As part of the data team, we can constantly find numbers to assess the behaviour and needs of the customer while constantly improving any under-performance in the journey. As an business, there will be multiple teams such as marketing, sales, supply chain and so on. But for a customer, it is the entire experience from the beginning till the end that counts and hence we can also help connect the dots between customer interaction with company’s products and business outcomes. To do this, we can start breaking silos and encouraging a data mindset with both the team and the client and create awareness of what data can do for the business.</p>
