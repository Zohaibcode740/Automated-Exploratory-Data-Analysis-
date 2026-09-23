# 📊 Automated Exploratory Data Analysis

An automated **Exploratory Data Analysis (EDA)** project built with Python and Jupyter/Google Colab.

This project analyzes the **Nepal weather and river dataset** and demonstrates how different Python EDA tools can be used to inspect, clean, visualize, and generate automated reports from a dataset.

---

## 🚀 Project Overview

The project performs automated exploratory data analysis on the `nepal.csv` dataset.

The notebook includes:

* Dataset requirement validation
* Dataset loading and inspection
* Column name cleaning
* Numerical and categorical column identification
* Basic statistical analysis
* Data visualization
* Automated EDA reports
* Interactive data exploration
* DataPrep report generation
* D-Tale interactive analysis

---

## 📁 Project Structure

```text
Automated-Exploratory-Data-Analysis-/
│
├── Main.ipynb
├── nepal.csv
├── dataprep_report.html
└── README.md
```

### Files

| File                   | Description                                                             |
| ---------------------- | ----------------------------------------------------------------------- |
| `Main.ipynb`           | Main Jupyter/Google Colab notebook containing the complete EDA workflow |
| `nepal.csv`            | Nepal weather and river dataset used for analysis                       |
| `dataprep_report.html` | Generated automated DataPrep EDA report                                 |
| `README.md`            | Project documentation                                                   |

---

## 📊 Dataset

The project uses `nepal.csv`.

The dataset contains:

* **13,390 records**
* **19 columns**
* Numerical attributes
* Categorical attributes
* Weather-related measurements
* Geographic information
* River and hydrological measurements

Some of the available attributes include:

* Date
* Location
* River
* Basin
* Latitude
* Longitude
* Elevation
* Precipitation
* Soil Moisture
* Rainfall
* Temperature
* Dew Point
* Relative Humidity
* Wind Speed
* Wind Gusts
* Wind Direction
* River Discharge

---

## 🔍 Dataset Validation

The notebook first checks whether the dataset satisfies the required conditions.

```text
Records > 10,000        : PASS
Numerical Attributes    : PASS
Categorical Attributes  : PASS
```

The dataset contains **13,390 records and 19 columns**, making it suitable for the project's EDA workflow.

---

## 🧹 Data Cleaning

The notebook performs basic preprocessing before analysis.

This includes:

* Loading the CSV file with Pandas
* Cleaning column names
* Converting column names into a consistent format
* Removing unnecessary characters from column names
* Handling duplicate column names
* Checking dataset dimensions
* Inspecting the first rows of the dataset

For example, column names are converted into a cleaner format such as:

```text
temperature_mean_c
river_discharge_m3s
relative_humidity_mean_pct
wind_speed_max_kmh
```

---

## 📈 Exploratory Data Analysis

The project uses several Python libraries and EDA tools to explore the dataset.

### Pandas

Used for:

* Loading the dataset
* Data inspection
* Data cleaning
* Statistical analysis
* Data manipulation

### NumPy

Used for numerical operations and data processing.

### Plotly

Used for interactive visualizations and charts.

### AutoViz

Used for automatically generating exploratory visualizations and identifying patterns in the dataset.

### DataPrep

Used to generate an automated HTML-based EDA report.

### D-Tale

Used for interactive exploration and analysis of the Pandas DataFrame.

---

## 📑 Automated DataPrep Report

The project generates an HTML report using **DataPrep**.

The generated report is available in:

```text
dataprep_report.html
```

The report provides automated analysis of the dataset, including distributions, statistics, and relationships between variables.

---

## 🖥️ D-Tale

The notebook also demonstrates how to launch **D-Tale** for interactive dataset exploration.

D-Tale provides a browser-based interface for exploring the Pandas DataFrame without manually writing every analysis command.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Google Colab
* Pandas
* NumPy
* Plotly
* AutoViz
* DataPrep
* D-Tale

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Zohaibcode740/Automated-Exploratory-Data-Analysis-.git
```

Move into the project directory:

```bash
cd Automated-Exploratory-Data-Analysis-
```

Install the main Python dependencies:

```bash
pip install pandas numpy plotly autoviz dtale
```

> **Note:** DataPrep can have compatibility requirements depending on the Python version. The notebook includes a separate Python 3.10 virtual environment setup for generating the DataPrep report.

---

## ▶️ Running the Project

### Google Colab

The easiest way to run the project is through Google Colab.

1. Open `Main.ipynb`.
2. Upload/open the notebook in Google Colab.
3. Make sure `nepal.csv` is available in the notebook environment.
4. Run the notebook cells in order.
5. Generate the EDA reports and visualizations.

### Local Jupyter Notebook

You can also run the notebook locally:

```bash
jupyter notebook Main.ipynb
```

---

## 📌 Project Workflow

```text
Load Dataset
     ↓
Validate Dataset Requirements
     ↓
Inspect Dataset
     ↓
Clean Column Names
     ↓
Identify Data Types
     ↓
Explore Numerical & Categorical Data
     ↓
Generate Visualizations
     ↓
Automated EDA
     ↓
Generate DataPrep Report
     ↓
Explore Data with D-Tale
```

---

## 🎯 Project Goals

The main goals of this project are to:

* Practice exploratory data analysis with Python
* Learn automated EDA techniques
* Work with real-world datasets
* Understand numerical and categorical data
* Generate automated data reports
* Explore multiple Python EDA libraries
* Learn interactive data analysis workflows

---

## 📚 Learning Outcomes

By working with this project, you can learn how to:

* Load and inspect large CSV datasets
* Clean and standardize column names
* Identify numerical and categorical variables
* Perform basic dataset validation
* Use Pandas for data analysis
* Create interactive visualizations with Plotly
* Generate automated EDA reports
* Explore datasets using D-Tale
* Work with Jupyter Notebook and Google Colab

---

## 🤝 Contributing

Contributions are welcome.

If you find a bug or have an idea for improving the project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Open a Pull Request.

Example:

```bash
git checkout -b improve-eda
git add .
git commit -m "improve EDA workflow"
git push origin improve-eda
```

Then open a Pull Request on GitHub.

---

## 📄 License

This project currently does not specify a license.

If you plan to allow others to freely use, modify, and distribute the project, consider adding an appropriate open-source license.

---

## 👨‍💻 Author

**Zohaibcode740**

GitHub: `https://github.com/Zohaibcode740`

---

⭐ If you find this project useful, consider giving the repository a star.
