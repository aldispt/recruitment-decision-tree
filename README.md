# Recruitment Prediction System using Decision Tree 🌳

![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange?style=flat&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?style=flat&logo=pandas)

This project implements a **Decision Tree Classifier** to predict recruitment results (Accepted/Rejected) based on candidate attributes. It demonstrates the use of data preprocessing (Label Encoding) and model interpretation using Entropy-based decision rules.

## 📋 Dataset Overview

The dataset is created programmatically within the notebook and consists of the following attributes:

| Feature      | Description                                      | Values (Examples)          |
|--------------|--------------------------------------------------|----------------------------|
| `Pendidikan` | Education level of the candidate                 | S1, S2, D3                 |
| `Pengalaman` | Years of work experience                         | < 2 Thn, 2-5 Thn, > 5 Thn  |
| `Skill`      | Assessment of candidate's technical skills       | Tinggi (High), Rendah (Low)|
| `Wawancara`  | Interview performance result                     | Baik (Good), Buruk (Bad)   |
| **`Hasil`** | **Target Variable (Output)** | **Diterima (Accepted), Ditolak (Rejected)** |

## 🛠️ Tech Stack & Prerequisites

* **Python 3.x**
* **Pandas**: For data manipulation.
* **Scikit-Learn**: For the Decision Tree model and preprocessing.

To install the required dependencies, run:

```bash
pip install pandas scikit-learn
