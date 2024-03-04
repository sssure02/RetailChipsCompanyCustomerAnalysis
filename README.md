# ✨Retail Chips Company Customer Analysis
## About the project:
The Category Manager of a chips company has approached Quantium's retail analytics team to analyze their data and provide actionable insights to boost sales. The project also aims to evaluate the effectiveness of new trial store layouts.
<details>
<summary> About the datasets: </summary>
<br>
  
QVI_purchase_behavior dataset: This dataset comprises information on approximately 72,000 customers and includes:
* LYLTY_CARD_NBR: Unique customer identifier.
* LIFESTAGE: Classification of customers based on their life stage. They are described as one of the following: young singles/couples, midage singles/couples, older singles/couples, new families, young families, older families, and retirees.
* PREMIUM_CUSTOMER: Categorization of customers based on the premium level of their purchasing behavior, segmented into budget, mainstream, and premium tiers.

QVI_transaction_data dataset: This dataset encompasses details of around 200,000 transactions and includes:
* DATE: Transaction date.
* STORE_NBR: Store identifier where the transaction occurred.
* LYLTY_CARD_NBR: Unique customer identifier associated with the chip purchase.
* PROD_NBR: Product number corresponding to the purchased chips.
* PROD_NAME: Name of the purchased chips.
* PROD_QTY: Quantity of chip packs purchased.
* TOT_SALES: Total sales amount generated from the transaction.
</details>

## Task 1:
The goal of this project phase is to analyze the transaction dataset and identify customer purchasing behaviors to provide sales-boosting recommendations. Primarily, I learned how to 
* identify customer segments based on purchasing behavior
* examine sales drivers to gain insights into overall sales performance.

### Insights into Customer Purchasing Behaviors:
* Sales have mainly been due to Budget- older families, Mainstream- young singles/couples, and Mainstream- retirees shoppers.
  - We found that the high spend in chips for mainstream young singles/couples and retirees is due to there being more of them than other buyers.
* Mainstream, midage, and young singles/couples are also more likely to pay more per packet of chips, indicating impulsive buying tendencies.
* We’ve also found that Mainstream young singles/couples are 23% more likely to purchase Tyrrells chips compared to the rest of the population.

### Recommendation:
**To boost category performance, the Category Manager could strategically place Tyrrells and smaller chip packs in high-traffic areas where young singles/couples frequent more often to increase visibilty and impulse behaviour.**

## Task 2:
The goal of this project phase is to identify benchmark stores that allow us to test the impact of the trial store layouts on customer sales. Primarily, I 
* learned how to select control stores based on defined metrics
* gained proficieny in performing statistical analysis to assess sales differences and formulate recommendations.
* deepened my understanding of experimentation and uplift testing, comparing trial and control stores.

### Insights from New Trial Layouts Evaluation:
* We’ve found control stores 233, 155, 237 for trial stores 77, 86 and 88 respectively.
* The results for trial stores 77 and 88 during the trial period show a significant difference in at least two of the three trial months but this is not the case for trial store 86.
  - We can check with the client if the implementation of the trial was different in trial store 86.

### Recommendation:
**Overall, the trial shows a significant increase in sales. The trial layout should be rolled out to all their stores.**
 
## Skills used:
* R
* Affinity Analysis
* Uplift testing 

#### The project was completed through the Quantium Data Analytics Job Simulation on Forage. The certificate of completion can be found [here](Certificate.pdf).
