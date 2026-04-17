#  TMDb Movie Dataset Analysis

An exploratory data analysis (EDA) project using the TMDb (The Movie Database) dataset to uncover insights about movie profitability and director success.

---

## Overview

This project investigates a dataset of thousands of movies to answer two key research questions:

1. **Which movie genre generates the highest average profit?**
2. **Who is the most successful movie director based on audience engagement?**

The analysis was conducted using Python in a Jupyter Notebook environment.

---

##  Key Findings

- **Animation** is the most profitable genre on average, with consistently high budgets, revenues, and popularity scores.
- **Christopher Nolan** stands out as the most successful director in the dataset, with films like *Inception*, *Interstellar*, and *The Dark Knight* combining high ratings, strong audience engagement, and significant profitability.

---

##  Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Project Structure

```
├── Investigate_a_Dataset.ipynb   # Main analysis notebook
├── Investigate_a_Dataset.html    # Exported HTML version
└── README.md
``` 

---

## Limitations

- Movies with missing or zero budget/revenue values were removed, which reduced the dataset size.
- The analysis is **exploratory only** — no statistical tests were performed.
- Results describe patterns and should **not** be interpreted as evidence of causation.

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Investigate_a_Dataset.ipynb
   ```

---

##  Dataset

The dataset used is the **TMDb Movie Dataset**, which contains information on thousands of movies including budget, revenue, genres, directors, cast, ratings, and more.
