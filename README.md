# IBM-EdunetFoundation-Project
## About the Project
This project analyzes demographic and regional disparities in Tele-Law service utilization using a machine learning model. By predicting the total number of case registrations per district, the system provides insights to support equitable legal service delivery across India.

**Capstone Project | IBM & Edunet Foundation Initiative**
**Developed by:** *Durga Reddy Karri, Department of Computer Science and Engineering, Lovely Professional University*

---

## Problem Statement:
**Analyzing Demographic and Regional Disparities in Tele-Law Case Registrations for Inclusive Legal Access.**
Despite the rapid expansion of the Tele-Law initiative across Indian states and districts, disparities in usage across gender, caste, and geography remain insufficiently understood. Certain marginalized communities—such as **SC, ST, and OBC** and underserved districts report low engagement. This raises concerns about **equity in legal aid access**. Additionally, varying **CSC (Common Service Centres)** counts complicate direct comparisons between regions.
This project addresses these challenges through a **data-driven predictive model** that forecasts Tele-Law case registrations, offering **actionable insights for policymakers** to ensure inclusive and optimized legal service delivery.

---

## Project Objective:
To develop a predictive system using **IBM Watsonx.ai Studio’s AutoAI** that forecasts the total number of Tele-Law case registrations in each Indian district based on:
- Gender-wise data (Male, Female)
- Caste-wise data (SC, ST, OBC, General)
- Geographic data (State/UT, District)
- Number of CSCs per district

---

## Proposed Solution:
A regression model was built using **IBM Watsonx.ai Studio AutoAI**, leveraging demographic and regional data to predict legal aid utilization. This solution allows:
- Identification of underperforming districts
- Strategic CSC planning
- Support for inclusive policy decisions

---

## Dataset:
- **Source**: [data.gov.in – District-wise Tele-Law Case Registration (FY 2021–25)](https://www.data.gov.in/resource/district-wise-tele-law-case-registration-and-advice-enabled-data-fy-2021-22-2024-25)
- **Format**: CSV
- **Features Used**: Gender-wise counts, caste-wise counts, number of CSCs, district/state names.

---

## Results:
The model achieved accurate predictions of **total case registrations** using demographic and regional inputs. It helped highlight low-performing districts and provided insights for policy optimization.
### INPUT DATA
<img width="1528" height="767" alt="image" src="https://github.com/user-attachments/assets/bacab752-5bdb-4dab-91f9-a34be8bce4ad" />

### PREDICTION RESULT
<img width="1528" height="767" alt="image" src="https://github.com/user-attachments/assets/f2b6a20b-89df-4b37-b002-9a0e0025d90d" />

### MODEL PREDICTION ACCURACY: COMPARISION WITH ACTUAL DATA
<img width="1528" height="767" alt="image" src="https://github.com/user-attachments/assets/3cfda7ba-c073-4036-8aa8-98e1cb0d1223" />

---

## Conclusion:
The project successfully developed a predictive system for analyzing legal aid access disparities using **IBM Watsonx.ai Studio**. The model enables **informed decision-making** to support equitable **Tele-Law service distribution** across India.
