# Easy Visa Project

## Overview

The **Easy Visa Project** aims to address the challenges faced by business communities in the United States in identifying and attracting the right talent. With a high demand for skilled human resources, companies often look for talented individuals both locally and abroad. This project leverages data analysis and machine learning to streamline the process of hiring foreign workers while ensuring compliance with U.S. immigration policies.

## Problem Statement

### Context
Business communities in the U.S. face challenges in sourcing qualified and hard-working individuals. The Immigration and Nationality Act (INA) allows foreign workers to enter the U.S. on a temporary or permanent basis. The Office of Foreign Labor Certification (OFLC) oversees job certification applications to ensure compliance with statutory requirements and protect U.S. workers' wages and working conditions.

### Objective
This project seeks to optimize the foreign labor certification process by using data-driven approaches to:
- Predict the likelihood of job certification approval.
- Identify factors influencing approval decisions.
- Provide actionable insights for employers and policymakers.

## Features
- **Data Analysis**: Comprehensive analysis of foreign labor certification data to uncover trends and insights.
- **Machine Learning Models**: Predictive models to estimate job certification outcomes.
- **Visualizations**: Clear and interactive visualizations to aid decision-making.


## Key Insights

- **Education Level**: The education level of employees, particularly high school and master's degrees, is the most critical factor, strongly influencing job performance and role alignment.
- **Job Experience**: Prior job experience significantly impacts performance, suggesting that experienced employees are better suited for the roles analyzed.
- **Prevailing Wage**: Competitive wages are crucial for job satisfaction and retention, highlighting the need for well-structured compensation packages.
- **Geographical Factors**: Regional and continental factors affect performance, indicating the need for location-specific strategies.
- **Model Performance**: The Tuned Gradient Boost and XGBoost Classifiers excel across all metrics, making them ideal for predictive tasks, while Decision Tree models, especially without tuning, are less effective.

## Business Insight

Business insights suggest that visa approval is more likely for applicants with higher education (Bachelor’s or above) and relevant job experience, especially if they come from Europe, Africa, or Asia. Focusing recruitment efforts on regions where demand aligns with educational qualifications—such as the Northeast for Master's degrees—can optimize success. Offering a prevailing wage around $72,000 or higher and preferring annual wage units over hourly ones also increases approval chances. Additionally, gathering data on employer wage offers and employee specialization can help tailor hiring strategies, improving alignment with trends that favor successful visa applications.

## Recommendations

- **Hiring**: Focus on candidates with relevant education and experience.
- **Model Deployment**: Use advanced models like Tuned Gradient Boost and XGBoost for reliable predictions.
- **Regional Strategies**: Customize hiring, compensation, and training based on regional needs.
- **Prioritization**: Prioritize applicants with higher education levels (Bachelor's, Master's, or Doctorate) and relevant job experience, as they have higher chances of visa approval.
- **Focus Regions**: Emphasize hiring from Europe, Africa, and Asia, and consider focusing on regions with greater demand for specific education levels (e.g., Master's in the Northeast).
- **Compensation**: Ensure that the prevailing wage meets or exceeds $72,000, and prefer applicants with annual wage units over hourly ones.
- **Data Collection**: Collect additional data on employer wage offers and employee specializations to refine the selection process further and align with trends observed in successful visa approvals.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/elijahcharles18/easy-visa-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd easy-visa-project
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Easy_Visa_Project.ipynb
   ```
2. Follow the instructions in the notebook to explore the data, train models, and visualize results.

## Technologies Used
- **Programming Languages**: Python
- **Libraries**:
  - Data Manipulation: `pandas`, `numpy`
  - Data Visualization: `matplotlib`, `seaborn`
  - Machine Learning:  `Stacking Classifier`, `Decision tree`, `Bagging Classifier`, `Random Forest`, `Adaboost Classifier`, `Gradient Boost Classifier`, `XGBoost Classifier`
   
- **Tools**: Jupyter Notebook

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
