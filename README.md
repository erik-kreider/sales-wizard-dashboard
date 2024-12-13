# Healthcare SalesWizard Dashboard

## Datasets
- **`healthcare_sales_dataset`**: For use in the Product Pricing, Bundling, and Territory Optimization modules.
- **`leadscore_dataset`**: For use in the Lead Scoring module.

## Application File
- **`app.py`**: The Streamlit executable file for running the application.

---

## Project Report

### Purpose & Audience
The Healthcare SalesWizard Dashboard is designed to assist healthcare sales managers and representatives in making data-driven decisions that optimize their sales strategies. The key audiences include:

- **Sales Managers**: Tools for prioritizing leads and optimizing sales territories.
- **Sales Representatives**: Insights to enhance selling techniques and improve conversion rates.
- **Product Managers**: Understanding market dynamics to optimize product bundling and pricing.

This application leverages machine learning models and data visualizations to streamline decision-making in the competitive healthcare market, where identifying unique variables is essential for profitable insights.

---

### App Architecture
The application is built using a modular architecture that ensures scalability and flexibility:

- **Frontend**: Built with Streamlit to provide an intuitive interface for data visualization and interaction.
- **Backend**: Developed using Python, utilizing libraries such as `scikit-learn` and `apriori` for machine learning model implementation.
- **Data Handling**: Uses synthetic and real-world datasets, including data cleaning, manipulation, and exploratory data analysis (EDA).

This architecture integrates multiple machine learning models, offering diverse functionalities while maintaining ease of use for end-users.

---

### Functionalities
The Healthcare SalesWizard Dashboard includes four primary functionalities:

1. **Sales Lead Scoring and Prioritization**
   - Utilizes an ensemble of machine learning classifiers in a pipeline.
   - Selects the best model to categorize leads into high, medium, or low priority.
   - Helps sales teams focus on the most promising opportunities.

2. **Sales Territory Optimization**
   - Clusters regions by growth potential using KNN (high or low growth).
   - Reduces dimensionality with PCA to four components explaining 95% of the variance.
   - Predicts growth categories using Random Forest models.

3. **Product Bundling**
   - Implements the Apriori algorithm to identify frequently purchased product combinations.
   - Enables strategic bundling for promotions or logistical improvements.

4. **Product Pricing**
   - Employs models such as XGBoost, Random Forest, and Linear Regression.
   - Provides pricing recommendations based on historical sales data, region, and customer size.
