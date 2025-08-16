# 🦠 COVID-19 India Data Analysis & Visualization

This project demonstrates a data engineering and visualization pipeline that scrapes raw COVID-19 data from an API, processes it, and generates a dynamic "racing" bar chart visualization. This project showcases skills in data extraction, cleaning, and creating animated data visualizations.

-----

## 📊 Project Goal

The primary goal of this project is to provide a comprehensive workflow for analyzing COVID-19 case trends in India. It focuses on:

  * **API Data Extraction:** Fetching raw, unstructured data from `https://api.covid19india.org/raw_data.json`.
  * **Data Processing:** Cleaning, structuring, and aggregating the raw data into a usable format (e.g., daily confirmed cases per state).
  * **Dynamic Visualization:** Creating a **running bar chart**  to visually represent the evolution of total COVID-19 cases by state over time. This type of visualization effectively highlights trends and changes in rankings.

-----

## 🛠️ Technologies Used

  * **Python:** The core programming language.
  * **Requests:** A library for making API calls to fetch the raw JSON data.
  * **Pandas:** For data loading, cleaning, aggregation, and manipulation.
  * **Matplotlib & Pandas Plotting:** For creating static plots.
  * **`matplotlib.animation` or `bar_chart_race`:** For generating the animated running bar chart.

-----

## 📁 Project Structure

```
.
├── COVID-19-India.ipynb    
├── requirements.txt          # List of required Python libraries
└── README.md                 # This file
```

-----

## 📝 How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/satishf889/COVID19-india-analysis.git
    cd COVID19-india-analysis
    ```
2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the notebook:**
    
    Upon execution, the script will:
      * Fetch the raw data from the API.
      * Process the data to aggregate total cases per state over time.
 
## Snapshot from notebook
![Screenshot](https://github.com/satishf889/COVID19-india-analysis/blob/master/covid-19.png?raw=true)

#### Note: Data in this api is getting updated slowly so you might see differences in count.
