# Q-Commerce Apps EDA

**A deep dive into the delivery performance, customer sentiment and platform efficiency of India's top instant delivery apps.**

In the age of 10-minute delivery promises, quick-commerce platforms like Blinkit, Swiggy Instamart and JioMart are changing how people shop. This project analyses **100,000 delivery records** to find out what drives delivery success, customer satisfaction and refund behaviour.

## What this project covers

- Data cleaning and exploration across platforms
- Univariate and bivariate analysis
- Sentiment analysis of customer feedback with TextBlob
- Visualisation of trends across platforms, product categories and feedback
- Business insights drawn from the data

## Key insights

### Delivery performance
- Average delivery time across all platforms: **~29.5 minutes**
- **13.7%** of orders were delayed, often leading to poor ratings and refund requests
- Swiggy Instamart and Blinkit outperformed JioMart on delivery efficiency and consistency

### Customer sentiment and ratings
- Feedback was mostly very positive or very negative; neutral feedback was rare
- Delayed orders correlated strongly with negative sentiment and low service ratings
- Average service rating: **~3.2 / 5**

### Refund behaviour
- **46%** of orders had refund requests
- Higher refund rates were linked to delays, high order values and negative feedback
- Fruits and dairy had more refund complaints, pointing to packaging or freshness issues

## Business implications

- **Small local businesses are at risk.** Deep discounts and near-instant delivery are hard for neighbourhood stores to match.
- **Efficiency matters more than raw speed.** Fast delivery means little if quality is poor or items are missing.
- **Balance wins.** Platforms that combine speed with accuracy and customer care should see better retention and lower refund losses.

## Files

| File | Description |
|------|-------------|
| `ecommerce_delivery_app_eda.ipynb` | Full analysis notebook |
| `Ecommerce_Delivery_Analytics_New.csv` | Raw delivery dataset |
| `Ecommerce_Analytics_Cleaned.csv` | Cleaned dataset used for analysis |

## Run it

```bash
pip install pandas numpy seaborn matplotlib textblob jupyter
jupyter notebook ecommerce_delivery_app_eda.ipynb
```

## Tech stack

Python (pandas, NumPy, seaborn, matplotlib), TextBlob, Jupyter Notebook


---

<sub>Made by [tanaytejush](https://github.com/tanaytejush)</sub>
