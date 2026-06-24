# TH-NANO: Thai Grassroots Credit Risk Scoring & Automated Decision Matrix
**"From Global Macro Anthropology to Local Financial Inclusion"**

---

## Part 1: The Macro View — Why Context Matters in Credit Scoring?

Before building a Machine Learning model for Thai grassroots micro-entrepreneurs (Nano-Finance), we first conducted an **Anthropological Data Analysis** using the *World Bank Global Findex Database (2021)* across 6 continents. 

The objective is to demonstrate a fundamental Data Science trap: **"Model distribution shift via geographical context."** A standard credit scoring model trained on Western data will fail catastrophically if deployed in Southeast Asia.

![Global Radar Chart](global_radar_chart.png)

### Key Anthropological Findings:
1. **The Hyper-Leveraged vs. The Thin-File:** In North America, the primary driver of credit default is **Over-indebtedness** (consumers holding multiple maxed-out credit lines). Conversely, in **East & Southeast Asia (including Thailand)**, the core issue is not the lack of willingness to pay, but the **Documentation Barrier** (8.5/10 score). 
2. **The Measurement Trap:**
   Thai micro-entrepreneurs (e.g., street vendors, freelance drivers) possess healthy daily cash flows, but operate entirely in the *Informal Economy*. When standard commercial banks evaluate them using traditional commercial metrics (e.g., **Fixed Payroll Slips**), they are misclassified as "High Risk".

![Rejection Reasons](global_rejection_reasons.png)

> **Business Takeaway for Part 2:** > The data proves that applying Western "Risk-Averse Law" or "FICO-style scoring" to Southeast Asians excludes high-potential borrowers. **Therefore, our Machine Learning Model (TH-NANO) will abandon 'Salary Slips' as a feature, and instead engineer 'Alternative Behavioral Data' (e.g., utility bill discipline, digital transaction frequency) to predict default.**