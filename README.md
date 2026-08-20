# 🐍 Complete Python for Data Analytics

**A self-built, notebook-by-notebook journey through Python — from first principles to real-world exploratory data analysis.**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Status](https://img.shields.io/badge/Status-Actively%20Growing-brightgreen?style=flat-square)](https://github.com/theaditya24/COMPLETE-PYTHON-FOR-DATA-ANALYTICS)

---

## 📌 Overview

This repository is a personal, structured curriculum for learning Python for data work — built as a collection of Jupyter notebooks that progress from core language fundamentals through pandas/NumPy data wrangling, visualization, SQL, and full exploratory data analysis (EDA) on real datasets.

It's meant to be read as a path, not a pile of notes: each topic builds on the one before it, ending in portfolio-ready EDA projects on datasets like Netflix, Airbnb, Zomato, and hotel bookings.

Useful if you're:
- Learning Python specifically for data analytics
- Preparing for data analyst interviews
- Looking for a clean, working reference for pandas/NumPy patterns
- Building EDA projects to add to a portfolio

---

## 🗂️ Repository Structure

```
COMPLETE-PYTHON-FOR-DATA-ANALYTICS/
│
├── 🧱 Python Foundations
│   ├── basic.ipynb
│   ├── Operators_and_BooleanFunctions.ipynb
│   ├── Conditional_statement.ipynb
│   ├── Function.ipynb
│   ├── OOPS.ipynb
│   ├── Strings.ipynb
│   └── Regex.ipynb
│
├── 📦 Data Structures
│   ├── List.ipynb
│   ├── List_Practice_Questions.ipynb
│   ├── Dictionary.ipynb
│   └── Set.ipynb
│
├── 🐼 Pandas & Data Wrangling
│   ├── pandas.ipynb
│   ├── Pandas Revision.ipynb
│   ├── Indexing.ipynb
│   ├── Filtering and Sorting in Pandas.ipynb
│   ├── 02_Filtering_&_Sorting/
│   ├── 03_Grouping/
│   ├── 04_Apply/
│   ├── Pivot.ipynb
│   ├── DFH.ipynb
│   ├── Sampling and Resampling.ipynb
│   ├── Date & Time Series.ipynb
│   └── Time Shifting & Resampling.ipynb
│
├── 🔢 Numeric Computing
│   └── Numpy.ipynb
│
├── 📊 Data Visualization/
│   ├── Data Visualization Practice.ipynb
│   └── DATA VISUALIZATION/       → charting notebooks
│
├── 🗃️ SQL
│   └── Raw_SQL.ipynb
│
├── 🌐 Working with APIs
│   ├── API.ipynb
│   └── TMDB API.ipynb
│
├── 🚀 Applied EDA Projects
│   ├── Netflix Data Analysis/
│   ├── Airbnb Data Analysis/
│   ├── Zomato Data EDA/
│   ├── Hotel Booking EDA/
│   ├── EDA and Feature Engineering/
│   ├── Business Case Studies/
│   ├── Project 1/
│   ├── Capstone Project/
│   ├── CRUD OPERATION PROJECT/
│   └── mini_project.ipynb
│
├── 🎯 Practice & Interview Prep
│   ├── Practice-Questions.ipynb
│   ├── Interview Practice.ipynb
│   ├── Interview Ques ( Theory ).ipynb
│   └── Extras.ipynb
│
└── 📄 Sample Datasets
    ├── coffee.csv, data.csv, csv_file.csv
    ├── mymoviedb.csv, prediction_data.csv, results.csv
    ├── file1.json … file5.json
    └── new.txt, untitled.txt
```

> Note: some root-level notebooks (`h.ipynb`, etc.) and data files are scratch/working files used while building the exercises above.

---

## 🧠 What You'll Learn

| Stage | Focus | Key Notebooks / Folders |
|---|---|---|
| **1. Foundations** | Variables, types, operators, control flow, functions, OOP, regex | `basic`, `Conditional_statement`, `Function`, `OOPS`, `Strings`, `Regex` |
| **2. Data Structures** | Lists, dictionaries, sets, and how to manipulate them | `List`, `Dictionary`, `Set` |
| **3. Data Wrangling** | Indexing, filtering, sorting, grouping, applying, pivoting, resampling | `pandas`, `Filtering and Sorting in Pandas`, `02_Filtering_&_Sorting`, `03_Grouping`, `04_Apply`, `Pivot` |
| **4. Numeric Computing** | Arrays and vectorized operations | `Numpy` |
| **5. Time Series** | Dates, time shifting, resampling | `Date & Time Series`, `Time Shifting & Resampling`, `Sampling and Resampling` |
| **6. Visualization** | Turning data into charts that tell a story | `DATA VISUALIZATION/`, `Data Visualization Practice` |
| **7. SQL Basics** | Querying data the relational way | `Raw_SQL` |
| **8. APIs** | Pulling and working with data from external APIs | `API`, `TMDB API` |
| **9. Applied EDA** | End-to-end analysis on real, messy datasets | `Netflix`, `Airbnb`, `Zomato`, `Hotel Booking EDA`, `Capstone Project` |
| **10. Interview Ready** | Theory and practice questions to test yourself | `Interview Practice`, `Interview Ques ( Theory )`, `Practice-Questions` |

---

## 🚀 Featured Projects

- 🎬 **Netflix Data Analysis** — Exploring Netflix's content catalog: genres, release trends, and content mix.
- 🏠 **Airbnb Data Analysis** — Cleaning and exploring listings data to surface pricing and location patterns.
- 🍽️ **Zomato Data EDA** — Restaurant-level analysis covering ratings, cuisines, and cost trends.
- 🏨 **Hotel Booking EDA** — Investigating booking patterns, cancellations, and demand trends.
- 📈 **Business Case Studies** — Applied analysis framed around real business questions.
- 🎓 **Capstone Project** — A full dataset analyzed end-to-end, tying together the whole pandas + visualization toolkit.
- 🛠️ **CRUD Operation Project** — Applying core Python logic to build and manage data records.

---

## ⚙️ Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/theaditya24/COMPLETE-PYTHON-FOR-DATA-ANALYTICS.git
cd COMPLETE-PYTHON-FOR-DATA-ANALYTICS
```

**2. (Recommended) Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
```

**3. Install the core libraries**
```bash
pip install numpy pandas matplotlib seaborn jupyter requests
```

**4. Launch Jupyter**
```bash
jupyter notebook
```

Then open any `.ipynb` file and start exploring — follow the structure above topic by topic, or jump straight into one of the applied EDA projects.

---

## 💡 Who This Is For

- 🐣 **Beginners** taking their first steps into Python
- 🎯 **Aspiring Data Analysts** building a portfolio of real EDA work
- 📚 **Students** preparing for interviews or coursework
- 🔁 **Developers** brushing up on Python + pandas fundamentals

---

## 🛣️ Roadmap

- [x] Python fundamentals & data structures
- [x] Pandas & NumPy deep dive
- [x] Visualization notebooks
- [x] Real-world EDA projects (Netflix, Airbnb, Zomato, Hotel Booking)
- [x] Working with REST APIs
- [ ] Statistical analysis & hypothesis testing
- [ ] Expanded SQL for analytics
- [ ] Power BI / Tableau dashboard integration
- [ ] End-to-end analytics case studies

---

## 🤝 Contributing

Suggestions, corrections, and new practice notebooks are welcome. Open an issue or submit a pull request if you'd like to improve a notebook or add a new project.

---

## 👨‍💻 Author

**Aditya Raj**
B.Tech, Computer Science & Engineering
Aspiring Data Analyst · Python Developer

[![GitHub](https://img.shields.io/badge/GitHub-theaditya24-181717?style=flat-square&logo=github)](https://github.com/theaditya24)

---

### ⭐ If this repository helped you learn, consider giving it a star — it helps others find it too!
