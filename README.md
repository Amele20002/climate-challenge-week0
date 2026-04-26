# climate-challenge-week0
This project was set up using Git branching and CI workflow.git add README.
# 🌍 Climate Challenge Week 0

## 📌 Project Overview
This project is part of a climate data analysis challenge focused on understanding African climate trends leading up to COP32. The work involves Git version control setup, data cleaning, and exploratory data analysis using Python.

---

## 📁 Project Structure
climate-challenge-week0/
│
├── data/ # Raw and cleaned datasets (not pushed to GitHub)
├── notebooks/ # Jupyter notebooks for analysis
├── src/ # Source code (if needed)
├── scripts/ # Helper scripts
├── tests/ # Test files
├── .github/workflows/ # CI pipeline (GitHub Actions)
├── requirements.txt # Project dependencies
└── README.md # Project documentation

---

## 🧠 Task 1: Git & Environment Setup

In Task 1, I created a GitHub repository and set up a local development environment using a Python virtual environment (venv). I initialized Git, structured the project into organized folders, and configured a .gitignore file to exclude unnecessary files such as datasets and checkpoints.

I created a requirements.txt file and set up a GitHub Actions workflow for continuous integration, which installs dependencies using pip install -r requirements.txt.

I practiced proper Git workflow by creating a feature branch (setup-task), making multiple commits following Conventional Commits standards, and merging the branch into main using a Pull Request.

---

## 📊 Task 2: Data Profiling, Cleaning & EDA Approach

In Task 2, I worked with a climate dataset to perform data profiling, cleaning, and exploratory data analysis.

### Steps followed:
- Loaded dataset using pandas
- Added a Country column for identification
- Converted YEAR and DOY into datetime format
- Extracted Month column for seasonal analysis
- Replaced -999 sentinel values with NaN
- Checked and removed duplicate rows
- Performed summary statistics and missing value analysis
- Identified missing value percentages per column
- Planned outlier detection using Z-scores

### Data Cleaning Approach:
- Forward fill applied for continuous weather variables
- Rows with excessive missing values considered for removal
- Outliers analyzed using statistical thresholds

### Analysis Plan:
- Time series analysis of temperature and rainfall trends
- Correlation heatmaps for climate variables
- Distribution analysis of precipitation and temperature
- Seasonal pattern identification

---

## 🚀 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Git & GitHub
- GitHub Actions

---

## 📌 Author
Student working on climate data analysis and Git workflow practice.