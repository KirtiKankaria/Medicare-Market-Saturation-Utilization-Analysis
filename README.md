# Medicare Market Saturation Utilization Analysis

📌 **Overview**

- This project explores how Medicare market saturation and utilization influence county-level health behavior rankings across two healthcare service domains: Neurology and Preventive Health Services (PHS). Leveraging logistic regression and ensemble machine learning models, the analysis identifies key predictors of poor health outcomes using data from County Health Rankings and Medicare. 
- Rural areas face a 30% lower provider-to-patient ratio compared to urban counties.
- Understanding the correlation between Medicare market saturation and county health outcomes can inform policy decisions and resource allocation.



---

🛠️ **Tools & Technologies**

- Exploratory Data Analysis (EDA): Initial data exploration to understand distributions, missing values, and potential correlations. 
- Correlation and Causation Analysis: Identifying relationships between variables and determining causative factors. 
- Model Building: Constructing logistic regression for interpretability and Random Forest/Gradient Boosting models for predictive accuracy. 
- Dashboard Development: Deploying a Power BI dashboard for interactive, on-demand access to insights for health administrators and field operators.

---

📊 **Key Results**

- **Logistic Regression For PHS:**  
  - Accuracy: 76% | F1-score: 0.76
  
- **Random Forest For PHS:**  
  - Accuracy: 78% | F1-score: 0.78

- **Gradient Boosting (Neural Network) For PHS:**  
  - Accuracy: 78.2% | F1-score: 0.782
 
- **Logistic Regression For Neurology:**  
  - Accuracy: 70% | F1-score: 0.70

- **Random Forest For Neurology:**  
   - Accuracy: 76% | F1-score: 0.76
     
- **Gradient Boosting (Neural Network) For Neurology:**  
   - Accuracy: 73% | F1-score: 0.73

  📌 **Conclusion:**
     
- In Preventive Health Services, negative health behaviors—like smoking, obesity, and excessive drinking—emerged as the top predictors of poor health rankings. On the flip side, better access to primary care, lower preventable hospitalization rates, and higher Medicare user coverage helped counties rank better.
  
- In the Neurology domain, different predictors emerged:
- A higher number of primary care physicians was associated with better rankings—highlighting the importance of access.
- Meanwhile, more uninsured adults and a higher share of dual-eligible users were linked to worse rankings, likely reflecting socioeconomic disadvantage, Counties with higher death rates, more adults in fair or poor health, and higher smoking or obesity levels also tended to fall into the lower quartiles.

---

📂 **Repository Structure**
- `Model_for_Neurology.ipynb`, `Models_For_PHS.ipynb` – Jupyter/Colab notebooks with full model training & evaluation
- `Neurology_1.pbix`, `PHS_1.pbix` – Power BI files for interactive data visualization
- `Analyzing Medicare Market Saturation Report.pdf` – Project PDF and documentation

---

🔗 **Links**
- 📄 [Project Report (PDF)](https://github.com/KirtiKankaria/Medicare-Market-Saturation-Utilization-Analysis/blob/main/Analyzing%20Medicare%20Market%20Saturation%20Report.pdf)
- 📊 [Models For Neurology](https://github.com/KirtiKankaria/Medicare-Market-Saturation-Utilization-Analysis/blob/main/Model_for_Neurology.ipynb)
- 📊 [Models For PHS]()
- 🚀 [Power BI For Neurology]() 
- 🚀 [Power BI For PHS](#) 

---

🚀 **Future Work**
- Expand modeling to additional specialties and regions.
- Integrate new datasets for broader market analysis.
- Enhance visualization dashboards for real-time insights.
