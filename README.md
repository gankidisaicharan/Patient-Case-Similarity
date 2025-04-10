# 🫀 Coronary Heart Disease Risk Prediction Using Patient Case Similarity & Machine Learning

This project applies machine learning and case similarity techniques to predict the risk of Coronary Heart Disease (CHD). It incorporates clustering and predictive modeling along with an intuitive Gradio interface for medical professionals.

---

## 📊 Project Highlights

- **Dataset**: Patient demographics, medical history, and lifestyle features
- **ML Models**: XGBoost, Random Forest, Logistic Regression, SVM
- **Best Model**: Random Forest
- **Accuracy**: 99%
- **Similarity**: K-Means clustering and Euclidean distance
- **UI**: Gradio app for real-time CHD risk prediction

---

## 🧪 Methodology

1. <i>**Data Preparation**</i>  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize numerical features

2. <i>**Exploratory Data Analysis (EDA)**</i>  
   - Visualize feature distributions  
   - Analyze correlations

3. <i>**Feature Engineering & Splitting**</i>  
   - Create and select important features  
   - Train-test split (80-20)

4. <i>**Model Training & Evaluation**</i> 
   - Train XGBoost, Random Forest, Logistic Regression, SVM  
   - Evaluate using accuracy, precision, recall, F1-score

5. <i>**K-Means Clustering**</i>  
   - Determine optimal clusters using Elbow method  
   - Cluster patients by risk factor similarity

6. <i>**Case Similarity Analysis**</i>  
   - Assign user input to a cluster  
   - Find top-k similar patients using Euclidean distance  
   - Predict based on majority label of similar cases

7. <i>**Risk Prediction Interface**</i>  
   - Gradio-based web interface  
   - Input patient data and view prediction

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn, XGBoost  
- Matplotlib  
- Gradio

---

## 📈 Results

- *Accuracy*: 99%  
- *Precision*: 99%  
- *Recall*: 98%  
- *F1-Score*: 99%

*Top 3 Features (by importance):*
- Age  
- Tobacco usage  
- LDL cholesterol

*Clusters Identified*: 4 (via Elbow method)

---

## 🖼️ Model Output Preview

![Patient Case Similarity Output](images/output_patient_case_similarity.png)

---

## 🙏 Acknowledgments

Thanks to the open-source community, healthcare researchers, and contributors who made this project possible.
