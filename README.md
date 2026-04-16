# BIMA AI: Getter-Insure-AI
BIMA AI is an AI-powered recommendation engine designed to intelligently identify insurance needs based on customer's real time banking behavior, financial profile and life events. Instead of relying solely on human sales teams or passive marketing. the system embeds insurance recommendations directly into banking channels(payment confirmation sms).


# Bima-AI: Insurance Cross-Sell Engine Inside Banking Transactions

**An AI-powered recommendation engine designed to intelligently identify insurance needs based on customer banking behavior, financial profile, and life events.**

---

## Project Overview

**Bima-AI** (Getter Insure AI) is a machine learning-powered recommendation system that automates bancassurance by embedding personalized insurance recommendations directly into banking channels. Instead of relying solely on human sales teams or passive marketing, the system intelligently identifies when customers are most receptive to insurance products based on real-time banking behavior and life events.

### The Problem

Traditional bancassurance cross-selling faces critical limitations:

- **Low Customer Engagement**: Customers rarely encounter insurance offers unless manually contacted
- **Lack of Contextual Relevance**: Recommendations aren't based on actual financial behavior or life events
- **Limited Data-Driven Insights**: Banks rarely leverage transactional patterns to infer insurance needs
- **Sales Team Dependency**: Performance heavily depends on manual follow-ups and branch visits

### The Solution

Bima-AI solves this by automating the entire process using machine learning models trained on:

- Customer demographics
- Income segmentation
- Banking transactions
- Spending categories
- Digital engagement patterns
- Existing insurance policies

---

## Key Features & Objectives

### 1. **Personalized, Real-Time Recommendations**

Identifies customer life events and recommends appropriate insurance products:

- **Salary Credit** - Life Cover
- **School Fees Payment** - Education Cover
- **Travel Bookings** - Travel Insurance
- **Electronics Purchase** - Gadget Insurance
- **Loan Disbursements** - Credit Life Cover
- **Vehicle, Repair Payment, Car Wash Payment & Fuel Purchase** - Motor Insurance
- **Hospital Bills & Drug Purchases** - Medical Insurance

### 2. **Automated Lead Generation**

- Removes dependence on manual outreach
- Auto-generates leads for Relationship Managers (RMs)
- Triggers self-service digital flows

### 3. **Improved Financial Protection**

- Ensures customers have adequate protection at key life moments
- Reduces underinsurance caused by low awareness

### 4. **Revenue Growth**

- Drives higher conversion rates
- Expands insurance penetration through digital channels
- Increases bancassurance revenue

---

## Dataset Overview

The project uses a **semi-rule-based dataset** containing:

- **35,000 customer records** with no missing values
- **12 features** including:
  - **Demographics**: Age, Occupation, City, Income Band
  - **Customer Profile**: Customer Segment, KYC Risk Rating
  - **Behavioral**: Transaction Amount, Spending Category
  - **Channel Data**: Digital Channel (App, USSD, Internet Banking, Branch)
  - **Target**: Insurance Product Type (Travel, Education, Gadget, Medical, Life, Motor)

### Key Statistics

| Metric | Value |
|--------|-------|
| Total Records | 35,000 |
| Features | 11 (+ 1 target) |
| Age Range | 18-79 years |
| Average Transaction Amount | KES 149,922 |
| Average Premium Amount | KES 7,782 |
| Customer Segments | 3 (Affluent, SME, Mass Market) |
| Income Bands | 3 (Low, Medium, High) |
| Cities | 10 major Kenyan cities |
| Occupations | 639 unique occupations |

---

## Machine Learning Models

The project implements and compares multiple classification algorithms:

### Implemented Models

- **Logistic Regression** - Baseline linear model
- **Decision Tree Classifier** - Rule-based approach
- **Random Forest Classifier** - Ensemble method
- **XGBoost Classifier** - Gradient boosting
- **Neural Networks** - Deep learning approach using TensorFlow/Keras

### Evaluation Metrics

- **Accuracy Score**
- **Precision & Recall**
- **F1-Score**
- **Confusion Matrix**
- **Classification Report**
- **Cross-Validation Scores**

---

## 🛠️ Technologies & Libraries

### Data Processing
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing

### Visualization
- **matplotlib** - Static plotting
- **seaborn** - Statistical data visualization

### Machine Learning
- **scikit-learn** - ML algorithms and preprocessing
- **xgboost** - Gradient boosting
- **TensorFlow/Keras** - Deep learning

### Model Interpretation
- **SHAP** - Explainable AI for model interpretability

### Utilities
- **joblib** - Model serialization

---



