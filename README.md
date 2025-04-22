# 🧠 Diabetes Prediction Model using Neural Networks
<img width="995" alt="image" src="https://github.com/user-attachments/assets/0a093587-f535-4150-8b98-238991c74335" />
<img width="434" alt="image" src="https://github.com/user-attachments/assets/b3c826ec-ff33-4baf-a1b5-71686c6de9ba" />
<img width="1283" alt="image" src="https://github.com/user-attachments/assets/37099b3d-e20a-41ce-b726-56f06257be29" />

This project is a **machine learning-based diabetes prediction tool** built using a neural network. It allows users to input key health metrics and instantly receive a prediction of whether they are likely to have diabetes.

### 🚀 Live Demo
> 💡 Hosted via Gradio on Google Colab  
> 📌 Launch the notebook and interact in your browser.

---

## 📊 Dataset

- **Source**: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Description**: Includes 768 samples with 8 clinical features:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age

---

## 🧠 Model Architecture

- **Type**: Deep Neural Network (Sequential)
- **Framework**: TensorFlow / Keras
- **Layers**:
  - Dense (128 units, ReLU)
  - Dense (64 units, ReLU)
  - Output Layer (1 unit, Sigmoid)

---

## 💡 Features

- Real-time prediction interface using **Gradio**
- Easy to use: enter a few health metrics and get instant feedback
- Visualization of training accuracy and loss
- Downloadable and customizable model

---

## 📦 Installation

In your Google Colab notebook:

```bash
!pip install gradio pandas numpy scikit-learn tensorflow matplotlib seaborn
📌 Future Work
Add model evaluation metrics

Improve model with more feature engineering

Expand to other diseases (heart, cancer, eyes)

Deploy with authentication and user tracking

here by I am attaching the link of the model
https://51def78c685aa5bd04.gradio.live
