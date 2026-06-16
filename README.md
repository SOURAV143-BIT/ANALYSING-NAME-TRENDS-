# 👶 Analyzing Naming Trends Using Python

## 📖 Overview

This project analyzes baby naming trends in the United States using historical data from the Social Security Administration (SSA). The objective is to extract data from compressed ZIP files, perform exploratory data analysis (EDA), and visualize trends in baby names over time.

By leveraging Python and data analysis libraries, this project uncovers patterns in male and female births and identifies the most popular baby names across different years.

---

## 🎯 Project Objectives

* Extract and process baby name data from ZIP files.
* Analyze the number of male and female babies born each year.
* Identify the most popular baby names based on birth counts.
* Explore naming trends over time.
* Visualize insights using charts and graphs.

---

## 📂 Dataset

The dataset is provided by the U.S. Social Security Administration (SSA) and contains baby names registered each year along with gender and birth counts.

### Dataset Features

| Feature | Description            |
| ------- | ---------------------- |
| Name    | Baby Name              |
| Gender  | Male (M) or Female (F) |
| Births  | Number of Babies Born  |
| Year    | Year of Registration   |

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* ZipFile
* BytesIO
* Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Extraction

* Loaded the ZIP dataset.
* Extracted relevant yearly files.
* Combined all records into a single DataFrame.

### 2. Data Cleaning & Preparation

* Assigned appropriate column names.
* Added year information to each dataset.
* Merged multiple years into one dataset.

### 3. Gender-Based Analysis

* Calculated total male births.
* Calculated total female births.
* Compared gender distributions across years.

### 4. Popular Name Analysis

* Grouped records by baby names.
* Calculated total birth counts.
* Identified the Top 100 most popular names.

### 5. Trend Analysis

* Tracked popularity of specific names over time.
* Visualized changes in naming preferences.

---

## 📈 Visualizations

The project includes:

* Male vs Female Birth Count Bar Charts
* Top 10 Most Popular Baby Names
* Name Popularity Trend Graphs
* Birth Count Comparisons Across Years

---

## 🔍 Key Findings

* Certain names remain consistently popular across decades.
* Naming preferences evolve significantly over time.
* Male and female birth distributions can vary by year.
* Trend analysis reveals how cultural influences affect naming choices.

---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/Analyzing-Naming-Trends.git
```

### Install Dependencies

```bash
pip install pandas matplotlib
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

## 📁 Project Structure

```text
Analyzing-Naming-Trends/
│
├── Analyzing_Naming_Trends.ipynb
├── names.zip
├── README.md
└── images/
```

---

## 💡 Skills Demonstrated

* Data Extraction
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis
* Python Programming
* Pandas Data Manipulation

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in handling real-world datasets, performing exploratory data analysis, creating meaningful visualizations, and identifying trends using Python.

---

## 📜 Conclusion

This project demonstrates the effectiveness of Python for analyzing large datasets and extracting valuable insights. By studying baby naming trends, we can observe how cultural, social, and historical factors influence naming preferences over time.


This project demonstrates the effectiveness of Python for analyzing large datasets and extracting valuable insights. By studying baby naming trends, we can observe how cultural, social, and historical factors influence naming preferences over time.
