# 📘 Code Book — Python Data Analysis & Recommendation Projects

A collection of **Python-based data analysis, data cleaning, and recommendation projects** demonstrating practical use of Python, JSON data, Pandas, and data-processing techniques.

The repository contains multiple Jupyter Notebooks covering **data exploration, cleaning, social-network analysis, and recommendation logic**.

---

## 📌 Overview

This repository is a collection of hands-on Python projects created to practice and demonstrate core **Data Analytics and Python programming concepts**.

The projects work with JSON-based datasets and focus on:

* Loading and exploring data
* Identifying data-quality issues
* Cleaning and preprocessing data
* Working with JSON files
* Using Python data structures
* Analyzing user relationships
* Finding potential people to connect with
* Recommending pages a user might like
* Working with Pandas and Python functions

The goal is to transform raw data into **clean, structured information and meaningful recommendations**.

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **JSON**
* **Python Data Structures**

  * Lists
  * Dictionaries
  * Sets
  * Tuples
* **Functions**
* **Loops & Conditional Statements**
* **File Handling**
* **Data Cleaning**

---

## 📂 Repository Structure

| File                        | Description                           |
| --------------------------- | ------------------------------------- |
| `01Project.ipynb`           | Initial data exploration and analysis |
| `02Project_CleanData.ipynb` | Data cleaning and preprocessing       |
| `03People_might.ipynb`      | Finding people a user might know      |
| `Page_might_liked.ipynb`    | Page recommendation analysis          |
| `Data.json`                 | Original dataset                      |
| `Dumped_Data.json`          | Processed/stored dataset              |
| `cleaned_data.json`         | Cleaned dataset                       |

---

## 🔎 Projects

### 1. Data Exploration

**Notebook:** `01Project.ipynb`

The first stage focuses on understanding the raw dataset and its structure.

Key activities include:

* Loading JSON data
* Inspecting records
* Understanding users and their relationships
* Exploring lists and dictionaries
* Identifying potential data-quality issues
* Working with nested JSON data

---

### 2. Data Cleaning

**Notebook:** `02Project_CleanData.ipynb`

This project focuses on preparing raw data for further analysis.

The cleaning process includes:

* Identifying missing values
* Handling incomplete records
* Checking inconsistent data
* Processing nested data
* Removing or correcting invalid information
* Creating a cleaner and more structured dataset

The resulting data is stored in:

`cleaned_data.json`

---

### 3. People You Might Know

**Notebook:** `03People_might.ipynb`

This project demonstrates a simple **people recommendation system** based on user relationships.

The logic analyzes existing friendships and identifies potential connections based on shared relationships.

### Example Concept

If:

```text
User A → User B
User B → User C
```

The system can identify **User C as a potential connection for User A**, depending on the recommendation rules.

This demonstrates practical use of:

* Dictionaries
* Sets
* Loops
* Functions
* Relationship mapping
* Recommendation logic

---

### 4. Pages You Might Like

**Notebook:** `Page_might_liked.ipynb`

This project explores a simple **page recommendation system**.

The system analyzes pages already liked by users and uses relationships between users to identify pages that a user may be interested in.

The project demonstrates how user activity can be used to generate basic recommendations.

---

## 🔄 Data Workflow

The overall workflow followed in this repository is:

```text
Raw JSON Data
      ↓
Data Loading
      ↓
Data Exploration
      ↓
Identify Data Issues
      ↓
Data Cleaning
      ↓
Cleaned JSON Data
      ↓
Data Analysis
      ↓
Recommendation Logic
      ↓
People & Page Recommendations
```

---

## 🧠 Key Concepts Demonstrated

### Python

* Variables and data types
* Conditional statements
* Loops
* Functions
* List and dictionary operations
* Sets and tuples
* File handling
* JSON processing

### Data Analytics

* Data exploration
* Data cleaning
* Data transformation
* Structured data processing
* Relationship analysis
* Basic recommendation logic

### Problem Solving

The projects focus on converting real-world style problems into programmable solutions using Python data structures and logical algorithms.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Vishal0-ai/Code-book.git
```

### 2. Navigate to the Project

```bash
cd Code-book
```

### 3. Install Required Libraries

If required:

```bash
pip install pandas jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open any of the `.ipynb` files and execute the cells sequentially.

---

## 📊 Dataset

The repository uses **JSON-formatted data** containing information about users, their friendships, and pages they have interacted with.

Example structure:

```json
{
    "users": [
        {
            "id": 1,
            "name": "User",
            "friends": [2, 3],
            "liked_pages": [101]
        }
    ]
}
```

The raw and processed versions of the data are maintained separately to demonstrate the data-cleaning workflow.

---

## 🎯 Skills Demonstrated

This repository demonstrates practical skills in:

* **Python Programming**
* **Data Analysis**
* **Data Cleaning**
* **JSON Data Processing**
* **Pandas**
* **Data Structures**
* **Problem Solving**
* **Recommendation Logic**
* **Jupyter Notebook**
* **Data Preprocessing**

---

## 🚀 Future Improvements

Potential improvements to these projects include:

* Building more advanced recommendation algorithms
* Adding similarity-based recommendations
* Implementing SQL databases
* Creating visualizations for user relationships
* Building a Power BI dashboard
* Adding statistical analysis
* Developing an interactive application

---

## 👤 Author

**Vishal Yadav**

Aspiring **Data Analyst** with an interest in Python, SQL, Data Analytics, and Business Intelligence.

---

## ⭐ Repository

Explore the complete project:

[Vishal0-ai/Code-book on GitHub](https://github.com/Vishal0-ai/Code-book?utm_source=chatgpt.com)

If you find the project useful, consider giving the repository a ⭐.
