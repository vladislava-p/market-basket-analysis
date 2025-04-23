# Market Basket Analysis (Apriori Algorithm)

Implementation of **Market Basket Analysis** using the **Apriori algorithm** on transactional retail data.

## Goal
To uncover product associations and generate recommendation rules using frequent itemsets.

## Dataset
Simulated retail data: 603 purchases from 95 customers  
Each row = transaction ID, products bought

## Technologies Used
- **Python**
- pandas, apriori, matplotlib, seaborn
- Association rules: `Apriori`, `lift`, `confidence`, `support`

## Steps
1. Convert transaction data to one-hot encoded matrix
2. Use Apriori algorithm to find frequent itemsets
3. Derive association rules
4. Visualize rule metrics (support, confidence, lift)

## Key Metrics
- Minimum support = 0.05
- Minimum confidence = 0.6
- Generated ~40 valid rules

## Contact
pileckavladislava@gmail.com  
Telegram: @pillecka
