# Product Recommendation System using Hybrid Filtering

## Overview

This project develops a **Hybrid Product Recommendation System** for an e-commerce platform by combining **Popularity-based Filtering**, **Content-based Filtering**, and **Collaborative Filtering** to generate personalized product recommendations.

The system is designed to improve customer engagement, enhance product discovery, and support data-driven marketing strategies by recommending the most relevant products for each customer.

---

## Business Objective

Modern e-commerce platforms often contain thousands of products, making it difficult for customers to discover items that match their interests.

This project aims to:

- Build a personalized product recommendation system.
- Improve customer engagement and shopping experience.
- Increase product discovery and cross-selling opportunities.
- Support business decision-making through recommendation analytics.

---

## Dataset

**Source:** Kaggle – E-commerce Dataset

Dataset includes:

- Customer information
- Product information
- Transaction history
- User-product interactions

Dataset Path:

```
/kaggle/input/ecommerce-dataset
```

---

## Project Workflow

```
Raw Data
     │
     ▼
Data Cleaning
     │
     ▼
Feature Engineering
     │
     ▼
Exploratory Data Analysis (EDA)
     │
     ▼
────────────────────────────────────
Popularity-based Filtering
Content-based Filtering
Collaborative Filtering
────────────────────────────────────
     │
     ▼
Hybrid Recommendation Engine
     │
     ▼
Top-N Product Recommendation
     │
     ▼
Model Evaluation
     │
     ▼
Business Insights
```

---

## Exploratory Data Analysis

The dataset was analyzed to understand:

- Customer purchasing behavior
- Product popularity
- Customer-product interaction patterns
- Purchase frequency
- Product distribution

The insights from EDA were used to support feature engineering and recommendation model development.

---

## Recommendation Models

### 1. Popularity-based Filtering

Recommends globally popular products based on historical interactions.

**Advantages**

- Simple
- Fast
- Effective for new users

---

### 2. Content-based Filtering

Recommends products with similar characteristics based on product features and customer preferences.

---

### 3. Collaborative Filtering

Learns customer preferences from historical interactions to recommend products that similar users have purchased.

---

### 4. Hybrid Recommendation System

The final recommendation combines:

- Popularity-based Filtering
- Content-based Filtering
- Collaborative Filtering

to improve recommendation quality while reducing the limitations of each individual method.

---

## Sample Prediction

| User | Product | Actual Rating | Predicted Rating |
|------:|---------:|--------------:|-----------------:|
| 9899 | 2542 | 1.0 | 1.479 |
| 3871 | 1279 | 1.0 | 0.935 |
| 8107 | 3494 | 1.0 | 1.183 |
| 2639 | 3336 | 3.0 | 1.808 |
| 4003 | 2214 | 1.0 | 0.964 |

---

## Sample Recommendations

### User 1572

```
[511, 2575, 142, 2143, 3292,
2614, 2911, 2516, 3123, 2824]
```

### User 1999

```
[3491, 2575, 3386, 2909, 142,
1657, 3100, 2844, 2854, 258]
```

### User 11041

```
[2824, 2614, 2575, 2911, 1126,
3123, 2155, 2030, 370, 482]
```

---

## Model Evaluation

| Top-K | RMSE | F1-score |
|-------:|-----:|----------:|
| Top-3 | 1.2243 | 0.5002 |
| Top-5 | 1.2244 | 0.4999 |
| Top-10 | **1.2246** | **0.4997** |

---

## Business Value

The recommendation system can support e-commerce businesses by:

- Delivering personalized product recommendations
- Increasing customer engagement
- Improving product discovery
- Supporting cross-selling opportunities
- Enhancing customer shopping experiences
- Providing data-driven recommendations for marketing activities

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Power BI
- Machine Learning
- Popularity-based Filtering
- Content-based Filtering
- Collaborative Filtering

---

## Future Improvements

Future enhancements may include:

- Deep Learning-based Recommendation Models
- Real-time Recommendation Engine
- Context-aware Recommendation
- Customer Segmentation Integration
- Recommendation API Deployment
- Additional ranking evaluation metrics (Precision@K, Recall@K, NDCG)

---

## Author

**Tran Hoang Thanh Thu**

Business Intelligence | Data Analytics | Machine Learning

