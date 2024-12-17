# Data Science Professional Certification Course
# 🚀 **SpaceX Falcon9 First Stage Landing Prediction**

![Project Type](https://img.shields.io/badge/Project-Type%3A%20Data%20Science-blue)  
![Status](https://img.shields.io/badge/Status-Completed-success)  
![Tools Used](https://img.shields.io/badge/Tools-Pandas%20%7C%20Scikit--Learn%20%7C%20Dash%20%7C%20Folium%20%7C%20Plotly-orange)

## **Project Overview 📊**

This repository showcases the **SpaceX Falcon9 First Stage Landing Prediction** project, which was developed as part of the **IBM Data Science Professional Certification Course**.  
The objective of this project is to **predict the successful landing** of Falcon9 first-stage boosters using historical launch data. This prediction helps SpaceX reduce costs by determining reusability.

---

## **Project Objectives 🎯**

1. **Data Collection**: Retrieve launch data using APIs and web scraping.
2. **Data Preprocessing**: Clean and wrangle the collected data.
3. **Exploratory Data Analysis (EDA)**: Analyze patterns, trends, and correlations in the data.
4. **Model Development**: Use machine learning algorithms to predict the outcome of landings.
5. **Visualization**: Provide insights through visualizations and interactive dashboards.

---

## **Table of Contents 🗂️**

- [Key Features](#key-features-)
- [Dataset Description](#dataset-description-)
- [Technologies Used](#technologies-used-)
- [Project Workflow](#project-workflow-)
- [Installation Guide](#installation-guide-)
- [Usage](#usage-)
- [Results](#results-)
- [Project Files](#project-files-)
- [How to Contribute](#how-to-contribute-)
- [Author](#author-)
- [License](#license-)

---

## **Key Features 🧩**

- **API and Web Scraping**: 
   - Used **BeautifulSoup** to collect data from websites.
   - Leveraged APIs to fetch real-time launch data from SpaceX's sources.

- **Data Wrangling & Cleaning**:
   - Handled missing values and transformed data into a structured format using **pandas**.

- **SQL Integration**:
   - Stored, queried, and managed datasets using SQL.

- **Interactive Visualizations**:
   - Built **interactive dashboards** using **Dash** and **Plotly** for analysis.
   - Used **Folium** to visualize geospatial data (e.g., launch sites).

- **Machine Learning Model**:
   - Developed predictive models using **Scikit-learn** to determine the likelihood of successful rocket landings.

---

## **Dataset Description 📋**

The dataset consists of information about various SpaceX launches, including:  
- Launch site details  
- Payload mass  
- Orbit type  
- Flight number  
- Booster version  
- Launch success or failure status  

The data was collected from public APIs and web scraping (Wikipedia/SpaceX).

---

## **Technologies Used 🛠️**

The following tools and libraries were used for this project:

- **Programming Languages**: Python  
- **Data Collection**: APIs, BeautifulSoup (Web Scraping)  
- **Data Analysis & Wrangling**: pandas, numpy  
- **Data Visualization**: matplotlib, seaborn, Dash, Plotly, Folium  
- **Machine Learning**: Scikit-learn  
- **Databases**: SQL  
- **Environment**: Jupyter Notebook  

---

## **Project Workflow 🧵**

1. **Data Collection**:  
   - Used APIs and web scraping to gather historical SpaceX launch data.

2. **Data Preprocessing**:  
   - Cleaned and transformed raw data for modeling.

3. **Exploratory Data Analysis (EDA)**:  
   - Identified patterns and correlations through visualizations.

4. **Model Development**:  
   - Applied machine learning algorithms to classify successful landings.

5. **Visualization & Dashboard**:  
   - Created interactive maps and dashboards for analysis.

6. **Results**:  
   - Evaluated model performance and presented insights.

---

## **Installation Guide 💻**

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/gaganageethika/Data-Science-Professional-Certification-Course.git
   cd Data-Science-Professional-Certification-Course
   ```

---

### 2. **Set Up a Virtual Environment**

#### **a. Create a Virtual Environment**  
For **Windows**:
```bash
python -m venv venv
venv\Scripts\activate
```

For **Mac/Linux**:
```bash
python3 -m venv venv
source venv/bin/activate
```

#### **b. Verify Virtual Environment Activation**  
Run the following command to check if the virtual environment is active:

For **Windows**:
```bash
where python
```

For **Mac/Linux**:
```bash
which python
```

The path should point to the virtual environment folder (e.g., `venv/bin/python`).

---

### 3. **Install Dependencies**

Install the required libraries using the `requirements.txt` file:  
```bash
pip install -r requirements.txt
```

---

### 4. **Run Jupyter Notebook**

Start Jupyter Notebook to open and execute project files:  
```bash
jupyter notebook
```

---

### 5. **Open Project Files**

- Navigate to the folder where the repository is cloned.
- Open the relevant `.ipynb` files to view and execute:
   - **Data Collection**: `spacex_api_data.ipynb`
   - **EDA and Visualization**: `eda_and_visualization.ipynb`
   - **Model Development**: `model_development.ipynb`
   - **SQL Integration**: `spacex_sql_queries.ipynb`
   - **Interactive Dashboard**: `interactive_dashboard.py`

---

### 6. **Deactivate the Virtual Environment**

Once you're done, deactivate the virtual environment:  
```bash
deactivate
```

---

## **Results 📈**

The project successfully predicted the likelihood of Falcon9 first-stage booster landings.  
Key outcomes include:  
- Insights into critical factors influencing successful landings.  
- Interactive visualizations showing launch site distributions and landing patterns.  
- A classification model that achieved reasonable accuracy for predicting outcomes.

---

## **Project Files 📂**

The repository contains the following key files:

1. **Data Collection**  
   - `spacex_api_data.ipynb`: Fetches and saves SpaceX launch data using APIs and web scraping.

2. **Data Analysis**  
   - `eda_and_visualization.ipynb`: Performs Exploratory Data Analysis (EDA) and visualization.

3. **Machine Learning Model**  
   - `model_development.ipynb`: Builds and evaluates a classification model to predict successful landings.

4. **SQL Integration**  
   - `spacex_sql_queries.ipynb`: Contains SQL queries for the processed data.

5. **Interactive Dashboard**  
   - `interactive_dashboard.py`: Creates an interactive Dash-based visualization dashboard.

6. **Dependencies**  
   - `requirements.txt`: Contains all the required libraries for the project.

---

## **How to Contribute 🤝**

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add new feature or fix"
   ```
4. Push the branch to your forked repository:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Submit a Pull Request.

---

## **License 📚**

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this project, provided that appropriate credit is given.

For more details, see the [LICENSE](LICENSE) file in this repository.

---

**✈ Made with passion for Data Science! ✈**
