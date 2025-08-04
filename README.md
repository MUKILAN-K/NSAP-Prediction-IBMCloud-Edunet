# NSAP-Prediction-IBMCloud-Edunet

A machine learning project that predicts the NSAP Scheme Code using AutoAI on IBM Cloud. Built under the Edunet Foundation program using real-world government data.

## 📌 Problem Statement

Ensuring accurate prediction of NSAP scheme codes based on applicant data is essential to streamline and improve the benefits distribution process. The goal is to build a predictive model that classifies scheme codes based on various demographic and eligibility features.

## 🚀 Project Objective

To build an ML model using IBM Cloud AutoAI to predict the `schemecode` column from a public pension dataset under the National Social Assistance Programme (NSAP).

---

## 🗃️ Dataset

- **Source**: AI Kosh by IndiaAI  
- **Title**: District-wise Pension Data under NSAP  
- **Link**: [Click here to view dataset](https://aikosh.indiaai.gov.in/web/datasets/details/district_wise_pension_data_under_the_national_social_assistance_programme_nsap_1.html)

---

## ⚙️ Tools & Technologies Used

- IBM Cloud AutoAI
- IBM Watson Studio
- Python (for optional testing)
- Machine Learning (Random Forest Classifier)
- Edunet Foundation Cloud Lab Environment

---

## 🧠 Prediction Target

- **Prediction Column**: `schemecode`
- **Algorithm Used**: Snap Random Forest Classifier
- **Features Used**: 26 input features including district, age, caste, gender, etc.

---

## 📊 Model Performance

| Metric               | Holdout Score | Cross-validation Score |
|----------------------|---------------|-------------------------|
| Accuracy             | 0.977         | 0.984                   |
| F1 Macro             | 0.977         | 0.984                   |
| Precision Macro      | 0.977         | 0.984                   |
| Recall Macro         | 0.977         | 0.984                   |
| Log Loss             | 0.222         | 0.143                   |

---


---

## 📌 Future Scope

- Integrate advanced ML algorithms or ensemble models.
- Use more granular data from multiple states or cities.
- Build a full web dashboard for stakeholders.
- Deploy as an API using IBM Cloud Functions or Flask.

---

## 🤝 Contributors

- Mukilan K  
- Edunet Foundation  
- IBM SkillsBuild

---

## 📄 License

This project is released for educational and demonstration purposes under the MIT License.
