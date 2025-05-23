# Data Science Learning Journey

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Learning-green.svg)](https://github.com/aakifahAsger)

My data science learning journey following a comprehensive Udemy course. This repository contains all my practice code, projects, and assignments as I explore the world of data science with Python.

## 📚 What I'm Learning

- **Python Fundamentals** - Variables, loops, functions, and data structures
- **Data Manipulation** - Pandas, NumPy for data cleaning and analysis
- **Data Visualization** - Matplotlib, Seaborn for creating insights
- **Statistical Analysis** - Descriptive and inferential statistics
- **Machine Learning** - Supervised and unsupervised learning algorithms
- **Data Cleaning** - Handling missing data, outliers, and data preprocessing

## 📋 Prerequisites

To run the notebooks and scripts in this repository:

- Python 3.13.1
- Jupyter Notebook or JupyterLab or VS code
- Git (for cloning the repository)


## 📁 Repository Structure

```
├── Week-01/                 # Python basics and fundamentals
├── Week-02/                 # Data manipulation with Pandas
├── Week-03/                 # Data visualization
├── Week-04/                 # Statistical analysis
├── Projects/                # Mini-projects and assignments
├── Datasets/                # Practice datasets
└── Notes/                   # Learning notes and cheatsheets
```

## 💻 Sample Code

### Data Loading and Basic Analysis
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

# Load dataset
df = pd.read_csv('dataset.csv')

# Basic info
print(df.head())
print(df.info())
print(df.describe())
```

### Data Visualization Example
```python
import seaborn as sns

# Create a simple plot
plt.figure(figsize=(10, 6))
sns.histplot(data=df, x='column_name')
plt.title('Distribution of Column Name')
plt.show()
```

## 🎯 Learning Goals

- [ ] Master Python programming fundamentals
- [ ] Understand data manipulation with Pandas and NumPy
- [ ] Create meaningful data visualizations
- [ ] Apply statistical concepts to real data
- [ ] Build and evaluate machine learning models
- [ ] Complete end-to-end data science projects
- [ ] Develop a portfolio of data science work

## 🤝 Connect & Learn Together

Feel free to:
- Check out my code and provide feedback
- Suggest improvements or better approaches
- Share your own learning resources
- Connect for data science discussions

If you're also learning data science, let's learn together!

## 📝 License

This project is for educational purposes. Feel free to use the code and learn from it!

## 👨‍💻 About Me

- **Aakifah Asger** - Aspiring Data Scientist
- Currently learning through comprehensive Udemy course
- Passionate about turning data into insights
- GitHub: [aakifahAsger](https://github.com/aakifahAsger)

## 🙏 Resources & Acknowledgments

- Udemy course instructor and content
- Python.org documentation
- Pandas and NumPy communities
- Kaggle for practice datasets
- Stack Overflow community for problem solving

## 📞 Contact

- GitHub: [@aakifahAsger](https://github.com/aakifahAsger)
- Open to feedback, suggestions, and learning discussions!

## 🗺️ Learning Progress

- [x] Set up Python environment
- [x] Started Udemy course
- [x] Complete Python fundamentals section
- [ ] First data analysis project
- [ ] Data visualization projects
- [ ] Machine learning basics
- [ ] Complete course capstone project

## 📊 Current Status

🎓 **Actively Learning** - Regularly updating with new code and projects as I progress through the course

---

⭐ If you find this repository helpful for your own data science journey, please consider giving it a star!
