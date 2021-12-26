## Predicting customer satisfaction at Olist - a Brazilian e-commerce platform

### Problem statement

Each business's mission is to satisfy their customers. With an e-commerce platform where customers' purchase is affected by the product's feedback and sellers' ratings, keeping a positive feedback loop is crucial for customer return and sales growth. Therefore, in this project, we're interested in predicting the customer review scores, to better understand the  customers' experience through product quality, sellers' reputation, and shipping process. This would help the company to continue selecting better products to offer on their platform, recommend more reliable sellers, improve the delivery operation, and especially, design the effective customer services and marketing campaigns to different targeted customers.

### Data
In this project, we use data shared by Olist - a Brazilian e-commerce platfrom. The data set contains 9 sub-datasets that offer valuable information on 3 main aspects of an e-commerce transaction:
- `Products`: category, description, size & weight of the product.
- `Customers and sellers`: tracking id & shipping location.
- `Order and shipping process`: number of items, tracking timestamp of the purchase & shipping, customer reviews (by score and text).

In addition, Brazilian demographic data at state level is used for customer's social-economic context.

### Data source: 
Raw data of Olist and detailed descriptions of the attributes were retrieved from this post on Kaggle: <a href="https://www.kaggle.com/olistbr/brazilian-ecommerce"> Brazilian E-Commerce Public Dataset by Olist </a>.
<br>
Raw data of Brazil social-economic factors were loaded from Brazilian Institute of Geography and Statistics: 
<a href="https://www.ibge.gov.br/en/statistics/social/income-expenditure-and-consumption/18704-summary-of-social-indicators.html?=&t=resultados"> household average income </a> and <a href="https://www.ibge.gov.br/en/statistics/social/population/18448-estimates-of-resident-population-for-municipalities-and-federation-units.html?edicao=21737&t=downloads"> population </a> by state.
