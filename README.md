# DBSCAN Clustering on Mall Customer Data

This project demonstrates **DBSCAN (Density-Based Spatial Clustering)** on *Mall Customers* dataset to segment customers based on purchasing behavior and income patterns.

DBSCAN is a powerful unsupervised clustering algorithm that identifies **dense regions of data** and labels sparse points as **noise/outliers**.

---

## Overview

In this analysis, we:

- Load the *Mall Customers* dataset.
- Preprocess important features like **Annual Income** and **Spending Score**.
- Apply **DBSCAN** to discover natural clusters without predefining cluster count.
- Visualize clusters along with outliers.
- Interpret customer segments for potential marketing insights.

---

**Key properties:**
- Does **not require specifying the number of clusters** beforehand.
- Detects **clusters of varying shapes**.
- Identifies **noise/outliers** effectively.
- Sensitive to parameters: *epsilon (ε)* and *min_samples*.

---

### 1. Clone the Repository

```bash
git clone https://github.com/SelvamathanS/DBSCAN-for-Mall-customer-analysis.git
````

### 2. Install Requirements

Create a virtual environment (optional):

```bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

*(If there’s a requirements.txt, install with `pip install -r requirements.txt`.)*

---

### 3. Run the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook DBSCAN.ipynb
```

Execute all cells to reproduce the clustering analysis and visualizations.

---
