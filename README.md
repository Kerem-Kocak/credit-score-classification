# CREDIT SCORE CLASSIFICATION

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oSiSDzIlFqs2lajIHZsDxrc15nFVPxkQ?usp=sharing)

## 📌 Project Overview
This project aims to automate the classification of customer credit scores into three categories: **Good, Standard, and Poor**.                       
Using a dataset of over 73,000 records, we implemented a full machine learning pipeline—from rigorous data cleaning and outlier handling to hyperparameter optimization of ensemble models.

The **Tuned Random Forest Classifier** emerged as the optimal model, achieving an **Accuracy of 78.89%** and an **F1-Score of 78.92%**.

---

## 📊 Key Results
**Best Model:** Tuned Random Forest.
<br>**Performance:** 23.13% improvement over the Logistic Regression baseline.<br/>
**Critical Features:** 'Outstanding Debt' and 'Credit Mix' were identified as the most impactful predictors of creditworthiness.



---

## 🛠 Team & Contributions
This project was a collaborative effort for the **COE305 Machine Learning** course.

</br>**[Kerem Koçak](https://github.com/Kerem-Kocak)**:
</br>**ML Pipeline Development:** Actively participated in the training and testing of six classification models, ensuring robust evaluation through Stratified 5-Fold Cross-Validation.
</br>**Presentation & Analysis:** Co-designed the technical presentation and analyzed performance metrics to justify model selection.
</br>**Strategic Synthesis (Video Lead):** Led the final results comparison and authored the "Future Work" roadmap, including proposals for SMOTE and Deep Learning integration.
</br>**[Berke Durdu](https://github.com/BerkeDurdu)**: Collaborated on data preprocessing and model implementation.
</br>**[Gabriel Kesler](https://github.com/Gabi8347)**: Collaborated on initial model selection and baseline comparisons.

---

## 📺 Project Demo & Presentation
[▶️ Watch the Project Video](https://drive.google.com/file/d/1IGUhbCIVh5fo-X5H2UPh89RHqMpL7AyO/view?usp=drive_link)

*Note: My specific contribution to the video begins at the **Final Results Comparison** and covers the **Strategic Roadmap** for future improvements.*

---

## 🚀 Future Roadmap
Based on our final analysis, the following steps are proposed for production-level deployment:
1. **Handle Class Imbalance:** Apply **SMOTE** to improve recall for the minority "Good" credit class.
2. **Advanced Algorithms:** Explore **CatBoost** and **LightGBM** for better handling of categorical data.
3. **Operationalization:** Deploy the model via a **Flask or Streamlit API** for real-time scoring.
