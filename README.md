# The Boston Consulting Group - Data Science Program

## PowerCo Churn Prediction Project

## Overview

PowerCo, a major gas and electricity utility company, partnered with BCG to address customer churn, especially in the SME segment, after the power liberalization in the European energy market. This project focuses on understanding the impact of price changes on customer churn and developing predictive models to mitigate churn through targeted strategies.

### Project Tasks

1. **Business Understanding and Hypothesis Testing**
   - Hypothesis: Price changes significantly affect customer churn.
   - Data required: Historical customer data, pricing data, churn indicators.
   - Approach: Develop a predictive model to identify at-risk customers sensitive to price changes.

2. **Exploratory Data Analysis**
   - Verified the correlation between price sensitivity and churn.
   - Key Findings: Price sensitivity correlates with churn; suggested additional data sources for model enhancement.

3. **Feature Engineering and Modelling**
   - Engineered features from available data and improved feature predictive power.
   - Utilized a Random Forest Classifier to predict churn probabilities.
   - Estimated potential cost savings by preventing churn using the model.

4. **Findings and Recommendations**
   - Abstract Slide Summary: Highlighted model accuracy, potential savings, and actionable insights.
   - Recommendations: Deploy the churn prediction model, continue data augmentation efforts, and monitor model performance.

## How to Use

### Prerequisites

- Python 3.7 or higher
- Required libraries (NumPy, Pandas, Scikit-learn)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/powerco-churn-prediction.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Navigate to the project directory:

   ```bash
   cd powerco-churn-prediction
   ```

2. Run the Jupyter notebooks:

   ```bash
   jupyter notebook
   ```

3. Explore the notebooks sequentially: `1_Business_Understanding.ipynb`, `2_Exploratory_Data_Analysis.ipynb`, `3_Feature_Engineering_Modeling.ipynb`, `4_Findings_Recommendations.ipynb`.

## Data Sources

- Historical customer data: _Add source details_
- Historical pricing data: _Add source details_
- Churn indicator: _Add source details_

## Acknowledgments

- This project was completed as part of the collaboration between PowerCo and BCG.
- Special thanks to the teams involved in data collection and processing.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to modify this template to suit your project’s specific details and add more sections or details as necessary. Ensure you replace placeholder texts with actual data sources, installation steps, and acknowledgments related to your project.
