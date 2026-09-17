# HR-Automation-Python
A Python automation pipeline using Pandas and NumPy to clean corporate recruitment records and calculate automated Time-to-Hire metrics.

# Automated HR Data Cleaning Pipeline (Python & Pandas)

## 📌 Project Overview
Manual data entry often leads to formatting inconsistencies and missing values in HR systems. This project features a **Python** automation script designed to handle data preprocessing, type-casting, and calculation workflows for a recruitment tracker containing 1,000+ rows of candidate metrics.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Libraries:** Pandas, NumPy
- **Environment:** Jupyter Notebook / Google Colab

## ⚙️ Core Automation Features
1. **Automated Formatting:** Automatically detects and converts text strings into standard `datetime` formats to prevent calculation breaking.
2. **Dynamic Metric Calculation:** Measures processing speed (**Time-to-Hire** in days) dynamically across active records.
3. **Null-Value Handling:** Gracefully segments missing fields (unhired candidates) using NumPy to eliminate data parsing errors (`#VALUE!`) in downstream systems.
