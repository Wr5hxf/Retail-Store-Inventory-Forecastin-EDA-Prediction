# **Retail Store Inventory Forecastin EDA & Prediction**

This project focuses on predicting product demand across multiple retail regions using advanced machine learning regression models.  
It helps optimize inventory, pricing, and sales strategies — improving decision-making and reducing stock-related losses.  

## **Project Overview**

The goal is to design an AI-powered system that forecasts demand based on sales history, inventory, discounts, prices, and seasonal trends.  
It supports data-driven inventory planning and ensures products are available when and where needed.  

## **Tech Stack**

- **Python**  
- **Pandas, NumPy**  
- **Scikit-learn**  
- **Plotly, Matplotlib, Seaborn**  
- **Google Colab**  

## **Dataset Details**

The dataset contains the following attributes:  
- Inventory, Sales, Orders, Price, Discount, Competitor Price  
- Regions: North, South, East, West  
- Seasons: Spring, Summer, Autumn, Winter  
- Date Range: 2022–2024  

## **Process Workflow**

1. **Data Cleaning and Preprocessing**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature Engineering and Correlation Study**  
4. **Model Training:** Linear Regression, SVR, Decision Tree, KNN  
5. **Model Evaluation and Comparison**  
6. **Forecast Visualization and Insights**  

## **Model Evaluation Results**

| **Model** | **R² Score** | **MAE** | **RMSE** |
|------------|--------------|----------|-----------|
| Linear Regression | 0.9937 | 0.017 | 0.022 |
| Decision Tree | 0.9911 | 0.025 | 0.031 |
| SVR | 0.9822 | 0.043 | 0.047 |
| KNN | 0.9764 | 0.052 | 0.059 |

**Best Model:** Linear Regression — delivered the highest accuracy and lowest error rate.  

## **Key Insights**

- Demand peaks during summer and festive seasons.  
- Competitor pricing and discounts significantly impact purchase behavior.  
- Historical data patterns strongly predict future demand.  
- Regional trends show distinct buying behaviors across markets.  

## **Conclusion**

The **Linear Regression** model achieved an **R² score of 0.9937**, making it the most reliable choice for accurate demand forecasting.  
This system helps retail companies maintain ideal inventory levels, prevent stockouts, and improve profitability through smarter demand planning.  

## **Author**

**Waqar Ali**  
*Aspiring Data Scientist / AI–ML Engineer*  
[LinkedIn](https://www.linkedin.com/in/waqar-ali-bb45b1246/) | [Portfolio](#)
