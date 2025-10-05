# Customer Churn Prediction

## **Business Problem Statement**

**Scenario:** You are a Data Scientist at a major telecommunications company. The business is losing customers at an alarming rate, and the executive team needs a predictive model to identify customers likely to churn (cancel their service) in the next month.

**Business Impact:**
- **Customer Acquisition Cost**: $500-1000 per new customer
- **Monthly Revenue Loss**: $50-200 per churned customer
- **Retention Campaign Cost**: $50-100 per targeted customer
- **Success Rate**: Retention campaigns have 60% success rate when properly targeted

**Your Mission:** Build an end-to-end machine learning pipeline that can predict customer churn with high precision, enabling proactive retention campaigns.

---

## **Learning Objectives**

1. **Analyze** real-world business data with missing values and inconsistencies
2. **Engineer** meaningful features from raw customer data
3. **Handle** imbalanced datasets common in business applications
4. **Build** and tune neural networks for binary classification
5. **Evaluate** models using business-relevant metrics beyond accuracy
6. **Interpret** model decisions for business stakeholders
7. **Design** production-ready ML pipelines with monitoring considerations

---

## **1. Project Overview and Data Understanding**

### **1.1 Industry Context: Telecommunications Churn**

**Customer churn** is one of the most critical business challenges in telecommunications. With intense competition and high customer acquisition costs, retaining existing customers is 5-25x more cost-effective than acquiring new ones.

**Key Business Challenges:**
- **Market Saturation**: Limited new customer growth opportunities
- **Price Competition**: Competitors offering aggressive pricing
- **Service Quality**: Network issues driving customer dissatisfaction
- **Contract Flexibility**: Month-to-month plans increase churn risk

### **1.2 Dataset Overview**

**Source**: Telco Customer Churn Dataset (Kaggle)  
**Business Context**: Real telecommunications company customer data  
**Prediction Target**: Will customer churn in the next month? (Binary: Yes/No)

**Data Categories:**

| **Category** | **Features** | **Business Relevance** |
|--------------|--------------|------------------------|
| **Demographics** | Gender, Age, Partner, Dependents | Customer life stage affects loyalty |
| **Services** | Phone, Internet, Security, Backup, etc. | Service bundle size impacts retention |
| **Account** | Contract, Payment Method, Billing | Contract terms strongly predict churn |
| **Usage** | Tenure, Monthly Charges, Total Charges | Usage patterns indicate satisfaction |

### **1.3 Business Questions to Answer**

1. **Who churns?** What customer profiles are most at risk?
2. **Why do they churn?** Which services/features correlate with churn?
3. **When do they churn?** How does tenure affect churn probability?
4. **How can we prevent it?** What interventions would be most effective?

### **1.4 Success Metrics**

**Model Performance:**
- **Precision**: % of predicted churners who actually churn (minimize false alarms)
- **Recall**: % of actual churners we successfully identify (minimize missed churners)
- **F1-Score**: Balanced measure for imbalanced data
- **AUC-ROC**: Overall discriminative ability

**Business Impact:**
- **Revenue Retention**: $$$ saved through successful interventions
- **Campaign Efficiency**: ROI of targeted retention campaigns
- **Customer Lifetime Value**: Long-term revenue impact