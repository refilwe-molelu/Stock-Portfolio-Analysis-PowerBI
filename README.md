
# 📊 Stock Portfolio Performance & Market Benchmark Analysis

An interactive data analytics project built to centralize personal investment data, build a resilient data model, and analyze portfolio performance trends against major market benchmarks (S&P 500, NASDAQ, and Dow Jones).

---

## 🛠️ The Core Challenge & Objectives

* **The Problem:** Tracking multiple personal investments manually across different platforms is messy, exhausting, and confusing. Without a centralized view, it is incredibly difficult to know if a financial strategy is actually winning or losing compared to broader market trends.
* **The Goal:** To build a robust, dynamic data solution that cleans raw historical transaction records, establishes a formal data model, and visualizes comprehensive portfolio performance alongside market baselines.

---

## 🧩 Data Architecture & Data Modeling (Star Schema)

Instead of relying on a single, dense flat file, the data was structured into a clean **Star Schema** to optimize engine performance and ensure accurate calculation filtering:

* **Fact Table (The Mother Table):** Holds all core investment amounts, daily values, and specific portfolio transaction numbers.
* **Dimension Tables:** Connected lookups, including a dedicated calendar lookup (`Dim_Date`), ensuring that time-intelligence filters flow seamlessly across charts without error.

---

## 💡 Key Business Insights & Strategic Recommendations

### 1. Maintain a Defensive Core Baseline
* **Insight:** Tracking stable indices like the Dow Jones helped the overall portfolio stay steady and completely absorb the sharp macroeconomic drops that hit tech-heavy stocks during market corrections.
* **Recommendation:** Keep a strong, calculated percentage of capital in stable, low-volatility sectors to act as a defensive buffer, rather than over-allocating into high-risk growth areas.

### 2. Prioritize Risk Management over Speculative Hype
* **Insight:** Trying to time the market perfectly usually fails, whereas a highly diversified asset plan naturally protects capital downside during market contractions.
* **Recommendation:** Prioritize downside risk protection. Accepting steady, diversified growth yields premium long-term stability over chasing speculative market-timing trends.

---

## 🚀 How to Explore this Project

1. **Download the Project File:** Click on the `finance owerbi.pbix` file listed right here in this repository and download it to open it directly inside Power BI Desktop.
2. **Review the Layout:** Check the dashboard structure to see the multi-page design tracking total returns, performance metrics, and automated benchmark cards.

---

## 📬 Connect with Me!
* **LinkedIn:** [Refilwe Molelu](https://www.linkedin.com/in/refilwe-molelu-713379241)
