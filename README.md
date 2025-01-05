# MarketingSalesPredictor


## **Problem Statement**

The task involves predicting future sales for businesses that offer products or services. Given the ever-changing market dynamics, it is crucial for businesses to forecast sales accurately, considering factors such as advertising spending, audience targeting, and the choice of advertising platforms.

### **Challenges:**

1. **Impact of Advertising Spend:** Assessing how varying levels of advertising expenditure influence sales is a complex challenge.
2. **Audience Segmentation:** Identifying and analyzing distinct audience segments to understand their impact on sales performance.
3. **Platform Selection:** Determining which advertising platforms yield the best outcomes in terms of sales generation.

### **Objective:**

The goal of this project is to develop a machine learning model using Python to predict future sales. The model should provide actionable insights on how advertising investments, audience segments, and advertising platforms interact to influence sales figures.

### **Importance:**

Accurate sales predictions are essential for businesses to fine-tune their advertising strategies, allocate resources more effectively, and quickly adapt to shifting market conditions.

### **Approach:**

This project employs machine learning techniques in Python, particularly regression analysis and predictive modeling, to develop a powerful sales prediction model.

### **Outcome:**

The successful implementation of this project will result in a reliable sales forecasting tool that will help businesses make informed decisions, optimize their marketing efforts, and achieve more accurate sales predictions.

---

## **Project Summary**

### **Objective:**

The primary aim of this data science project is to predict future sales for businesses. Key predictors include advertising expenditures, audience segmentation, and the choice of advertising platforms.

### **Scope:**

Sales prediction plays a pivotal role in guiding business decisions, particularly in the areas of advertising budgets and strategy. This project leverages Python and machine learning to forecast future sales based on the factors mentioned above.

### **Key Components:**

- **Advertising Expenditure Analysis:** Analyzing how advertising spend affects sales predictions.
- **Audience Segmentation:** Investigating how different audience groups contribute to variations in sales outcomes.
- **Platform Influence:** Studying how advertising platforms impact overall sales performance.

### **Implementation:**

Python will be the primary tool for applying machine learning algorithms. Techniques such as regression analysis and predictive modeling will be used to develop a robust sales prediction model.

### **Outcome:**

The project aims to provide a solid sales prediction model that empowers businesses to make data-driven decisions, improve advertising strategies, and enhance operational efficiency.

---

## **Results**

The R² score has been chosen as the key metric for evaluating the accuracy of the sales prediction model. After excluding models that showed signs of overfitting (with 100% R² scores on training data), the following regression models and their R² scores were selected:

| Sl. No. | Regression Model              |   Train R² (%) |   Test R² (%) |
|:--------|:------------------------------|---------------:|--------------:|
|    1    | Linear regression             |       88.98    |      90.99    |
|    2    | Linear regression tuned       |       88.98    |      90.99    |
|    3    | Lasso regression              |       81.82    |      83.65    |
|    4    | Lasso with alpha = 0.01       |       88.98    |      91.02    |
|    5    | Ridge regression              |       88.98    |      90.93    |
|    6    | Ridge with alpha = 1          |       88.98    |      90.93    |
|    7    | Decision tree tuned           |       87.06    |      82.02    |
|    8    | Random forest                 |       99.70    |      97.93    |
|    9    | Random forest tuned           |       84.24    |      84.11    |
|   10    | Gradient Boosting Regressor   |       99.87    |      98.17    |
|   11    | Gradient Boosting Regressor Tuned |    99.58    |      95.11    |

---

## **Conclusion**

In the ever-evolving world of product and service-based businesses, being able to predict future sales is essential. This project, conducted during the data science internship at Oasis Infobyte, focused on building a machine learning model for sales prediction. Below are the key findings:

### **Insights and Observations:**

1. Sales show a strong positive correlation with advertising expenses, particularly for TV and Radio ads, indicating the significant influence of these platforms.
2. A particularly strong relationship was observed between TV advertising spend and sales, highlighting the power of TV ads in driving sales.
3. The R² score, chosen as the evaluation metric, demonstrated the model's effectiveness in forecasting sales.
4. The Gradient Boosting Regressor emerged as the most successful model, achieving 99% accuracy in training and 98% in testing.

### **Key Takeaways:**

- Understanding the link between advertising expenditure and sales provides valuable insights for strategic decision-making.
- The selected machine learning model demonstrated strong predictive capabilities, providing a foundation for effective sales planning.
- The R² score serves as a reliable measure of the model’s ability to predict future sales trends.

This project not only highlights the complexities of sales prediction but also underscores the importance of data science in refining business strategies. The insights gained offer businesses actionable data for making informed decisions and planning future sales initiatives.

---
