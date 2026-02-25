# India Job Market Analysis: Salary Trends & Regional Insights

##  Project Overview

Navigating the job market requires a data-driven understanding of compensation benchmarks and geographic demand. This project involves a comprehensive **Exploratory Data Analysis (EDA)** of the Indian job market using a dataset of over 800+ job listings across various industries and regions.

As a **Business and Data Analyst**, my role was to clean the unstructured salary data, standardize geographical locations, and derive insights that help recruiters and job seekers understand the current economic landscape of the Indian workforce.

---

##  Business Objectives

The analysis aims to bridge the information gap between employers and talent by addressing:

1. **Compensation Benchmarking:** What is the average monthly salary across different states and job titles?
2. **Geographic Hotspots:** Which states (e.g., Kerala, Maharashtra, Karnataka) are seeing the highest volume of recruitment?
3. **Work Preferences:** What is the prevalence of "Remote" work vs. "On-site" roles in the current market?
4. **Role Popularity:** Identifying high-demand roles like Delivery Executives, STEM Trainers, and Software Developers.

---

##  Dataset Description

The dataset contains cleaned records with the following key attributes:

| Feature | Description |
| --- | --- |
| `Job_Title` | The professional designation for the role. |
| `Location` | The city and state of the workplace. |
| `Monthly_Salary` | A standardized numerical column representing the calculated monthly pay. |
| `State` | The specific Indian state where the job is based. |
| `Locality` | Granular location data, including "Remote" classification. |
| `Salary` | The original raw salary string as advertised. |

---

##  Methodology & Technical Stack

### Technologies Used:

* **Python:** Core engine for data manipulation.
* **Pandas:** Used for cleaning unstructured salary strings and handling missing data.
* **Matplotlib & Seaborn:** For visualizing distribution of pay and regional job density.

### Analytical Workflow:

1. **Data Pre-processing:** Successfully transformed raw salary ranges (e.g., "₹1.8L - ₹3.6L per year") into a uniform `Monthly_Salary` metric.
2. **State-wise Segmentation:** Aggregated data at the state level to identify regional economic variances.
3. **Categorical Analysis:** Analyzed job titles to find the most frequent hiring categories.
4. **Outlier Detection:** Identified and addressed significant variances in salary data to ensure statistical reliability.

---

## Key Findings

* **Regional Dominance:** Kerala and Maharashtra appeared as major hubs in this specific dataset, showing high hiring activity.
* **Remote Work Trends:** A significant portion of the roles are classified as "Remote," reflecting the shifting nature of the post-pandemic workspace in India.
* **Salary Variance:** Significant pay gaps were observed between specialized technical roles (STEM/Web Dev) and entry-level service roles.
* **Data Quality:** 100% data consistency achieved in the `Monthly_Salary` and `State` columns after cleaning.

---

##  How to Run

1. **Clone the Repository:**
```bash
git clone https://github.com/vnandini879/india-job-market-india-EDA5-python.git

```


2. **Install Requirements:**
```bash
pip install pandas seaborn matplotlib

```


3. **Execute:** Run the provided Jupyter Notebook or Python script to generate the analysis and visualizations.

---

##  Author

**Nandini Verma**

* **Role:** Business and Data Analyst
* **GitHub:** [vnandini879](https://www.google.com/search?q=https://github.com/vnandini879)

---

*Note: This project is part of an EDA portfolio series exploring regional economic data.*
