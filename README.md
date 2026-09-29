# 📊 Students Performance — Statistical Analysis

Statistical analysis of student exam scores to uncover what factors influence academic performance, using Python, SciPy, and Matplotlib.

## 📌 Questions Answered
1. Are math, reading, and writing score distributions normal?
2. How strongly do the three subjects correlate with each other?
3. Which students are statistical outliers — and what makes them unusual?
4. Does test preparation actually improve math scores?
5. Do reading scores differ significantly between male and female students?

## 🔍 Key Findings
- All three subjects approximate normality visually, though Shapiro-Wilk formally rejects it at n=1000 (expected with large samples)
- Reading–Writing correlation is 0.955 — the strongest pair, both driven by shared language ability
- ~4–5% of students per subject fall beyond |z|>2, consistent with normal distribution theory
- Test prep adds ~5.6 points to math scores (t=5.70, p=1.54e-08) — statistically significant, but self-selection bias likely confounds causation
- Female students score 7.14 points higher in reading on average (t=7.96, p=4.68e-15) — significant association, not an established cause

## 🛠️ Tech Stack
- Python 3.14.2
- pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Files
| File | Description |
|---|---|
| `stats_report.ipynb` | Main analysis notebook |
| `data/StudentsPerformance.csv` | Original dataset |

## 📊 Dataset
[Students Performance in Exams — Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
