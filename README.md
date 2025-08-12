# 📚 Economic Hardship and Its Implications on Education in the Diaspora (USA)

## 📌 Project Overview
This research examines how Nigeria’s macroeconomic conditions influence the ability of Nigerian students to enroll and remain in U.S. higher education institutions.  
Using annual time series data from **1990–2024** and the **Autoregressive Distributed Lag (ARDL)** model, the study explores both **short-run** and **long-run** effects of key economic variables on diaspora education.

---

## 🎯 Objectives
- Quantify the impact of **remittance inflows**, **inflation**, **exchange rate fluctuations**, and **tuition costs** on Nigerian student enrollment in the USA.
- Identify both **immediate** and **lagged** effects of these variables.
- Provide **policy recommendations** to mitigate economic hardship and sustain educational access.

---

## 📊 Dataset & Variables
**Sources**:  
- World Development Indicators (WDI)  
- Statista  
- Nigerian Diaspora Commission (NiDCOM)  
- Opendoors  

**Variables**:
- **ENROLL** → Number of Nigerian students enrolled in the USA  
- **REMIT** → Remittance inflows to Nigeria (USD billions)  
- **INF** → Inflation rate in Nigeria  
- **EXR** → NGN/USD exchange rate  
- **TUITION** → Average U.S. tuition fees for international students (USD)

---

## 🛠 Methodology
1. **Unit Root Tests (ADF)** → Confirmed a mix of I(0) and I(1) variables, justifying ARDL use.
2. **ARDL Bounds Test** → Established a significant long-run relationship between variables.
3. **ARDL(1,1,3,0,3) Estimation** → Chosen via Akaike Information Criterion (AIC).
4. **Diagnostic Tests**:
   - No heteroskedasticity (Breusch-Pagan-Godfrey test)
   - No serial correlation (Breusch-Godfrey LM test)
   - Residuals are stable and efficient.

---

## 📈 Key Findings
- **Exchange Rate (EXR)** → Significant negative effect on enrollment: Naira depreciation sharply increases study costs.
- **Inflation (INF)** → Negative long-term impact with a 3-year lag, reflecting delayed financial strain on families.
- **Remittance Inflows (REMIT)** → Negative and significant effect at a 1-year lag; delayed remittances disrupt tuition payments.
- **Tuition Costs (TUITION)** → Mixed effects:
  - Negative impact at a 2-year lag (price shock discourages enrollment)
  - Positive at a 3-year lag (families adapt via savings, scholarships, or alternative funding).
- **Enrollment Persistence** → Strong influence of previous-year enrollment trends.

---

## 💡 Policy Recommendations
1. **Stabilize the Exchange Rate** → Improve forex management and trade balance.
2. **Create a Dedicated Education Forex Window** → Shield tuition payments from black-market volatility.
3. **Establish Diaspora Education Support Funds** → Scholarships and grants for middle-/low-income families.
4. **Expand Bilateral Education Agreements** → Negotiate tuition concessions with U.S. institutions.
5. **Improve Remittance Channels** → Faster, cheaper, and more predictable transfers.
6. **Enhance Domestic University Quality** → Reduce push factors for studying abroad.
7. **Manage Inflation** → Target food and education-related costs.

---

## 🛠 Tools Used
- **EViews** → Econometric modeling
- **Microsoft Word** → Research documentation
- **Excel** → Data preparation

---

## 📎 Citation
Adegbola Ayeni (2025). *Economic Hardship and its Implications on Education in the Diaspora (USA)*.  

---
💡 **Author:** Adegbola Ayeni  
📧 Contact: ayeniadegbolaelijah@gmail.com  
🌐 Portfolio: https://github.com/adegbolaayeni
