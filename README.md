# Demographic Data Analyzer

## Project Overview
This project analyzes demographic data using Pandas, based on a dataset extracted from the 1994 U.S. Census database. The goal is to answer several key demographic questions by processing the dataset in Python.

## Features
- Uses Pandas for data analysis
- Calculates statistics such as:
  - Racial representation in the dataset
  - Average age of men
  - Percentage of people with a Bachelor's degree
  - Income analysis based on education level
  - Work hours and income correlation
  - Country-wise income distribution
  - Most common high-income occupation in India
- Rounds all decimals to the nearest tenth

## Functionality
The `demographic_data_analyzer.py` script answers the following questions:
1. **How many people of each race are represented in this dataset?**
   - Output: Pandas Series with race names as index labels.

2. **What is the average age of men?**
   - Output: Float rounded to the nearest tenth.

3. **What is the percentage of people who have a Bachelor's degree?**
   - Output: Percentage rounded to the nearest tenth.

4. **What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?**
   - Output: Percentage rounded to the nearest tenth.

5. **What percentage of people without advanced education make more than 50K?**
   - Output: Percentage rounded to the nearest tenth.

6. **What is the minimum number of hours a person works per week?**
   - Output: Integer value.

7. **What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?**
   - Output: Percentage rounded to the nearest tenth.

8. **What country has the highest percentage of people that earn >50K, and what is that percentage?**
   - Output: Country name and percentage rounded to the nearest tenth.

9. **What is the most popular occupation for those who earn >50K in India?**
   - Output: String representing the most common occupation.

## Installation & Setup
### Requirements
- Python 3.x
- Pandas

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo-url.git
   ```
2. Navigate to the project directory:
   ```sh
   cd demographic-data-analyzer
   ```
3. Install dependencies:
   ```sh
   pip install pandas
   ```
4. Run the script:
   ```sh
   python demographic_data_analyzer.py
   ```

## Example Output
```python
{
    "race_counts": {
        "White": 27816,
        "Black": 3124,
        "Asian-Pac-Islander": 1039,
        "Amer-Indian-Eskimo": 311,
        "Other": 271
    },
    "average_age_men": 39.4,
    "bachelors_percentage": 16.4,
    "higher_education_rich": 46.5,
    "lower_education_rich": 17.4,
    "min_work_hours": 1,
    "min_workers_rich_percentage": 10.0,
    "highest_earning_country": "United-States",
    "highest_earning_country_percentage": 39.7,
    "top_IN_occupation": "Prof-specialty"
}
```

## Author
- Pulkit Jain
- Contact: jain.infosec@gmail.com



This is the boilerplate for the Demographic Data Analyzer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/demographic-data-analyzer
