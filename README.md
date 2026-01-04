# Hostname Dataset Generator and Analysis with Python

## Project Overview

This project implements a complete data generation and analysis workflow using Python.  
It focuses on creating a realistic dataset of server hostnames, transforming the data into a structured format with Pandas, and performing exploratory data analysis through multiple visualizations.

The project demonstrates good practices in Python programming, data manipulation, and data visualization.

---

## Main Features

- Programmatic generation of server hostnames following predefined business rules.
- Extraction of structured information from hostnames:
  - Operating system
  - Environment
  - Country
  - Node number
- Creation and manipulation of a Pandas DataFrame.
- Export and import of data using CSV files.
- Data analysis and visualization using Matplotlib.

---

## Hostname Structure

Each hostname is composed of 8 uppercase alphanumeric characters:

- 1 character: Operating system  
- 1 character: Environment  
- 3 characters: Country code  
- 3 digits: Incremental node number  

---

## Functional Design

The project is organized around reusable functions, including:

- Hostname generation
- Attribute extraction (OS, environment, country)
- DataFrame creation from generated data

This modular approach improves readability, maintainability, and scalability.

---

## Data Analysis and Visualization

The project includes:
- Grouped bar charts to analyze hosts by country and environment.
- A multi-plot dashboard (2x2 grid) showing:
  - Operating systems grouped by country
  - Overall distribution of operating systems
  - Total hosts per country
  - Hosts grouped by country and environment

All visualizations are generated using Matplotlib and properly formatted for clarity.

---

## Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook / Google Collab  

---

## How to Run the Project

1. Open the notebook file in Jupyter Notebook or Google Colab.
2. Run the cells sequentially.
3. The dataset, CSV file, and visualizations will be generated automatically.

---

## Notes

This project showcases a complete workflow from data generation to analysis and visualization, using clean and structured Python code.
