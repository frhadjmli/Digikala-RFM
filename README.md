### Digikala RFM Analysis
This repository serves as an example of RFM (Recency, Frequency, Monetary) Analysis. The data used in this project is from an online retail business called Digikala and is available in this repository.

---

#### About RFM Analysis
RFM Analysis is a customer segmentation technique used in marketing and CRM to analyze customer purchasing behavior based on three metrics:

- Recency (R): How recently a customer made a purchase
- Frequency (F): How often a customer makes purchases
- Monetary (M): How much money a customer spends
Customers are scored (commonly from 1 to 5) on each metric.

The combined score (e.g. R=5, F=4, M=5 → 545) represents the customer’s value and this value determines the segment each customer belongs to.

| **Segment**         | **Description**                                            |
|---------------------|------------------------------------------------------------|
| Champions           | Bought recently, buy often and spend the most.             |
| Loyal Customers     | Spend good money. Responsive to promotions.                |
| Potential Loyalists | Recent customers, spent good amount, bought more than once |
| New Customers       | Bought more recently but not often                         |
| Promising           | Recent shoppers but haven't spent much                     |
| Need Attention      | Above average recency, frequency & monetary values         |
| About to Sleep      | Below average recency, frequency & monetary values         |
| At Risk             | Spent big money, purchased often but long time age         |
| Can't Lose Them     | Made big purchases and often but long time age             |
| Hibernating         | Low spenders, low frequency and purchased long time ago    |
| Lost                | Lowest recency, frequency & monetary values                |

---

#### Project Output

This project utilizes Digikala’s dataset (specifically Orders.csv) and Python’s powerful pandas library to generate a CSV file containing customers and their assigned RFM segments. For more details on the implementation, please refer to the analysis notebook.

---

#### Contact
- Project maintainer: `Farhad Jamali`
    
- Email: farhad080.jamali@gmail.com