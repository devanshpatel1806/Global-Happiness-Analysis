# 🌍 Global Happiness Report Analysis Using Python

## 📌 1. Project Introduction

The **Global Happiness Report Analysis** is a Python-based data analysis project that focuses on understanding happiness levels across different countries and geographical regions.

The project uses a real-world happiness dataset containing information about countries, happiness scores, economic conditions, social support, healthy life expectancy, freedom, generosity, and perceptions of corruption.

The main purpose of this project is to explore the dataset, clean and organize the data, perform statistical analysis, identify important patterns, and represent meaningful findings through graphical visualizations.

The complete analysis is developed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. An interactive menu-driven interface allows users to select different analysis operations and explore the dataset.

---

## 🎯 2. Project Objectives

The major objectives of this project are:

1. To understand and analyze the Global Happiness Report dataset.
2. To load and process real-world data using Python.
3. To identify and handle missing values in the dataset.
4. To check and remove duplicate records.
5. To perform exploratory data analysis (EDA).
6. To calculate statistical measures using Pandas and NumPy.
7. To analyze happiness scores across different countries.
8. To compare happiness-related information across geographical regions.
9. To understand the relationship between happiness and other contributing factors.
10. To create meaningful data visualizations using Matplotlib and Seaborn.
11. To develop an interactive menu-driven data analysis application.
12. To save cleaned data and analysis results for future reference.

---

## 🛠️ 3. Technologies and Libraries Used

The following technologies and Python libraries are used in this project:

| Technology / Library | Purpose |
|---|---|
| Python | Main programming language |
| Jupyter Notebook | Development environment |
| Pandas | Data loading, cleaning, manipulation, and analysis |
| NumPy | Numerical calculations and statistical operations |
| Matplotlib | Creating graphical visualizations |
| Seaborn | Statistical data visualization |
| ipywidgets | Creating an interactive menu-driven interface |

### Description of Libraries

**1. Python**

Python is the primary programming language used to develop the project. It provides simple and powerful tools for data analysis.

**2. Pandas**

Pandas is used to load CSV files, organize data into DataFrames, handle missing values, remove duplicates, filter records, and perform data analysis.

**3. NumPy**

NumPy is used for numerical operations and calculations, including statistical analysis of numerical columns.

**4. Matplotlib**

Matplotlib is used to create charts and graphs to represent happiness-related information visually.

**5. Seaborn**

Seaborn is used to create statistical visualizations and understand relationships between different numerical variables.

**6. ipywidgets**

ipywidgets is used to create interactive controls that allow users to select different operations from the menu without repeatedly entering commands in the terminal.

---

## 📊 4. Dataset Description

The project uses a dataset named **happiness.csv**.

The dataset contains information about 143 countries and includes 12 columns related to happiness scores and their contributing factors.

### Dataset Columns

| Column Name | Description |
|---|---|
| Country name | Name of the country |
| Regional indicator | Geographical region of the country |
| Ladder score | Overall happiness score |
| upperwhisker | Upper value of the happiness score interval |
| lowerwhisker | Lower value of the happiness score interval |
| Log GDP per capita | Information about economic conditions |
| Social support | Level of social support |
| Healthy life expectancy | Expected healthy lifespan |
| Freedom to make life choices | Level of freedom in making life decisions |
| Generosity | Measure related to generosity |
| Perceptions of corruption | Perception of corruption |
| Dystopia + residual | Additional component of the happiness score |

### Dataset Information

- Dataset file: `happiness.csv`
- Number of records: 143
- Number of columns: 12
- File format: CSV
- Data type: Structured tabular data

The dataset is loaded into a Pandas DataFrame for further processing and analysis.

---

## ⚙️ 5. Project Features and Functionalities

The project provides several features through an interactive menu-driven interface.

### 5.1 Data Loading

- Loads the original happiness dataset using Pandas.
- Reads CSV data into a DataFrame.
- Displays the dataset for examination.
- Allows users to inspect the available columns and records.

### 5.2 Data Exploration

Data exploration helps understand the structure and quality of the dataset.

The project supports examination of:

- First few records of the dataset.
- Dataset dimensions.
- Column names.
- Data types.
- Dataset information.
- Statistical summaries.
- Missing values.
- Duplicate records.

### 5.3 Data Cleaning

Data cleaning is performed to improve the quality and reliability of the dataset.

The cleaning process includes:

- Checking missing values.
- Identifying duplicate records.
- Handling missing numerical values.
- Removing duplicate records.
- Checking the cleaned dataset.
- Saving the cleaned data into a separate CSV file.

The cleaned dataset is stored as `cleaned_happiness.csv`.

### 5.4 Statistical Analysis

Statistical analysis is performed to understand the numerical information in the dataset.

The project uses Pandas and NumPy to perform calculations and examine numerical columns.

The analysis includes statistical measures such as:

- Mean
- Median
- Minimum value
- Maximum value
- Standard deviation
- Other descriptive statistics

These calculations help understand the distribution and variation of happiness-related factors.

### 5.5 Country-Wise Analysis

Country-wise analysis helps examine happiness information for individual countries.

It allows users to explore country-related records and understand the values of different happiness indicators.

