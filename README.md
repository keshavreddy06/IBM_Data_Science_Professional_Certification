# 🚀 Winning the Space Race with Data Science: SpaceX Falcon 9 Landing Prediction

> **IBM Data Science Professional Certificate – Applied Data Science Capstone**

## 📌 Project Overview

This project develops an end-to-end machine learning pipeline to predict whether the first stage of a **SpaceX Falcon 9** rocket will land successfully.

The successful recovery and reuse of Falcon 9 boosters significantly reduce launch costs, making landing prediction an important engineering and business problem. Using historical SpaceX launch data, this project explores the factors influencing landing success and develops predictive machine learning models to estimate landing outcomes.

---

## 🎯 Problem Statement

The objective of this project is to predict whether a Falcon 9 first-stage booster will successfully land after launch.

The project addresses the following questions:

- What factors influence Falcon 9 landing success?
- Which launch characteristics contribute most to successful landings?
- Which machine learning algorithm provides the highest prediction accuracy?

The target variable is a binary classification:

- **1** → Successful Landing
- **0** → Unsuccessful Landing

---

## 📂 Project Workflow

| Stage | Description | Technologies |
|--------|-------------|--------------|
| 01 | Data Collection using SpaceX REST API | Python, Requests, Pandas |
| 02 | Web Scraping from Wikipedia | BeautifulSoup |
| 03 | Data Wrangling & Feature Engineering | Pandas |
| 04 | Exploratory Data Analysis (SQL) | PostgreSQL |
| 05 | Exploratory Data Analysis (Visualization) | Matplotlib, Seaborn |
| 06 | Interactive Geospatial Analytics | Folium |
| 07 | Interactive Dashboard Development | Plotly Dash |
| 08 | Machine Learning Prediction | Scikit-learn |
| 09 | Final Presentation | PowerPoint / PDF |

---

## 🤖 Machine Learning Models

The following supervised learning algorithms were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

Hyperparameter optimization was performed using **GridSearchCV** with **10-fold cross-validation**, and model performance was evaluated using a held-out test dataset.

---

## 📊 Key Findings

- Launch success rates increased consistently between **2013 and 2020**.
- **Kennedy Space Center LC-39A** achieved the highest landing success rate.
- Lower payload missions generally exhibited higher landing success.
- Flight experience positively influenced booster recovery.
- Orbit type significantly affected landing outcomes.
- The **Decision Tree Classifier** achieved the highest prediction accuracy of approximately **94%**.

---

## 🛠️ Technologies Used

### Programming Languages

- Python
- SQL

### Python Libraries

- Pandas
- NumPy
- Requests
- BeautifulSoup
- Matplotlib
- Seaborn
- Folium
- Plotly Dash
- Scikit-learn

### Tools

- Jupyter Notebook
- PostgreSQL
- IBM Skills Network Labs

---

## 📁 Repository Structure

```text
├── 01. Data Collection API.ipynb
├── 02. Web Scraping.ipynb
├── 03. Data Wrangling.ipynb
├── 04. EDA with SQL.ipynb
├── 05. EDA with Visualization.ipynb
├── 06. Interactive Visual Analytics with Folium.ipynb
├── 07. Dash App.py
├── 08. Machine Learning Prediction.ipynb
├── 09. IBM Data Science Capstone Presentation.pdf
├── Spacex.csv
├── spacex_launch_dash.csv
└── spacex_launch_geo.csv
```

---

## 📚 Skills Demonstrated

- REST API Integration
- Web Scraping
- Data Cleaning & Preprocessing
- Feature Engineering
- SQL Querying
- Exploratory Data Analysis
- Data Visualization
- Interactive Geospatial Analytics
- Dashboard Development
- Supervised Machine Learning
- Hyperparameter Tuning
- Model Evaluation
- End-to-End Data Science Workflow

---

## 🙏 Acknowledgements

This project was completed as the capstone project for the **IBM Data Science Professional Certificate** offered through **Coursera**.

The notebook templates, datasets, and instructional materials were provided by **IBM Skills Network**. The data analysis, visualizations, feature engineering, machine learning implementation, model evaluation, and project deliverables contained in this repository represent my completed work based on the capstone requirements.

---

## 👨‍💻 Author

**Naredla Keshava Mani Dheekshith Reddy**

**M.Sc. Data Science**  
**University of Europe for Applied Sciences, Germany**
