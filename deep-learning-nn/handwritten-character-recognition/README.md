# Handwritten Character Recognition with EMNIST
#### By *Saurabh Kudesia* | June 2025
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/saurabh-kudesia)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/saurabhkudesia)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saurabhkudesia/)

---
## Context  
The EMNIST dataset extends the MNIST dataset by providing handwritten characters derived from the [NIST Special Database 19](https://www.nist.gov/srd/nist-special-database-19). It consists of 28x28 pixel images formatted to be compatible with MNIST. Details on the dataset and its conversion are available in the original paper: [https://arxiv.org/abs/1702.05373v1](https://arxiv.org/abs/1702.05373v1).

> > 🔧🚧 **Heads-up: This Code Is a Work in Progress**
>
> I'm continuously improving and refining the code as time allows, but there’s no fixed schedule for updates or new features.


## Dataset  
This project uses the **EMNIST Letters** split, featuring 145,600 samples across 26 balanced letter classes. Additional resources:  

- [Readme](https://biometrics.nist.gov/cs_links/EMNIST/Readme.txt)  
- [Binary format (MNIST-style)](https://biometrics.nist.gov/cs_links/EMNIST/gzip.zip)  
- [Matlab format](https://biometrics.nist.gov/cs_links/EMNIST/matlab.zip)  
- [EMNIST paper](https://arxiv.org/abs/1702.05373v1)  

**Citation:**  
Cohen, G., Afshar, S., Tapson, J., & van Schaik, A. (2017). EMNIST: an extension of MNIST to handwritten letters.  
Retrieved from [http://arxiv.org/abs/1702.05373](https://arxiv.org/abs/1702.05373v1)

## Folder Structure
```
├── source/             # Jupyter notebooks with source code, model pipelines, and dependencies
├── data/               # Source data or data loaders
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
© 2025 Saurabh Kudesia

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this code, provided you include proper attribution and retain the license notice.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