### 5.6 Regional Analysis

Regional analysis helps compare happiness-related information across geographical regions.

It provides a way to explore differences between regions and understand how happiness scores and contributing factors vary.

### 5.7 Data Visualization

Data visualization is an important part of this project.

Matplotlib and Seaborn are used to represent numerical information through graphical charts.

Visualizations help users understand patterns, comparisons, and relationships more easily than examining raw data alone.

### 5.8 Interactive Menu-Driven Interface

The project includes an interactive menu-driven interface developed using ipywidgets.

Users can select the required operation using interactive controls.

The interface makes the project easier to operate and allows users to explore different analysis functionalities without manually writing separate commands.

### 5.9 Data Export

The project supports saving processed data and analysis results into CSV files.

This allows the user to access the results later without performing the entire analysis again.

---

## 📈 6. Data Visualization

The project uses graphical representations to make the analysis easier to understand.

The visualizations folder can contain the charts generated during the project.

The visualizations can include:

- Happiness score comparisons.
- Country-wise comparisons.
- Region-wise comparisons.
- Distribution of numerical variables.
- Relationships between happiness-related factors.
- Correlation analysis.

The charts help identify patterns and relationships within the dataset.

---

## 🔍 7. Exploratory Data Analysis (EDA)

Exploratory Data Analysis is performed to understand the dataset before drawing conclusions.

The EDA process includes:

1. Loading the dataset.
2. Examining the first and last records.
3. Checking the number of rows and columns.
4. Understanding column names and data types.
5. Generating descriptive statistics.
6. Identifying missing values.
7. Checking duplicate records.
8. Exploring numerical variables.
9. Comparing country and regional information.
10. Understanding relationships between numerical columns through visualizations.

EDA helps identify the important characteristics of the dataset and supports further analysis.

---

## 📁 8. Project Folder Structure

The project files are organized as follows:

```text
Global_Happiness_Analysis/
│
├── Global_Happiness_Analysis.ipynb
│
├── happiness.csv
│
├── cleaned_happiness.csv
│
├── main.py
│
├── visualizations/
│   ├── [Saved visualization files]
│
└── README.md
```

### File Description

| File / Folder | Description |
|---|---|
| `Global_Happiness_Analysis.ipynb` | Main Jupyter Notebook containing the analysis and interactive menu |
| `happiness.csv` | Original happiness dataset |
| `cleaned_happiness.csv` | Cleaned dataset after data preprocessing |
| `main.py` | Python source file |
| `visualizations/` | Stores generated charts and graphical outputs |
| `README.md` | Project documentation |

---

## 💻 9. Installation and Requirements

To run this project, Python and Jupyter Notebook must be installed on your computer.

### Step 1: Install Required Libraries

Open the terminal or Anaconda Prompt and execute:

```bash
pip install pandas numpy matplotlib seaborn ipywidgets
```

### Step 2: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 3: Open the Project

Open the project folder and select:

`Global_Happiness_Analysis.ipynb`

### Step 4: Run the Notebook

Run the notebook cells in the correct order.

Make sure that `happiness.csv` is present in the same project directory.

### Step 5: Use the Application

After executing the required cells, use the interactive menu to select the available data analysis operations.

---

## 🧪 10. Expected Project Output

After running the project, users can:

- View the original happiness dataset.
- Examine dataset information and statistical summaries.
- Identify and handle missing values.
- Check duplicate records.
- Generate a cleaned dataset.
- Perform numerical and statistical analysis.
- Explore country-wise and region-wise information.
- Generate graphical visualizations.
- Save processed data and analysis results.

The project presents information in both tabular and graphical formats.

---

## 🌟 11. Advantages of the Project

- Uses a real-world dataset.
- Demonstrates practical Python programming skills.
- Provides experience in data cleaning and preprocessing.
- Helps understand exploratory data analysis.
- Uses Pandas and NumPy for numerical data analysis.
- Provides graphical representations of data.
- Offers an interactive menu-driven interface.
- Organizes the analysis into a reusable Jupyter Notebook.
- Helps develop an understanding of data analytics concepts.

---

## 🔮 12. Future Scope

The project can be improved in the future by adding:

- Additional datasets from different years for historical comparisons.
- More advanced statistical analysis.
- Additional interactive charts.
- A web-based dashboard.
- More detailed country and regional comparisons.
- Advanced machine learning techniques for further research.

---

## 📝 13. Conclusion

The **Global Happiness Report Analysis Using Python** project demonstrates the practical application of Python in data analysis.

Through this project, the dataset is loaded, explored, cleaned, and analyzed using Pandas and NumPy. Matplotlib and Seaborn are used to create visualizations that help understand happiness scores and their contributing factors.

The interactive menu-driven interface makes it easier for users to perform different analysis operations and explore the dataset.

Overall, this project provides practical knowledge of data handling, data cleaning, exploratory data analysis, statistical calculations, and data visualization using Python.

---

## 👨‍💻 14. Author

**Name:** Devansh Patel

**Project Title:** Global Happiness Report Analysis Using Python

**Project Type:** Python Data Analysis Project

**Development Environment:** Jupyter Notebook

---

⭐ If you find this project useful, feel free to explore the repository and its source code.
