📊 NovaRetail+ Customer Behavior Analysis
Overview

This project explores the relationship between customer behavior and the annual revenue generated for NovaRetail+, a large e-commerce platform operating across Latin America.

The objective was to identify which customer characteristics and behaviors are most strongly associated with revenue generation, using a correlation-based analytical approach. The analysis focuses on discovering meaningful relationships while avoiding causal assumptions.

Through exploratory analysis, statistical correlation methods, and data visualization, the project provides business-oriented insights that can support customer retention, growth, and marketing strategies.

Business Problem

The Growth and Retention team at NovaRetail+ wanted to understand:

Which customer behaviors are most strongly associated with annual revenue generation?

Answering this question can help the company prioritize initiatives that improve customer engagement, retention, and long-term value.

Because the goal is to identify associations rather than establish cause-and-effect relationships, the analysis was designed as a correlational and exploratory study.

Dataset

The dataset contains information for 15,000 customers and includes demographic, behavioral, engagement, and business value variables.

Key Variables
Variable	Descriptionedad	Customer age
nivel_ingreso	Estimated annual customer income
visitas_mes	Monthly website/app visits
compras_mes	Monthly purchases
gasto_publicidad_dirigida	Advertising spend assigned to the customer
satisfaccion	Customer satisfaction score (1-5)
miembro_premium	Premium membership indicator
abandono	Customer churn indicator
tipo_dispositivo	Preferred device type
region	Geographic region
ingreso_anual	Annual revenue generated for the company

Target Variable: ingreso_anual

Project Objectives
Explore customer behavior patterns.
Identify variables associated with annual revenue.
Compare different correlation techniques depending on variable types.
Detect potentially misleading correlations.
Document assumptions and limitations.
Translate analytical findings into business recommendations.
Tools and Technologies
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Methodology
1. Data Exploration
Dataset inspection
Data type validation
Summary statistics
Missing value assessment
2. Data Preparation
Feature selection
Validation of analytical assumptions
Data cleaning and formatting
3. Exploratory Visualization

Visual techniques were used to identify patterns and potential relationships:

Correlation heatmaps
Scatter plots
Distribution analysis
4. Correlation Analysis

Different statistical approaches were applied according to the nature of the variables:

Pearson Correlation

Used for linear relationships between numerical variables.

Spearman Correlation

Used for monotonic relationships and non-normal distributions.

Point-Biserial Correlation

Used to evaluate relationships between binary and continuous variables.

Cramér's V

Used to measure associations between categorical variables.

5. Interpretation

Results were interpreted using the following framework:

Evidence → Statistical Relationship → Business Implication

Special attention was given to avoiding causal conclusions from correlational evidence.

Key Questions Investigated
Do more frequent purchases correlate with higher revenue?
Is customer satisfaction associated with greater annual value?
Are premium members more profitable than non-premium customers?
Does customer churn impact revenue generation?
Are there regional or device-related behavioral patterns?
Limitations
Correlation does not imply causation.
External factors not included in the dataset may influence customer behavior.
Results depend on the variables available in the dataset.
Findings should be validated through experimentation before making strategic decisions.
Business Value

The insights generated from this analysis can help NovaRetail+:

Improve customer retention strategies.
Optimize marketing investments.
Identify high-value customer segments.
Design future experiments and predictive models.
Prioritize initiatives that increase customer lifetime value.
Repository Structure
Plain Text
Project-NovaRetail/
│
├── data/
│ └── novaretail_comportamiento_clientes_2024.csv
│
├── notebooks/
│ └── NovaRetail_Analysis.ipynb
│
├── images/
│ ├── heatmap.png
│ ├── scatterplot_1.png
│ └── scatterplot_2.png
│
├── README.md
│
└── requirements.txt
Author

Luis Felipe Gómez Contreras

Data Analytics Portfolio Project developed as part of the TripleTen Data Analyst Program.
