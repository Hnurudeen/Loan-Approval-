# Predicting Loan Approval with Backpropagation Neural Networks (BPNN) 🏦🧠



## 📝 Description  
This project predicts loan approval status (Approved/Rejected) using **Backpropagation Neural Networks (BPNN)** and **Support Vector Machines (SVM)**. Key highlights:  
- **97.19% accuracy** with BPNN vs. 93.44% with SVM.  
- Automated feature engineering and hyperparameter tuning.  
- Critical insights into factors like `luxury_assets_value` and `cibil_score`.  

---

Confusion Matrix

![Screenshot 2025-03-15 170807](https://github.com/user-attachments/assets/05b1c391-4585-4896-ae89-f1798379bbf3)
  
*Over the heatmap above, it is shown that the variable that affects the loan_status the most is cibil_score.
It is also proved there is no variable that has a linear relationship with the education and self_employed.
There are strong linear relationship between income_annum & loan_amount, luxury_assets_value & income_annum, bank_asset_value & income_annum and luxury_assets_value & bank_asset_value*

Feature Importance Plot

![Screenshot 2025-03-15 171355](https://github.com/user-attachments/assets/64420dfc-46f0-48bc-92fc-bf9f52911e3a)

*Top features influencing loan approval: Luxury assets, CIBIL score, residential assets and commercial assets.*

## 📊 Results  
| Metric               | BPNN      | SVM       |
|----------------------|-----------|-----------|
| **Accuracy**         | 97.19%    | 93.44%    |
| **Precision**        | 97.73%    | 90.68%    |
| **Recall**           | 94.63%    | 91.82%    |
| **F1-Score**         | 96.17%    | 91.25%    |

**Top 5 Influential Features**:  
1. `luxury_assets_value`  
2. `commercial_assets_value`  
3. `residential_assets_value`  
4. `cibil_score`  
5. `bank_asset_value`  

---

