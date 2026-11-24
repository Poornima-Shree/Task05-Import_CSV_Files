# Iris Flower Dataset Analysis 🌸

## 1. Project Overview

This project is about importing and analyzing CSV files using Python. I used the Iris Flower Dataset to understand how Pandas, NumPy, Matplotlib and Seaborn are used in data analysis.

The main goal of this project is to explore flower measurements, calculate basic statistics and visualize differences between Iris flower species.

## 2. Dataset Source

**Dataset Name:** Iris Flower Dataset

**Source:** UCI Machine Learning Repository

**Dataset Link:** https://archive.ics.uci.edu/dataset/53/iris

The dataset contains:
- 150 flower records
- 3 Iris species
- 4 numerical measurement columns
- 1 species column

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## 4. Project Structure

```text
iris_csv_analysis/
│
├── Iris_Dataset_Analysis.ipynb
└── README.md
```

## 5. Work Completed

1. Imported the required Python libraries.
2. Loaded the Iris CSV dataset using `pd.read_csv()`.
3. Created a Pandas DataFrame.
4. Displayed the first five rows using `head()`.
5. Checked dataset information using `info()`.
6. Checked dataset dimensions using `shape`.
7. Generated statistical summaries using `describe()`.
8. Checked missing values.
9. Performed numerical calculations using NumPy.
10. Created visualizations using Seaborn and Matplotlib.

## 6. Data Visualizations

### Chart 1: Number of Flowers in Each Species

This bar chart shows the number of flowers belonging to each Iris species.

**Observation:** Each species contains 50 flower records.

### Chart 2: Petal Length vs Petal Width

This colorful scatter plot compares petal length and petal width across the three Iris species.

**Color representation:**
- Red – Iris Setosa
- Blue – Iris Versicolor
- Green – Iris Virginica

**Observation:** Setosa generally has smaller petals, while Virginica has larger petals. Versicolor is generally between the two.

## 7. Findings

After analyzing the dataset, I found:

- The dataset contains 150 rows and 5 columns.
- There are three flower species: Setosa, Versicolor and Virginica.
- Each species has 50 records.
- There are no missing values in the dataset.
- Different Iris species have different petal measurements.
- Virginica generally has the largest petal measurements.

## 8. What I Learned

Through this project, I learned:

- How to import CSV files using Pandas.
- How to create and explore a DataFrame.
- How to use `head()`, `info()`, `describe()` and `shape`.
- How to perform numerical calculations using NumPy.
- How to create charts using Matplotlib and Seaborn.
- How to analyze and understand a public dataset.
- How to use Google Colab and GitHub for a Python project.

## 9. Conclusion

This project helped me understand the basics of data analysis using Python. I learned how to import a public dataset, explore its information, perform calculations and create visualizations.

It was a useful beginner-level project to improve my knowledge of Pandas and NumPy.

---

**Project:** Import CSV Files

**Level:** 1

**Module:** NumPy & Pandas

**Status:** Completed
