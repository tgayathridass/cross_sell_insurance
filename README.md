# cross_sell_insurance
---

## 📄 **Problem Statement**

### **Context:**
An insurance company that offers **Health Insurance** is exploring opportunities to cross-sell **Vehicle Insurance**. The company has historical customer data and wants to understand customer behavior and patterns that can help identify potential interest in Vehicle Insurance.

You are provided with a **test dataset** that contains customer information. Although it does not include the final purchase (`Response`), it is suitable for performing exploratory analysis using data engineering and modeling techniques.

---

### **Test Data Columns:**

| Column Name            | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `id`                   | Unique customer ID                                                          |
| `Gender`               | Gender of the customer                                                      |
| `Age`                  | Age of the customer                                                         |
| `Driving_License`      | 1 if customer has a driving license, 0 otherwise                            |
| `Region_Code`          | Encoded region code representing the customer’s location                    |
| `Previously_Insured`   | 1 if customer already has vehicle insurance, 0 otherwise                    |
| `Vehicle_Age`          | Age category of the vehicle (`< 1 Year`, `1-2 Year`, `> 2 Years`)           |
| `Vehicle_Damage`       | Indicates whether the customer had a vehicle damage in the past (Yes/No)    |
| `Annual_Premium`       | Yearly premium the customer pays for health insurance                       |
| `Policy_Sales_Channel` | Encoded channel through which the policy was sold                           |
| `Vintage`              | Number of days the customer has been associated with the company            |


