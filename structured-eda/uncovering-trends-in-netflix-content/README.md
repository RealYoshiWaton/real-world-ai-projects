# Uncovering Trends in Netflix Content: What's Hot and What's Not
#### By *Saurabh Kudesia* | May 2025
[GitHub](https://github.com/saurabh-kudesia) | [Kaggle](https://www.kaggle.com/saurabhkudesia) | [LinkedIn](https://www.linkedin.com/in/saurabhkudesia/)

---
## Description
[Netflix](http://netflix.com/), one of the world's largest streaming platforms, offers a vast catalog of movies and TV shows spanning genres, countries, and decades. As the entertainment industry becomes increasingly data-driven, it is valuable to analyze what content Netflix provides, how it has evolved over time, and what patterns exist across titles, formats, and regions.

### Goals
The primary goal of this analysis is to explore and uncover insights from Netflix's content catalog using structured exploratory data analysis. Specifically, we aim to:

- Understand the composition and evolution of Netflix's catalog  
- Identify dominant patterns across countries and genres  
- Examine trends over time in content type  
- Investigate content diversity across regions and years    

### Key Themes
The analysis is structured around the following key themes:

- **Catalog Composition:** Is Netflix leaning more toward Movies or TV Shows?  
- **Geographic Trends:** Which countries dominate the catalog, and how diverse is the content?  
- **Temporal Analysis:** How has content volume and type evolved over time?  
- **Duration Trends:** What is the typical length of Netflix content?

### Data Dictionary
This project utilizes a dataset sourced from
[Kaggle](https://www.kaggle.com/datasets/octopusteam/full-netflix-dataset), provided by [Octopusteam](https://www.kaggle.com/octopusteam). It contains detailed metadata about Netflix's content.

> ⚠️ **Warning**
>
> Since the [original dataset](https://www.kaggle.com/datasets/octopusteam/full-netflix-dataset) is regularly updated, some analyses may not reflect the most current data. All results in this notebook are based on the dataset snapshot from May 30, 2025. For learning purposes, you can download the exact dataset used in these analyses [here](./data).

> 🔧🚧 **Heads-up: This Code Is a Work in Progress**
>
> I'm continuously improving and refining the code as time allows, but there’s no fixed schedule for updates or new features.

## Folder Structure
```
├── source/             # Jupyter notebooks with source code, model pipelines, and dependencies
├── data/               # Source data or data loaders
├── requirements.txt    # Python dependencies and versions
├── README.md           # Project-specific documentation
```
### Requirements
This project requires Python 3.8 or higher and Jupyter Notebook.

All required Python packages and their exact versions are listed in the [`requirements.txt`](./requirements.txt) file.

To install the dependencies, run the following command in your terminal or command prompt:

```bash
pip install -r requirements.txt
```
### Getting Started
To run this project locally and reproduce the analysis, follow these steps:

#### 1. Clone the Repository

```bash
git clone https://github.com/saurabh-kudesia/real-world-ai-projects.git
cd real-world-ai-projects/structured-eda/uncovering-trends-in-netflix-content/
````

#### 2. Set Up the Environment
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

#### 3. Launch the Jupyter Notebook
> ⚠️ Make sure you have Python installed, along with Jupyter Notebook.
> Specific package versions are listed in [`requirements.txt`](./requirements.txt).

```bash
jupyter notebook source/uncovering-trends-in-netflix-content-sk.ipynb
```

### License
© 2025 Saurabh Kudesia

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this code, provided you include proper attribution and retain the license notice.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
