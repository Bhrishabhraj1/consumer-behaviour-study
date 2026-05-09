# 📊 Consumer Behaviour & Brand Perception Study
> **MBA Project – Marketing Management** | Bhrishabh Raj

## 📌 Overview
A primary research-based marketing analytics project analysing purchase intent, brand loyalty drivers, and consumer segmentation across 150 respondents. Applies core MBA frameworks — STP, AIDA, and BCG Matrix — backed by Python statistical analysis.

**Key Results:**
- ✅ **Brand Trust (r=0.52)** is the strongest predictor of Purchase Intent
- ✅ **25–34 age group** identified as highest-value target segment
- ✅ **Social Media (35%)** dominates as the primary information channel
- ✅ **Brand A & C** qualify as BCG "Stars" — recommend increased investment

---

## 🛠️ Tech Stack
| Category | Tools |
|---|---|
| Language | Python 3.8+ |
| Data Manipulation | Pandas, NumPy |
| Statistical Testing | SciPy (Pearson, ANOVA, T-test) |
| Visualisation | Matplotlib, Seaborn |
| Frameworks Applied | STP, AIDA Model, BCG Matrix |

---

## 📁 Project Structure
```
consumer-behaviour-study/
│
├── consumer_behaviour_study.py   ← Main script (run this)
├── requirements.txt              ← Python dependencies
├── README.md                     ← You are here
│
└── outputs/ (auto-generated after running)
    ├── eda_consumer_behaviour.png    ← EDA charts (brand, age, channels)
    ├── framework_analysis.png        ← STP, AIDA, BCG Matrix, correlation
    ├── marketing_recommendations.png ← Actionable strategy report
    └── survey_data.csv               ← Full synthetic survey dataset
```

---

## 🚀 Step-by-Step Setup & Run Guide

### Step 1 — Prerequisites
Make sure Python 3.8 or above is installed:
```bash
python --version
```

### Step 2 — Clone or Download the Repository
```bash
git clone https://github.com/Bhrishabhraj1/consumer-behaviour-study.git
cd consumer-behaviour-study
```

### Step 3 — Create a Virtual Environment (Recommended)
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### Step 4 — Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 5 — Run the Project
```bash
python consumer_behaviour_study.py
```

### Step 6 — View Outputs
Four output files will be saved in the same folder:

| File | What it shows |
|---|---|
| `eda_consumer_behaviour.png` | Brand preference, age distribution, info channels, loyalty tiers |
| `framework_analysis.png` | STP perceptual map, AIDA funnel, BCG Matrix, trust–intent scatter |
| `marketing_recommendations.png` | 7 data-backed strategy recommendations |
| `survey_data.csv` | Full dataset — open in Excel / Google Sheets |

---

## 📐 Marketing Frameworks Applied

### 🎯 STP (Segmentation–Targeting–Positioning)
- **Segment** customers by age group and loyalty tier
- **Target** the 25–34 cohort with highest purchase intent
- **Position** brands on a perceptual map (Awareness vs Trust)

### 📣 AIDA Funnel
Tracks conversion from brand awareness → interest → desire → action using Likert scale survey responses.

### 📦 BCG Matrix
Plots all four brands on a Market Share vs Growth Rate grid to guide portfolio investment decisions.

### 📈 Statistical Tests
- **Pearson Correlation** — Brand Trust ↔ Purchase Intent
- **ANOVA** — Purchase intent differences across age groups
- **T-test** — Brand trust differences between male and female respondents

---

## 📚 Concepts Applied
- Primary Market Research & Survey Design
- Descriptive & Inferential Statistics
- Consumer Segmentation & Loyalty Analysis
- STP Strategy, AIDA Model, BCG Matrix
- Data Visualisation for Business Communication
- Python-based Statistical Analysis (SciPy, Pandas)
