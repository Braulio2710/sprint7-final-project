# 📊 Sprint 7 Final Project – Customer Segmentation Analysis

## 📌 Project Overview

This project was completed as the final assignment for **Sprint 7** of the **TripleTen Data Analytics Bootcamp**.

The objective was to analyze customer service usage patterns for a telecommunications company by exploring call and messaging behavior. The analysis focused on customer segmentation, outlier detection, and the generation of business insights to support data-driven decision-making.

---

## 🎯 Business Objective

Identify customer usage patterns and behavioral segments by answering the following questions:

* What are the main service usage patterns among customers?
* Can customers be segmented based on their service consumption and age?
* Are there unusual usage behaviors (outliers) that require further investigation?
* What insights can support customer segmentation strategies?

---

## 📂 Dataset

The analysis was performed using a telecommunications customer dataset containing service usage information.

### Features

| Column                  | Description                   |
| ----------------------- | ----------------------------- |
| `age`                   | Customer age                  |
| `cant_llamadas`         | Number of phone calls         |
| `cant_mensajes`         | Number of text messages       |
| `total_minutos_llamada` | Total call duration (minutes) |

An enriched dataset (`user_profile`) was also created, including:

* `grupo_uso` (Low, Medium, High Usage)
* `grupo_edad` (Young, Adult, Senior)

---

## 📈 Analysis Workflow

The project followed these main steps:

1. Data loading and validation
2. Exploratory Data Analysis (EDA)
3. Missing value analysis
4. Outlier detection using the IQR method
5. Customer segmentation
6. Contingency table analysis
7. Data visualization
8. Business insights

---

## 📊 Analytical Techniques

The following techniques were applied:

* Exploratory Data Analysis (EDA)
* Descriptive Statistics
* IQR Outlier Detection
* Customer Segmentation
* Contingency Tables
* Data Visualization

---

## 📌 Key Findings

* Adult customers showed the highest overall service usage.
* Medium Usage was the dominant segment across all age groups.
* Customer behavior varied noticeably between age segments.
* The segmentation identified opportunities for targeted business strategies based on customer usage patterns.

---

## ⚠️ Limitations

* The analysis is descriptive and does not establish causal relationships.
* Customer segmentation was based on predefined business rules rather than machine learning techniques.
* The dataset does not include revenue, churn, or customer lifetime value metrics.
* No predictive models were developed in this project.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/sprint7-final-project.git
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook using Jupyter Notebook, VS Code, or Google Colab.

4. Run all cells from top to bottom.

---

## 📈 Future Improvements

* Develop churn prediction models.
* Apply clustering techniques such as K-Means for data-driven customer segmentation.
* Incorporate Customer Lifetime Value (CLV) analysis.
* Build interactive dashboards using Power BI or Tableau.

---

## 👨‍💻 Author

**Braulio Santiago Esquivel**

Data Analyst | Database Administrator

Currently expanding my skills in statistical analysis, business analytics, and machine learning through the TripleTen Data Analytics Bootcamp.
