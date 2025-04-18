# 📊 data-visualization-techniques
Notebook showcasing data visualization techniques for a Data Mining session.

## Overview

This project explores various data visualization techniques using **Jupyter Notebook** and **Python** libraries like `pandas`, `matplotlib`, and `pywaffle`.

We use cancer death rate data by age group over time, and global population data, to demonstrate how different charts communicate data differently.

### Goals:
- Showcase multiple data visualization types.
- Compare their use cases, strengths, and limitations.
- Provide clean, reusable code for similar analysis projects.

---

## 📁 Datasets Used

1. **content/Cancer Death Rates by Age**
   - `cancer-death-rates-by-age.csv`
   - Worldwide cancer death rates by age group.

2. **content/World Population Data**
   - `world_population.csv`
   - Population by country.

---

## 🛠️ Getting Started

1. Upload or clone this notebook into Google Colab or Jupyter.
2. Make sure the CSV files are uploaded or correctly linked.
3. Install any missing libraries:

```python
!pip install pywaffle
```

4. Run the notebook cells step-by-step.

---

## 🔍 Sections Overview

### 🔹 1. Raw Numbers

- **Single Value Display:**  
  Show a specific cancer death rate by year and entity.

- **Single Value with Indicator:**  
  Compare two years' data and highlight the change.

- **Bullet Chart:**  
  Compare actual value vs benchmark using a bullet bar.

---

### 📋 2. Tables

- Raw data shown as tables using `pandas`.
- Sorted by Entity for clarity.

---

### 📈 3. Change Over Time Visualizations

- **Line Chart:**  
  Trend of cancer death rates in the USA from 1990–2019.

- **Sparkline:**  
  Minimal time series showing change over years.

- **Connected Scatter Plot:**  
  Dots connected by lines to show chronological change.

- **Bar Chart:**  
  Side-by-side bars comparing years 1990, 2000, 2010, 2019.

- **Box Plot:**  
  Shows distribution and outliers in age-based death rates.

---

### 🧩 4. Part-to-Whole Visualizations

- **Pie Chart (2022):**  
  Country-wise share of world population.

- **Doughnut Chart (2000):**  
  Similar to pie but with center cutout.

- **Waffle Chart:**  
  Each square = one country grouped by continent.

- **Stacked Bar Chart:**  
  Population of top 7 countries over time.

- **Stacked Area Chart:**  
  (Planned / Optional) Layered view of cumulative trends.

---

## 📦 Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
from pywaffle import Waffle
```

Install `pywaffle` if not already installed:

```bash
!pip install pywaffle
```

---

## 📚 Learning Objectives

- Compare data visualization types.
- Practice with `pandas` and `matplotlib`.
- Create engaging and informative charts.
- Learn to communicate patterns clearly with visuals.

---

## 📬 Contact
Author: Aymen Besbes

Email: Aymen.besbes@outlook.com | Aymen.besbes@ensi-uma.tn

LinkedIn: https://www.linkedin.com/in/aymen-besbes-158837245/

---

## 📅 Project Timeline

- **Original creation date:** December 2023  
- **Upload to GitHub:** April 2025

