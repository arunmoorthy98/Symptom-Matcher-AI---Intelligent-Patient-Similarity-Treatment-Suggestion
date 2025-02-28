# 🩺 Symptom-Matcher AI - Intelligent Patient Similarity & Treatment Suggestion

## 📌 Overview

**Symptom-Matcher AI** is a machine learning-powered web application that assists healthcare professionals in identifying similar patients based on symptoms and diseases. It also categorizes patients based on doctor comments, helping doctors make informed treatment decisions. The system leverages **NLP (Natural Language Processing)** and **Machine Learning (ML)** techniques to streamline patient diagnosis and improve healthcare efficiency.

## 📍 Project Details

- **Location:** Dodoma, Tanzania
- **Email:** [sashashamsia@gmail.com](mailto\:sashashamsia@gmail.com)
- **WhatsApp:** +255675839840
- **Demo:** Online

## 🎯 Target Audience

| Icon  | Rank | Target Audience                                                      |
| ----- | ---- | -------------------------------------------------------------------- |
| 🔬    | 1    | Healthcare Researchers (Epidemiologists, Clinical Researchers)       |
| 🩺    | 2    | Physicians (General Practitioners and Specialists)                   |
| 🏛️   | 3    | Public Health Officials (Health Department Personnel, Policy Makers) |
| 🏢    | 4    | Hospital Administrators                                              |
| 👩‍⚕️ | 5    | Nurses                                                               |
| 📊    | 6    | Data Analysts in Healthcare                                          |
| 👨‍💼 | 7    | Medical Directors                                                    |
| 💊    | 8    | Pharmacists                                                          |
| 🏥    | 9    | Clinic Administrators                                                |
| 🎓    | 10   | Medical Educators (Professors of Medicine)                           |

## ⚠️ Disclaimer

The patient records used in this application are **not real patient data**. They are **fictitious** and generated solely for educational purposes. The diseases, symptoms, and treatments shown in this app do **not** represent actual medical diagnoses. This application is intended for learning, training, and research purposes **only** and should **not** be used for real medical decisions.

---

## 🏥 1. Introduction

In healthcare, patient records contain crucial data such as **symptoms, diagnoses, doctor comments, and treatments**. This system uses **machine learning** to identify patterns and similarities in patient records to help:

- **Doctors:** Quickly recall previous treatments for similar cases.
- **Healthcare Providers:** Improve diagnosis efficiency.
- **Patients:** Receive better treatment recommendations based on past cases.

Symptom-Matcher AI applies **text similarity algorithms** and **topic modeling** to group and match patients efficiently.

---

## ❌ 2. Problem Statement

### **Challenges in Healthcare Data Management:**

1. **Manual grouping of patients** based on symptoms is inefficient.
2. **Doctor comments** are often unstructured text, making them difficult to analyze.
3. **Large datasets** make it challenging to recall past similar cases.

### **Solution:**

- Automatically **group patients with similar symptoms**.
- Categorize doctor comments to **identify treatment patterns**.
- Use **Machine Learning & NLP** to provide **intelligent recommendations**.

---

## 🎯 3. Importance of This App

✔ **Enhanced Patient Diagnosis** – Helps doctors find similar past cases for better decision-making. ✔ **Improved Treatment Consistency** – Ensures similar conditions get consistent treatments. ✔ **Efficient Healthcare Operations** – Reduces manual workload for healthcare providers. ✔ **Data-Driven Insights** – Helps analyze disease and treatment trends over time. ✔ **Cost & Time Saving** – Reduces patient diagnosis and treatment planning time. ✔ **Predictive Modeling** – Helps forecast common diseases and symptoms for better preparedness.

---

## 🔍 4. Main Purpose

The **primary goal** of Symptom-Matcher AI is to **match new patients with historical cases** and provide **treatment recommendations** based on previous doctor comments.

### **Key Features:**

✅ **Match Patients with Similar Symptoms** – Identifies patients with similar symptoms and disease histories. ✅ **Categorize Doctor Comments** – Uses **LDA topic modeling** to group patient records by treatment categories. ✅ **Provide Treatment Suggestions** – Recommends treatment plans based on past cases.

---

## 🛠 5. Methodology

### **Technologies Used:**

- **Streamlit** – For building the web application.
- **Pandas** – For data handling.
- **NumPy** – For numerical operations.
- **Scikit-learn** – For text vectorization and similarity computation.
- **Gensim** – For LDA-based topic modeling.

### **Key Components:**

#### **1️⃣ Data Preparation**

- Load patient data from `patient_conditions.csv` (or a database in production).
- Preprocess data to extract symptoms, diseases, and doctor comments.

#### **2️⃣ Patient Recommendation (Similarity Matching)**

- **TF-IDF (Term Frequency-Inverse Document Frequency)** – Converts text into a numerical format.
- **Cosine Similarity** – Computes the similarity score between patients.
- **Top-N Recommendations** – Returns **top 10 similar patients**.

#### **3️⃣ Patient Categorization (Doctor Comments Analysis)**

- **Text Preprocessing** – Converts doctor comments into word tokens.
- **LDA (Latent Dirichlet Allocation)** – Groups patients into **10 categories** based on treatment history.
- **Topic Assignment** – Assigns each patient a category number.

#### **4️⃣ Web Application (Streamlit UI)**

- **Dropdown to select a patient**
- **Button to find similar patients**
- **Table to display recommended patients and categories**

---

## 📊 6. Interpretation of Patient Records

### **1️⃣ Patient Records Example**

| ID | Age | Disease      | Symptoms            | Doctor Comment                |
| -- | --- | ------------ | ------------------- | ----------------------------- |
| 1  | 45  | Diabetes     | Fatigue, thirst     | Monitor blood sugar regularly |
| 2  | 50  | Hypertension | Headache, dizziness | Reduce salt intake            |

### **2️⃣ Recommended Patients Example**

| ID | Disease  | Symptoms                              |
| -- | -------- | ------------------------------------- |
| 42 | Diabetes | Increased thirst, slow healing wounds |
| 1  | Diabetes | Fatigue, thirst                       |

### **3️⃣ Patient Categorization Example**

| ID | Doctor Comment                | Category   |
| -- | ----------------------------- | ---------- |
| 1  | Monitor blood sugar regularly | Category 1 |
| 2  | Reduce salt intake            | Category 9 |

---

## 🏆 7. Conclusion

The **Symptom-Matcher AI** system enhances patient diagnosis and treatment by **grouping similar cases** and providing **data-driven recommendations**. It serves as a valuable tool for **doctors, researchers, and healthcare providers** to improve efficiency in clinical decision-making.

---

## 🚀 8. Installation & Usage

### **1️⃣ Install Dependencies**

```bash
pip install streamlit pandas numpy scikit-learn gensim
```

### **2️⃣ Run the Application**

```bash
streamlit run app.py
```

### **3️⃣ How to Use**

- Select a **patient ID** from the dropdown.
- Click **"Recommend Patients"** to find similar cases.
- View **top recommendations** and **categorized patients**.

---

## 📄 9. License

This project is licensed under the **MIT License**.

---

## 📧 10. Contact

For inquiries or contributions: 📍 **Email:** [arun63829@gmail.com](mailto\:arun63829@gmail.com)

