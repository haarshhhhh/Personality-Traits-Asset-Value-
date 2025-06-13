# Personality-Traits-Asset-Value-
# 💼 Personality Traits & Asset Value Analysis (GBP-Focused)

This project analyzes how individual personality traits relate to asset holdings (in GBP only). Data was sourced from a Supabase API and explored using Python with pandas, seaborn, and matplotlib. The goal was to uncover behavioral patterns among asset holders and document insightful visualizations and metrics.

---

## 🧠 Key Insight

**Highest asset value (in GBP) individual risk tolerance: 0.555**  
The top GBP holder has £542.86 in assets and exhibits a moderate risk tolerance.

---

## 📁 Project Structure
## 🔍 Files
- `assets.csv` – Raw asset data
- `personality.csv` – Raw personality data
- `eda_analysis_script.py` – Full Python analysis
- `EDA_Insights_Report.docx` – Written summary


---

## 🔍 Exploratory Data Analysis Highlights

### ✅ Descriptive Statistics (GBP Holders)
- Mean GBP asset value: £222.25
- Max GBP asset value: £542.86
- Min GBP asset value: £100.52
- Sample size: 122 individuals

### ✅ Correlations
- `confidence` ↔ `composure`: **0.53**
- `confidence` ↔ `risk_tolerance`: **0.92**
- `asset_value` shows **weak correlation** with any psychological trait

### ✅ Visual Insights
- 📈 Scatter plots indicate only **slight negative trends** between impact_desire/composure and asset value
- 🔥 Personality correlation heatmap helps visualize latent patterns among traits

---

## 📊 Visualizations Included
- Heatmap of personality correlations

- Risk Tolerance vs. Asset Value

---

## 🛠 Tools & Technologies

- **Python** – pandas, seaborn, matplotlib
- **Google Colab** – used for running and exporting notebook
- **Supabase API** – data source for `assets.csv`
- **MS Word** – for generating a professional summary

---

## 🚀 How to Run the Analysis

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install pandas seaborn matplotlib python-docx

