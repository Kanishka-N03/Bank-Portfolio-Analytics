# Bank-Portfolio-Analytics

This project involves cleaning and analysing a banking client dataset. The raw data was riddled with duplicates, missing values, and inconsistent formatting — it was cleaned and transformed into a structured, analysis-ready file, which was then used to uncover insights around client demographics, financial behaviour, loyalty segmentation, and credit risk.

---
<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Excel
- Python (Pandas, numpy)
- Power BI (Interactive Visualizations)
- GitHub

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Deleted columns Client ID and IAId as they were not required for analysis.
- Replaced values in the GenderId column: 1 → Man, 2 → Woman.
- Replaced values in the BRId column: 1 → Retail, 2 → Institutional, 3 → Private Bank, 4 → Commercial.
- Replaced null values in Estimated Income, Credit Card Balance, Bank Loans, Nationality, Occupation, Fee Structure, Age
- Flagged invalid age values — entries below 21 or above 70 were set to null as outside the valid client age range.
- Handled duplicates in the Name, Loyalty Classification,Nationality, Fee Structure column and sorted all records in ascending order.

---
<h2><a class="anchor" id="key-findings"></a> Key Findings</h2>

- Client acquisition peaked in 2020 at 241 new clients — 2.3× the historical average — indicating a significant growth surge in recent years.
- Loan-to-Deposit ratio stands at 0.86 with total bank loans of $1.69bn against deposits of $1.95bn, reflecting a moderately leveraged but stable portfolio.
- 15.93% of clients are high-risk, carrying an average loan of $853K — nearly double the portfolio average — representing a concentrated credit risk exposure.
- Europeans dominate 48.2% of the loan book at a 17.3% high-risk rate, making them the single largest concentration risk, while Americans show the safest profile at 12.7% risk but raise liquidity concerns with an LTD of 0.905.
- 10–15 year tenure clients are the riskiest segment at 17.2% high-risk rate, while 15–20 year clients are the bank's strongest cohort — lowest risk (15.1%) and highest average deposits ($685K) — highlighting tenure as a key indicator of client quality.

---
<img width="930" height="523" alt="Screenshot (197)" src="https://github.com/user-attachments/assets/15dcbe91-16e6-4c0f-ad3d-1a2e7a198761" />
<img width="888" height="480" alt="Screenshot (198)" src="https://github.com/user-attachments/assets/ada20482-a078-4bd6-abb6-8794d0377009" />

