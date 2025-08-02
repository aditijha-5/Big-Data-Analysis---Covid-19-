# 🦠 Big Data Analysis of COVID-19 Using PySpark

This project demonstrates how to perform scalable data analysis on a real-world COVID-19 dataset using Apache **PySpark** in **Google Colab**. It focuses on extracting insights such as top affected provinces and cities, handling missing data, and exploring basic correlations, all while leveraging PySpark's distributed data processing capabilities.

---

## 📌 Project Objective

To showcase how PySpark can be used to process and analyze large-scale datasets efficiently by:

- Aggregating COVID-19 cases by location (province/city)
- Handling missing values in big data pipelines
- Performing statistical correlation analysis
- Demonstrating the power of distributed data processing

---

## 🧰 Tools & Technologies

- **Python 3**
- **Apache PySpark**
- **Google Colab**
- **Pandas (optional)**
- **CSV data input**

---

## 📁 Dataset Overview

The dataset used contains COVID-19 case data across various cities and provinces.

**Columns include:**
- `case_id` – Unique identifier for each case
- `province` – State/province/region
- `city` – City name
- `infection_case` – Case type (group, visit, overseas, etc.)
- `confirmed` – Number of confirmed cases
- `latitude`, `longitude` – Geographical coordinates

---

## 🔍 Key Analysis Performed

- ✅ Dropped rows with missing/null values
- ✅ Grouped and summed confirmed cases by `province` and `city`
- ✅ Found top 10 regions with highest number of confirmed cases
- ✅ Calculated correlation between confirmed cases and latitude
- ✅ Aggregated average coordinates and cases for visual/statistical insights

