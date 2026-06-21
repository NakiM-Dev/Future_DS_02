# 📊 Customer Churn & Retention Analysis Report

**Dataset:** Telco Customer Churn (7,043 customers)  
**Project Type:** Data Analytics / Business Intelligence  

---

## 1. Business Objective

This analysis aims to understand:

- Why customers leave the service  
- Which customer segments are most likely to churn  
- How long customers stay before leaving  
- What actions can improve retention and customer lifetime value  

This project simulates the role of a Data Analyst supporting a SaaS or subscription-based business.

---

## 2. Data Cleaning & Preparation

### Dataset Overview
- Total records: 7,043  
- Features: 21  
- Target variable: Churn (Yes/No)  

### Data Quality Checks

| Issue | Result |
|------|--------|
| Duplicate Customers | None found |
| Missing Values | 11 records in TotalCharges |
| Data Types | Converted TotalCharges to numeric |
| Churn Values | Valid (Yes/No) |

### Cleaning Steps
- Converted `TotalCharges` from text to numeric  
- Handled missing values (11 records)  
- Verified unique customer IDs  
- Standardized categorical fields  

---

## 3. Overall Churn Analysis

| Metric | Value |
|--------|------|
| Total Customers | 7,043 |
| Customers Churned | 1,869 |
| Churn Rate | 26.54% |

**Insight:**  
Approximately 1 in every 4 customers leaves the company, indicating a significant retention challenge.

---

## 4. Customer Lifetime Analysis

### Average Tenure

| Customer Status | Average Tenure (Months) |
|----------------|------------------------|
| Active Customers | 37.6 |
| Churned Customers | 18.0 |

**Insight:**  
Customers who churn leave much earlier than retained customers.  
Most churn occurs within the first two years of the customer lifecycle.

---

## 5. Churn by Contract Type

| Contract Type | Churn Rate |
|---------------|-----------|
| Month-to-Month | 42.71% |
| One Year | 11.27% |
| Two Year | 2.83% |

**Insight:**  
Month-to-month customers are significantly more likely to leave.

**Recommendation:**  
- Offer annual discounts  
- Loyalty rewards  
- Contract upgrade incentives  

---

## 6. Churn by Internet Service

| Internet Service | Churn Rate |
|-----------------|-----------|
| Fiber Optic | 41.89% |
| DSL | 18.96% |
| No Internet Service | 7.40% |

**Insight:**  
Fiber customers churn at more than double the rate of DSL customers.

**Possible Causes:**
- Pricing concerns  
- Service quality issues  
- Misaligned expectations  

**Recommendation:**  
Conduct targeted surveys and service quality reviews for Fiber users.

---

## 7. Churn by Payment Method

| Payment Method | Churn Rate |
|---------------|-----------|
| Electronic Check | 45.29% |
| Mailed Check | 19.11% |
| Bank Transfer (Auto) | 16.71% |
| Credit Card (Auto) | 15.24% |

**Insight:**  
Electronic check users are far more likely to churn.

**Recommendation:**  
Promote:
- Auto-pay enrollment  
- Credit card / bank transfer incentives  

---

## 8. Retention Drivers

### Online Security

| Service | Churn Rate |
|---------|-----------|
| No Security | 41.77% |
| Security Enabled | 14.61% |

### Tech Support

| Service | Churn Rate |
|---------|-----------|
| No Tech Support | 41.64% |
| Tech Support Enabled | 15.17% |

### Partner & Dependents Impact

- Customers with partners churn less (19.66%)  
- Customers with dependents churn less (15.45%)  

**Insight:**  
Support services and household stability significantly improve retention.

---

## 9. High-Risk Customer Segments

The most likely customers to churn are:

- Month-to-month contracts (42.71%)  
- Fiber optic users (41.89%)  
- No security service (41.77%)  
- No tech support (41.64%)  
- Electronic check users (45.29%)  

---

## 10. Key Business Recommendations

### 1. Convert Customers to Long-Term Contracts
- Annual discounts  
- Loyalty rewards  
- Upgrade incentives  

### 2. Improve Fiber Customer Experience
- Investigate network performance  
- Address pricing concerns  
- Improve service quality  

### 3. Bundle Retention Services
Include:
- Online security  
- Tech support  
- Device protection  

### 4. Encourage Automatic Payments
- Discounts for auto-pay  
- Easier onboarding  

### 5. Focus on Early Retention
Target first:
- 3 months  
- 6 months  
- 12 months  

---

## Executive Summary

### Key Findings
- Overall churn rate: **26.54%**
- Month-to-month contracts have highest churn: **42.71%**
- Fiber users churn: **41.89%**
- Electronic check users churn: **45.29%**
- Security & tech support reduce churn significantly
- Churned customers stay only **18 months vs 38 months**

### Strategic Focus
- Contract upgrades  
- Fiber service improvement  
- Bundled retention services  
- Automatic payment adoption  
- Early customer engagement  

---

## 📌 Outcome

These strategies are expected to:
- Reduce churn significantly  
- Improve customer lifetime value  
- Strengthen long-term revenue stability  