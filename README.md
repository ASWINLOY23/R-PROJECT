# Enterprise Predictive Analytics Studio

An enterprise-style machine learning dashboard built using **R Shiny** for performing **Logistic Regression modeling**, predictive analytics, and interactive model evaluation.

This application enables users to upload datasets, configure predictors dynamically, train classification models, evaluate model performance using ROC/AUC metrics, and generate downloadable prediction outputs through an interactive dashboard interface.

---

# Features

## Dataset Management

* Upload CSV datasets dynamically
* Select target and predictor variables interactively
* Optional unique identifier selection

## Machine Learning Workflow

* Logistic Regression model training using `glm()`
* Configurable train-test split
* Binary classification support
* Automatic prediction probability generation

## Model Evaluation

* ROC Curve visualization
* AUC score calculation
* Confusion Matrix generation
* Accuracy metric calculation
* Sensitivity metric calculation
* Optimal threshold detection using ROC coordinates

## Interactive Dashboard

* Enterprise-style dashboard UI
* Interactive Plotly visualizations
* KPI summary cards
* Responsive layout using `shinydashboard`

## Prediction Export

* Download prediction outputs as CSV
* Includes probabilities and predicted classes

---

# Tech Stack

| Technology     | Purpose                   |
| -------------- | ------------------------- |
| R              | Programming Language      |
| Shiny          | Web Application Framework |
| shinydashboard | Dashboard UI              |
| Plotly         | Interactive Charts        |
| caret          | Model Evaluation          |
| pROC           | ROC & AUC Analysis        |
| DT             | Interactive Data Tables   |
| shinyWidgets   | Enhanced UI Components    |

---

# Required Packages

```r
install.packages(c(
  "shiny",
  "shinydashboard",
  "shinyjs",
  "shinycssloaders",
  "shinyWidgets",
  "pROC",
  "caret",
  "DT",
  "plotly"
))
```

---

# Running the Application

```r
library(shiny)

runApp()
```

Or directly run:

```r
shiny::runApp()
```

---

# Project Structure

```text
├── app.R
├── README.md
├── LICENSE
├── sample_data.csv
└── screenshots/
```

---

# Application Workflow

1. Upload CSV dataset
2. Select optional ID column
3. Choose target variable
4. Select predictor variables
5. Configure training percentage
6. Run Logistic Regression model
7. Analyze model performance
8. Download prediction results

---

# Example Use Cases

* Healthcare Risk Prediction
* Credit Risk Modeling
* Customer Churn Prediction
* Fraud Detection
* Insurance Analytics
* Marketing Response Modeling
* Clinical Outcome Prediction

---

# Highlights

* Modern enterprise-style UI
* Interactive analytics workflow
* End-to-end predictive modeling pipeline
* Dynamic variable configuration
* Downloadable prediction outputs
* Interactive ROC and distribution plots

---

# Future Enhancements

Potential future improvements:

* Class weighting implementation
* Feature importance visualization
* Additional ML algorithms
* Hyperparameter tuning
* Model explainability modules
* Database integration
* User authentication
* Deployment automation

---

# Deployment Options

This application can be deployed using:

* ShinyApps.io
* Posit Connect
* Docker
* AWS
* Azure
* Google Cloud Platform

---

# Author

Developed using R Shiny for interactive predictive analytics and machine learning workflows.

---

# Copyright

Copyright © 2026 Aswin Sankar

All rights reserved.

This source code may not be copied, modified, distributed, sublicensed, sold, or used commercially without explicit written permission from the author.

Commercial licensing is available for organizations, businesses, consultants, and deployment usage.

---

# Support

If you found this project useful:

* Star the repository
* Share feedback
* Connect for collaboration opportunities
