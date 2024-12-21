# **Telecom Churn Prediction Project**

---

## **Business Problem Overview**

In the telecom industry, customers often switch between service providers, leading to an average annual churn rate of **15-25%**. Considering that acquiring a new customer costs **5-10 times** more than retaining an existing one, **customer retention** has become a top priority for telecom companies. 

For many operators, retaining **highly profitable customers** is crucial to ensuring long-term business success. To achieve this, telecom companies need to predict which customers are at high risk of churn and take proactive measures to retain them.

---

## **Objective**

The primary goals of this project are:
1. **Analyze customer-level data** of a leading telecom firm.
2. **Build predictive models** to identify customers at high risk of churn.
3. Identify the **key indicators of churn** to guide retention strategies.

---

## **Understanding and Defining Churn**

### **Payment Models in Telecom**

1. **Postpaid Model**: Customers pay a monthly/annual bill after using the services. 
   - Churn is easily identifiable as customers inform the operator to terminate services.  
2. **Prepaid Model**: Customers pay/recharge in advance and use services.
   - **Challenge**: Churn is harder to detect as customers can simply stop using the services without informing the operator.

**Note**: This project focuses on the **prepaid model**, which is the dominant payment model in **India and Southeast Asia**.

### **Definitions of Churn**

1. **Revenue-Based Churn**: Customers who generate very little or no revenue over a specific period.  
   - *Limitations*: Some customers, like those in rural areas, may only receive calls or SMS without generating revenue.

2. **Usage-Based Churn**: Customers who show **zero usage** (no calls, internet, or SMS) over a given period.  
   - *Limitations*: Defining churn after a prolonged inactivity period may make retention efforts too late.

### **Project Definition**  
In this project, we use the **usage-based definition** of churn to identify customers at risk.

---

## **High-Value Customers and Revenue Impact**

In the **Indian and Southeast Asian markets**, **80% of revenue** comes from the **top 20% of customers**, referred to as **high-value customers (HVCs)**.  
- Reducing churn among high-value customers significantly reduces **revenue leakage** and enhances profitability.

---

## **Conclusion**

This project aims to predict churn for **prepaid customers** using a **usage-based definition**, with a special focus on **high-value customers**, to help telecom firms implement effective retention strategies.
