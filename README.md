# Understanding the Drivers of Drinking Water Quality

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **What makes water safe to drink, and can available water quality measurements help us understand the answer?**

---

# 📋 Table of Contents

* [Overview](#-overview)
* [Why This Project?](#-why-this-project)
* [Business Context](#-business-context)
* [Stakeholders](#-stakeholders)
* [Research Questions](#-research-questions)
* [Analytical Objectives](#-analytical-objectives)
* [Project Objectives](#-project-objectives)
* [Dataset](#-dataset)
* [Analytical Philosophy](#-analytical-philosophy)
* [Project Structure](#-project-structure)
* [Project Roadmap](#-project-roadmap)
* [Success Criteria](#-success-criteria)
* [Current Status](#-current-status)
* [Technologies Used](#-technologies-used)
* [Project Evolution](#-project-evolution)
* [Getting Started](#-getting-started)
* [License](#-license)
* [About the Author](#-about-the-author)

---

# 📖 Overview

Safe drinking water is essential to public health, yet assessing water quality often requires interpreting several physicochemical measurements simultaneously. Understanding how these measurements relate to drinking water safety can support environmental monitoring, scientific research, and evidence-based decision-making.

This project investigates the relationship between key water quality indicators and drinking water potability through a structured analytical workflow. Rather than approaching the dataset as a machine learning exercise from the outset, the project emphasizes understanding the problem, evaluating the quality of the data, exploring meaningful patterns, and communicating findings that are both statistically sound and useful for decision-making.

The objective is not simply to analyze a dataset, but to demonstrate how analytical thinking can transform raw data into actionable insight.

---

# 🌍 Why This Project?

This project represents the intersection of my background in **Pure and Industrial Chemistry** and my transition into **Data Science**.

Instead of selecting a generic practice dataset, I intentionally chose a problem rooted in environmental science to demonstrate how analytical methods can be applied to real-world scientific questions.

My goal is to build projects that combine scientific reasoning, statistical thinking, and clear communication to produce analyses that are reproducible, interpretable, and valuable to decision-makers.

---

# 🏢 Business Context

Access to safe drinking water remains one of the world's most important public health challenges.

Water quality assessment supports decisions made by environmental agencies, water treatment facilities, researchers, and policymakers. These decisions often depend on understanding the relationship between multiple physicochemical properties rather than relying on a single measurement.

Although this project uses a publicly available dataset for educational purposes, the analytical workflow is designed to reflect the structured approach commonly used in professional data analysis and scientific investigations.

---

# 👥 Stakeholders

This analysis may be valuable to:

* Public health organizations responsible for water safety.
* Environmental scientists studying water quality.
* Water treatment facilities seeking to understand important water quality indicators.
* Government regulatory agencies responsible for monitoring drinking water standards.
* Researchers and students interested in environmental data analysis.

---

# ❓Research Questions

This project seeks to answer the following questions:

1. What does the dataset reveal about the quality and completeness of the available water samples?
2. Which variables contain missing or incomplete information?
3. How are the individual water quality measurements distributed?
4. Which characteristics differ between potable and non-potable water samples?
5. Are any observed differences statistically meaningful?
6. Which water quality indicators appear most informative when assessing drinking water potability?

---

# 🎯 Analytical Objectives

The analysis aims to:

* Assess the quality and completeness of the dataset.
* Explore the distribution of physicochemical water quality measurements.
* Investigate relationships between water quality indicators.
* Compare potable and non-potable water samples.
* Identify statistically meaningful patterns.
* Communicate findings through clear visualizations and evidence-based interpretation.

---

# 🚀 Project Objectives

Beyond answering analytical questions, this project also aims to:

* Demonstrate an industry-standard exploratory data analysis workflow.
* Produce a fully reproducible analysis from raw data to final report.
* Document every major analytical decision.
* Communicate insights to both technical and non-technical audiences.
* Build a portfolio project that reflects professional analytical thinking.

---

# 📊 Dataset

**Source**

Kaggle Water Potability Dataset

The dataset contains measurements describing several physicochemical properties of water samples.

| Variable          | Description                                    |
| ----------------- | ---------------------------------------------- |
| `ph`              | pH value of the water sample                   |
| `Hardness`        | Water hardness (mg/L)                          |
| `Solids`          | Total dissolved solids (ppm)                   |
| `Chloramines`     | Chloramines concentration (ppm)                |
| `Sulfate`         | Sulfate concentration (mg/L)                   |
| `Conductivity`    | Electrical conductivity (μS/cm)                |
| `Organic_carbon`  | Organic carbon concentration (mg/L)            |
| `Trihalomethanes` | Trihalomethane concentration (μg/L)            |
| `Turbidity`       | Water turbidity (NTU)                          |
| `Potability`      | Target variable (0 = Not Potable, 1 = Potable) |

---

# 🧠 Analytical Philosophy

This project follows one guiding principle:

> **Good analysis begins with understanding the problem before applying technical solutions.**

Rather than jumping directly into predictive modeling, the workflow emphasizes:

* Business understanding
* Data understanding
* Data quality assessment
* Exploratory analysis
* Statistical investigation
* Clear communication of findings

The objective is not only to produce accurate results, but also to ensure that every conclusion is transparent, reproducible, and supported by evidence.

---

# 📁 Project Structure

```text
water-quality-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   ├── 04_statistical_analysis.ipynb
│
├── reports/
│   ├── figures/
│   └── final_report.md
│
├── src/
│   ├── data_loader.py
│   ├── data_cleaner.py
│   ├── visualization.py
│   └── statistics.py
│
├── requirements.txt
├── LICENSE
└── README.md
```

---

# 🗺️ Project Roadmap

| Sprint   | Phase                        | Status         |
| -------- | ---------------------------- | -------------- |
| Sprint 1 | Business Understanding       | ✅ Complete     |
| Sprint 2 | Data Understanding           | 🔄 In Progress |
| Sprint 3 | Data Cleaning                | ⬜ Planned      |
| Sprint 4 | Exploratory Data Analysis    | ⬜ Planned      |
| Sprint 5 | Statistical Investigation    | ⬜ Planned      |
| Sprint 6 | Insights & Recommendations   | ⬜ Planned      |
| Sprint 7 | Optional Predictive Modeling | ⬜ Planned      |
| Sprint 8 | Final Documentation          | ⬜ Planned      |

---

# ✅ Success Criteria

The project will be considered successful if it:

* Produces a complete and reproducible analytical workflow.
* Documents every major analytical decision.
* Clearly distinguishes observations from interpretations.
* Supports conclusions with evidence rather than assumptions.
* Presents findings that are understandable to both technical and non-technical audiences.
* Provides practical recommendations while acknowledging the limitations of the analysis.

---

# 📌 Current Status

**Current Phase:** Sprint 2 — Data Understanding

The current objective is to understand the dataset before making any modifications.

Activities currently in progress include:

* Inspecting dataset dimensions.
* Reviewing variable types.
* Assessing missing values.
* Identifying duplicate records.
* Evaluating the target variable.
* Documenting initial observations.

At this stage, **no changes have been made to the original dataset**.

---

# 💻 Technologies Used

| Tool             | Purpose                        |
| ---------------- | ------------------------------ |
| Python           | Programming language           |
| Pandas           | Data manipulation and analysis |
| NumPy            | Numerical computing            |
| Matplotlib       | Data visualization             |
| Seaborn          | Statistical visualization      |
| SciPy            | Statistical analysis           |
| Jupyter Notebook | Interactive analysis           |
| Git & GitHub     | Version control                |

---

# 🔄 Project Evolution

Future iterations of this project will include:

* Comprehensive exploratory data analysis.
* Statistical hypothesis testing.
* Correlation and relationship analysis.
* Feature importance investigation.
* Business-focused recommendations.
* Optional predictive modeling.
* A professionally formatted analytical report.
* Interactive visualizations where appropriate.

---

# 🛠️ Getting Started

## Prerequisites

* Python 3.8 or later
* Git
* Jupyter Notebook

## Installation

Clone the repository:

```bash
git clone https://github.com/<Evianojay>/water-quality-analysis.git
```

Navigate into the project:

```bash
cd water-quality-analysis
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment.

Install dependencies:

```bash
pip install -r requirements.txt
```

Download the Kaggle Water Potability dataset and place the CSV file inside:

```text
data/raw/
```

Launch Jupyter Notebook and begin with:

```text
notebooks/01_data_understanding.ipynb
```

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 About the Author

I'm a Data Science learner with a background in **Pure and Industrial Chemistry** and a growing interest in applying data analytics to scientific and environmental problems.

This repository documents not only the technical aspects of the analysis, but also the analytical thinking behind each decision. It forms part of my long-term journey toward building reproducible, evidence-driven analyses that bridge science, technology, and decision-making.
