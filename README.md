# Students Performance Data Analysis

## 📌 Project Overview

This project focuses on exploring and analyzing students' performance data using Python. It uses Pandas, NumPy, Matplotlib, and Seaborn to inspect the dataset and understand students' scores and demographic details.

## 🎯 Objectives

- Load and explore the students' performance dataset.
- Display the first and last five records.
- Understand the dataset structure and summary statistics.
- Identify column names and dataset dimensions.
- Explore students' mathematics, reading, and writing scores.
- Analyze demographic information such as gender, parental education, lunch type, and test preparation course.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## 📂 Dataset

The project uses a preprocessed Students Performance dataset.

The dataset includes the following columns:

- `gender`
- `race/ethnicity`
- `parental level of education`
- `lunch`
- `test preparation course`
- `math score`
- `reading score`
- `writing score`

## ⚙️ Project Workflow

### 1. Import Libraries

Import NumPy, Pandas, Matplotlib, and Seaborn for data analysis and visualization.

### 2. Load the Dataset

Load the preprocessed student performance dataset into a Pandas DataFrame.

### 3. Data Exploration

- `head()` – Displays the first five rows.
- `tail()` – Displays the last five rows.
- `info()` – Shows column names, data types, and non-null counts.
- `describe()` – Provides summary statistics for numerical columns.
- `columns` – Displays all column names.
- `shape` – Shows the number of rows and columns.

### 4. Score Analysis

Select the following score columns to examine students' academic performance:

- Mathematics score
- Reading score
- Writing score

### 5. Demographic Analysis

Explore the demographic columns:

- Gender
- Race/ethnicity
- Parental level of education
- Lunch type
- Test preparation course

### 6. Unique Value Analysis

Use the `unique()` method to identify distinct values in selected columns, including gender, parental education, lunch, and test preparation course.

## 📊 Results

The program explores the dataset structure, summarizes numerical data, and identifies the different categories in students' demographic information. It also selects academic score columns for further analysis.

## 🚀 How to Run the Project

1. Download or clone the repository.

2. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

3. Place the dataset in the correct folder.

4. Update the dataset file path in the Python code if necessary.

5. Run `week_8.py` using Python or open it in Google Colab/Jupyter Notebook.

6. Review the displayed dataset information and analysis results.

## 📁 Project Structure

```text
Students-Performance-Analysis/
│
├── week_8.py
├── StudentsPerformance_preprocessed.csv
└── README.md
```

## 🏁 Conclusion

This project demonstrates the use of Python libraries for basic exploratory data analysis. It helps understand students' academic scores, demographic categories, and the overall structure of the dataset.

##
