# Performance Analysis of Linear Models for Salary Prediction
#### By *Saurabh Kudesia* | Dec 2024
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/saurabh-kudesia)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/saurabhkudesia)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saurabhkudesia/)

---
## Description
This project demonstrates how to train and compare multiple regression models—Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Support Vector Regressor — to predict salary based on years of experience. The models are evaluated using key performance metrics, including R², Mean Absolute Error (MAE), Mean Squared Error (MSE), and others. The code allows users to input years of experience to predict salary and compare the accuracy of each model using both training and test data.

## Goals
The primary focus of this analysis is to assess how well these models predict salaries, with an emphasis on their ability to generalize. By analyzing metrics like R², MAE, and MSE, I aim to identify the most effective model and highlight potential areas for improvement.

## Data Dictionary
This project utilizes a dataset sourced from
[Kaggle](https://www.kaggle.com/code/saurabhkudesia/analysis-of-linear-models-with-salary-predictions).

> 🔧🚧 **Heads-up: This Code Is a Work in Progress**
>
> I'm continuously improving and refining the code as time allows, but there’s no fixed schedule for updates or new features.

## Folder Structure
```
├── source/             # Jupyter notebooks with source code, model pipelines, and dependencies
├── requirements.txt    # Python dependencies and versions
├── README.md           # Project-specific documentation
```
## Requirements
This project requires Python 3.8 or higher and Jupyter Notebook.

All required Python packages and their exact versions are listed in the [`requirements.txt`](./requirements.txt) file.

To install the dependencies, run the following command in your terminal or command prompt:

```bash
pip install -r requirements.txt
```
## Getting Started
To run this project locally and reproduce the analysis, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/saurabh-kudesia/real-world-ai-projects.git
cd real-world-ai-projects/structured-eda/uncovering-trends-in-netflix-content/
````

### 2. Set Up the Environment
Create a virtual environment (recommended) and install dependencies.

* **Using `pip`:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
```

Or manually install core libraries if `requirements.txt` is not present:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch the Jupyter Notebook
> ⚠️ Make sure you have Python installed, along with Jupyter Notebook.
> Specific package versions are listed in [`requirements.txt`](./requirements.txt).

```bash
jupyter notebook source/uncovering-trends-in-netflix-content-sk.ipynb
```

## License
© 2024 Saurabh Kudesia

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this code, provided you include proper attribution and retain the license notice.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
