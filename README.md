# 🐼 Pandas LeetCode Q&A

Welcome to my GitHub repository focused on solving **Pandas-related problems from LeetCode**.  
This is a personal collection of solutions using the **Pandas** library in Python — perfect for anyone looking to improve their data manipulation skills with real-world-style problems.

---

## 📌 What is Pandas?

[Pandas](https://pandas.pydata.org/) is a powerful and flexible open-source data analysis and data manipulation library for Python.  
It provides data structures like:

- `Series` – a one-dimensional labeled array
- `DataFrame` – a two-dimensional labeled data structure (like a table in SQL or Excel)

Pandas makes it easy to clean, filter, group, merge, and transform datasets efficiently.

---

## 🧠 Important Pandas Concepts & Keywords

Here are some common operations and functions that frequently appear in LeetCode Pandas problems:

| Concept               | Function/Method                         | Example Usage                               |
|-----------------------|------------------------------------------|---------------------------------------------|
| Filtering rows        | `df[df["column"] > 10]`                 | Select rows based on a condition            |
| Sorting data          | `df.sort_values(by="column")`           | Sort DataFrame by a column                  |
| Grouping data         | `df.groupby("column")`                  | Group by and apply aggregation              |
| Aggregations          | `.sum()`, `.mean()`, `.count()`, etc.  | Compute statistics                          |
| Merging/Joining       | `pd.merge(df1, df2, on="key")`          | Combine two DataFrames                      |
| Renaming columns      | `df.rename(columns={"old": "new"})`     | Change column names                         |
| Selecting columns     | `df["column"]` or `df[["col1", "col2"]]`| Access specific columns                     |
| Creating new columns  | `df["new"] = ...`                       | Add calculated fields                       |
| Dropping duplicates   | `df.drop_duplicates()`                  | Remove duplicate rows                       |
| Dealing with nulls    | `df.dropna()`, `df.fillna()`            | Handle missing data                         |

These functions are commonly used to replicate SQL-style queries in Pandas.

---

## 🎯 Purpose of This Repository

This repo contains solutions to **LeetCode's Pandas problems**, written in pure Python using the Pandas library.

The goals are to:

- Practice real-world data manipulation
- Improve fluency in Pandas
- Serve as a reference for future use or revision
- Help others learn through example code

---


> Problem files are named in the format: `problem-title.py`  
> Each solution file contains the code and may include sample data for testing.

---

## ⚙️ Requirements

Make sure you have Python and Pandas installed:

You can install pandas using pip:

```bash
pip install pandas
```
---
## ✍️ Contribution
Feel free to fork this repo, suggest improvements, or add your own solutions.
If you spot any errors or have better solutions — PRs are welcome!

---
## ⭐️ Support
If you find this helpful, leave a ⭐️ on the repo and share with fellow data lovers!

