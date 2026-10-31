# 👥 Recruitment Funnel & HR Analytics Dashboard | Power BI & Excel

An end-to-end recruitment analytics project developed in **Microsoft Power BI** and **Excel** evaluating candidate progression through hiring stages, sourcing channel ROI, departmental cycle times, and candidate drop-off patterns[cite: 22].

---

## 📌 Executive Summary
Talent acquisition teams require clear visibility into candidate conversion and pipeline velocity to eliminate bottlenecks and optimize sourcing spend[cite: 22]. This project tracks **100 candidates** across **265 stage-level events**, evaluating funnel efficiency from application to hire[cite: 22].

### 🎯 Key Performance Indicators (KPIs)
* **Total Applicants:** 100[cite: 22]
* **Total Hired:** 28[cite: 22]
* **Dropped & Rejected Candidates:** 72 (36 Dropped, 36 Rejected)[cite: 22, 23]
* **Overall Hire Rate:** 28.0%[cite: 22]
* **Average Time-to-Hire:** 26.64 days[cite: 22, 23]
* **Average Stage Duration:** 5.55 days[cite: 22, 23]

---

## 📊 Dashboard Architecture & Pages

The Power BI report contains 4 dedicated views:
1. **Home:** Project navigation and high-level context.
2. **Overview:** Stage conversion funnel, top-level KPI cards, and candidate outcome breakdown (Hired vs. Dropped vs. Rejected)[cite: 22, 23].
3. **Source & Department Analysis:** Sourcing channel efficiency and departmental hiring velocity[cite: 22].
4. **Process & Time-to-Hire:** Bottleneck discovery, average days spent per stage, and stage-specific rejection patterns[cite: 22, 23].

---

## 🔍 Key Insights & Analysis

### 1. Funnel Conversion & Bottlenecks
| Stage | Candidates Entering | Stage Conversion Rate | Avg Days in Stage |
| :--- | :---: | :---: | :---: |
| **Applications** | 100 | 100.0% | 5.64 days |
| **Screening** | 67 | 67.0% | 5.25 days |
| **Interviewed** | 48 | 71.6% | 5.31 days |
| **Offered** | 34 | 70.8% | 5.94 days |
| **Hired** | 28 | 82.4% | 6.19 days |

* **Major Drop-off:** The steepest attrition occurs between **Applications and Screening (33% drop)**, where 33 applicants were either rejected (16) or dropped out (17)[cite: 22, 23].
* **Offer Acceptance:** The **Offered-to-Hired** transition demonstrates the highest conversion at **82.35%**, indicating strong offer competitiveness[cite: 22, 23].

---

### 2. Sourcing Channel Performance
| Source | Applicants | Hired | Hire Rate (%) |
| :--- | :---: | :---: | :---: |
| **Company Website** | 28 | 10 | **35.7%** |
| **Finance / Referrals** | 24 | 7 | **29.2%** |
| **Indeed** | 22 | 6 | **27.3%** |
| **LinkedIn** | 12 | 3 | **25.0%** |
| **Job Fair** | 14 | 2 | **14.3%** |

* **Top Performer:** **Company Website** generated the highest volume of hires (10) and the top conversion rate (35.7%)[cite: 22, 23].
* **Lowest Performer:** **Job Fairs** generated the lowest return on investment, converting at only 14.3%[cite: 22].

---

### 3. Departmental Hiring & Velocity
| Department | Applicants | Hired | Hire Rate (%) | Avg Days/Stage |
| :--- | :---: | :---: | :---: | :---: |
| **Finance** | 24 | 8 | **33.3%** | 5.92 |
| **HR** | 18 | 6 | **33.3%** | 5.39 |
| **Sales** | 25 | 8 | **32.0%** | 6.08 |
| **Engineering** | 15 | 3 | **20.0%** | **4.07** |
| **Marketing** | 18 | 3 | **16.7%** | 5.00 |

* **Cycle Times:** **Engineering** is the fastest hiring department (4.07 days/stage), whereas **Sales** experiences the longest review cycles (6.08 days/stage)[cite: 22, 23].
* **Conversion Gaps:** **Marketing** exhibits the lowest overall hire rate at 16.7%[cite: 22, 23].

---

## 💡 Strategic Business Recommendations
1. **Refine Early Screening:** Standardize resume screening criteria to reduce the 33% drop-off at the application review stage[cite: 22, 23].
2. **Reallocate Sourcing Budget:** Shift talent acquisition marketing spend away from low-yielding Job Fairs toward Referral incentive programs and direct career portal SEO[cite: 22, 23].
3. **Streamline Final Approvals:** The Offered and Hired stages average over 6 days; automating offer letter workflows and background verification can shave 3–5 days off total time-to-hire[cite: 23].
4. **Replicate Engineering Best Practices:** Audit Engineering's fast-tracking interview structure to assist Sales in reducing its 6.08 days/stage duration[cite: 22, 23].

---

## 🛠️ Tools & Technologies Used
* **Business Intelligence:** Microsoft Power BI Desktop
* **Data Modeling:** Power Query, Star Schema, DAX (Calculated Columns, Dynamic Measures)
* **Data Prep & Audit:** Microsoft Excel / CSV
* **Documentation:** Markdown, Executive PDF Report[cite: 22]

---

## 📂 Repository Contents
* `Recruitment_Funnel_Analytics_Dashboard.pbix` — Interactive Power BI workbook
* `recruitment_funnel_data.csv` — Raw recruitment transaction data
* `Recruitment_Analytics_Summary_Report_Final.pdf` — Executive summary report[cite: 22]
* `README.md` — Project documentation and business insights

---

## 👨‍💻 Author
* **Adith Sudhi** – [LinkedIn](https://www.linkedin.com/in/adith-sudhi-98b163221/) | [GitHub](https://github.com/adithsudhi2001-hub)
