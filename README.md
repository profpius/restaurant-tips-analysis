# 🍽️ Restaurant Tips Data Analysis

A data analysis project exploring tipping behavior 
at restaurants using Python and Jupyter Notebook.

---

## 📌 Project Overview

This project analyzes the **Tips dataset** to uncover patterns in how people tip at restaurants. We explore the relationships between tip amounts, total bills, day of the week, and group size.

**Key Questions Explored:**
- How are tips distributed overall?
- Does a higher bill lead to a higher tip?
- Which day of the week gets the highest tips?
- Does group size affect how much people tip?

---

## 📊 Dataset

- **Name:** Tips Dataset
- **Source:** Built into the [Seaborn](https://seaborn.pydata.org/) Python library (no download needed)
- **Size:** 244 rows × 7 columns
- **Columns:** `total_bill`, `tip`, `sex`, `smoker`, `day`, `time`, `size`

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3 | Programming language |
| Pandas | Data loading & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts & dataset |
| Jupyter Notebook | Interactive coding environment |

---

## 📁 Project Structure

```
restaurant-tips-analysis/
│
├── analysis.ipynb       # Main Jupyter Notebook with all analysis
├── README.md            # Project overview (this file)
├── requirements.txt     # Python dependencies
└── images/              # Saved chart images
    ├── tip_distribution.png
    ├── bill_vs_tip.png
    ├── tips_by_day.png
    └── tips_by_size.png
```

---

## 🚀 How to Run This Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/profpius/restaurant-tips-analysis.git
   cd restaurant-tips-analysis
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. Open `analysis.ipynb` and run all cells.

---

## 📈 Key Findings

- The **average tip** is around **$3.00**, with most tips falling between **$2 and $4**.
- There is a **positive relationship** between total bill and tip — bigger bills generally lead to bigger tips.
- **Weekends (Saturday & Sunday)** tend to see slightly higher tip amounts.
- **Smaller groups** tip a higher percentage of the bill compared to larger tables.

---

## 📦 Requirements

To install all required packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Or use the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

---

## 👤 Author

**Pius Victor**  
GitHub: [@profpius](https://github.com/profpius)
---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
