# Customer Churn Analysis - Exploratory Data Analysis (EDA)

## Project Overview
This project performs a comprehensive exploratory data analysis on customer churn data to identify patterns and factors that influence customer retention. The analysis uses various visualization techniques to uncover insights about why customers churn and what characteristics distinguish retained customers from those who leave.

## Dataset Information
- **File**: Customer Churn.csv
- **Key Columns**:
  - Customer demographics (gender, senior citizen status, tenure)
  - Contract information (contract type, monthly charges, total charges)
  - Services subscribed (internet service, online security, tech support, etc.)
  - Payment information (payment method, billing method)
  - Target variable: Churn (Yes/No)

## Key Findings

### Overall Churn Rate
- **26.54%** of customers have churned

### Factors Influencing Churn

1. **Senior Citizen Status**
   - Senior citizens have a comparatively higher churn rate than younger customers

2. **Tenure**
   - Customers with longer service tenure tend to stay
   - Customers who subscribed for only 1-2 months have higher churn rates

3. **Contract Type**
   - **Month-to-month contracts**: Highest churn rate
   - **One-year contracts**: Moderate churn rate
   - **Two-year contracts**: Lowest churn rate
   - Longer-term contracts significantly improve customer retention

4. **Services & Add-ons**
   - Customers **without** security and support services churn more:
     - Online Security
     - Tech Support
     - Online Backup
     - Device Protection
   - Streaming services have less impact on churn compared to security/support services

5. **Internet Service Type**
   - **Fiber optic users**: Higher churn rate
   - **DSL users**: Lower churn rate
   - **No internet service**: Lowest churn rate

6. **Payment Method**
   - Customers using **electronic check** as payment method have the highest churn rate
   - Other payment methods show lower churn

7. **Gender**
   - No significant difference in churn between male and female customers

## Technologies & Libraries Used
- **Python 3.x**
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **matplotlib**: Data visualization
- **seaborn**: Statistical data visualization

## Project Structure
```
Customer-Churn-Analysis-EDA-/
├── ChurnAnalysis.ipynb          # Main analysis notebook
├── Customer Churn.csv           # Dataset
└── README.md                    # This file
```

## How to Run
1. Ensure Python and required libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook ChurnAnalysis.ipynb
   ```

3. Run the cells sequentially to perform the analysis and generate visualizations

## Data Preprocessing
- Replaced blank values in `TotalCharges` column with 0
- Converted `TotalCharges` to float data type
- Converted `SeniorCitizen` binary values (0/1) to categorical values (No/Yes)

## Recommendations
Based on the analysis, the following strategies can help reduce churn:

1. **Encourage longer-term contracts** over month-to-month plans
2. **Bundle security and support services** as part of retention packages
3. **Address fiber optic service issues** to improve customer satisfaction
4. **Promote alternative payment methods** to electronic check payments
5. **Implement targeted retention programs** for senior citizens
6. **Focus on early tenure engagement** - most churn happens in the first few months

## Author
This analysis was created as part of a customer churn analysis project.

**Last Updated**: January 2, 2026...
