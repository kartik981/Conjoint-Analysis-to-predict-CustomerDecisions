 # Finding Key Factors Affecting Customer Decisions Using Conjoint Analysis

## Introduction
Understanding customer preferences is essential for effective market segmentation. This project applies **conjoint analysis** using **fractional factorial design** to determine key factors influencing laptop purchase decisions. **Principal Component Analysis (PCA)** is also used to analyze product perceptions.

## Methodology
### Data Preparation
1. **Attribute and Level Selection:**
   - Attributes: **Brand, Hard Drive, RAM, Screen Size, Price**.
   - Levels: Defined for each attribute (e.g., Apple, Lenovo, Dell for Brand).
   - Initial dataset contained **576 product profiles**, reduced to **20 using fractional factorial design**.

2. **Survey Data Collection:**
   - **132 potential buyers** ranked laptop profiles based on preference.

### Conjoint Analysis
- **Part-Worth Estimation:**
  - Measures how much each attribute level influences customer choice.
  - Example: Customers were **6.9× more likely** to choose Acer over Apple in a specific case.
![Part-worths](https://github.com/kartik981/Conjoint-Analysis-to-predict-CustomerDecisions/blob/f8494031c63da17f5e30923845f5726f6dcdd031/variance.png)
- **Relative Importance of Attributes:**
  - **RAM (25%)** and **Screen Size (25.85%)** were the most influential factors.
  - Customers willing to pay **$1193.19 more for Apple** than Acer.
![Attribute Importance](https://github.com/kartik981/Conjoint-Analysis-to-predict-CustomerDecisions/blob/f8494031c63da17f5e30923845f5726f6dcdd031/attribute%20importance.png)

### Market Simulation
- **First Choice Model:** 37% of customers preferred **Apple (256GB, 16GB RAM, 17.3in, $1500)**.
![First Choice Model](https://github.com/kartik981/Conjoint-Analysis-to-predict-CustomerDecisions/blob/f8494031c63da17f5e30923845f5726f6dcdd031/first%20choice%20model.png)
- **Logit Share Model:** Apple dominated, while Dell had **zero market share**.
![Logit Share Model](https://github.com/kartik981/Conjoint-Analysis-to-predict-CustomerDecisions/blob/f8494031c63da17f5e30923845f5726f6dcdd031/logit%20share%20model.png)

### Principal Component Analysis (PCA)
- **86% variance explained** by the first three principal components.
![Elbow graph for Variance](https://github.com/kartik981/Conjoint-Analysis-to-predict-CustomerDecisions/blob/f8494031c63da17f5e30923845f5726f6dcdd031/variance.png)
- **Key Insights:**
  - **RAM and Screen Size** positively correlated with customer preference.
  - **Price and Hard Drive Size** had a negative correlation.

## Conclusion
- **Most influential factors:** **RAM, Screen Size, and Price.**
- **Brand importance was lower**, but Apple remained dominant.
- **Recommended Strategy:**
  - Prioritize **high RAM and larger screens** in marketing.
  - Expand Apple product offerings.
  - Use competitive pricing to shift market share.

## References
- Green, P. & Srinivasan, V. (1978). *Conjoint Analysis in Consumer Research.*
- Jolliffe, I. (2002). *Principal Component Analysis.*
- Kim, J. et al. (2011). *Product Positioning Using Conjoint Analysis.*
- Toubia, O. (2005). *Reducing Choice Overload in Iterative Choice Settings.*
