# Basic Statistics with Auto.csv

This repository contains teaching materials and a Jupyter Notebook for practicing basic statistics using the **Auto.csv** dataset.

## 🚀 Quick start

```bash
# 1. Clone this repo
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# 2. Create and activate a virtual environment (recommended)
python -m venv .venv
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
source .venv/bin/activate

# 3. Install requirements
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter lab   # or: jupyter notebook
```

Open the notebook under `/notebooks` and run the cells.

---

## 📁 Repository structure

```
<repo-root>/
├─ data/
│  └─ Auto.csv
├─ notebooks/
│  └─ Basic_Statistics.ipynb
├─ requirements.txt
└─ README.md
```

---

## 🧰 Requirements

- Python 3.9+
- [Jupyter Lab](https://jupyter.org/install)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 📓 Learning objectives

By working through the notebook, students will:

- Load and explore data with **pandas**
- Calculate descriptive statistics: **mean, median, quartiles**
- Understand measures of spread: **variance, standard deviation**
- Compute **standard error** and **confidence intervals**
- Filter and clean datasets in **pandas**
- Work with categorical variables (e.g., origin of cars)

---

## 🧑‍🏫 Instructor notes

- Place `Auto.csv` inside the `data/` folder.  
- Ensure students activate the correct virtual environment before running Jupyter.  
- Students can export results via **File → Download as → HTML** for submission.

---

## 📜 License

Educational use only.
