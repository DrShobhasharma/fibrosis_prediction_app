# 🧠 FAET Tool – AI-Based Advanced Fibrosis Prediction

## 🚀 Overview

FAET (Fibrosis Assessment using Extra Trees) is a web-based AI application developed to predict advanced liver fibrosis using minimal clinical inputs. The tool is designed for quick, real-time risk assessment and aims to assist early screening in healthcare settings.

## 🎯 Objective

* Predict advanced fibrosis (Advanced vs Non-Advanced)
* Provide a simple, low-cost, and scalable AI solution
* Improve over traditional clinical scoring systems (FIB-4, APRI)

## 🖥️ Application Interface

The application is built using Streamlit and provides a user-friendly interface where users input five clinical parameters:

* Age
* Platelet Count (PLT)
* Diabetes Status
* Serum AST/SGOT
* Serum Cholesterol

The system processes inputs and returns:

* Predicted Class (Advanced / Non-Advanced Fibrosis)
* Prediction Score (Probability)
* Confidence Level

## 📸 Screenshot

![App Interface](MASLD app screenshot.png)

## ⚙️ Methodology

* Data preprocessing and cleaning
* Feature selection (reduced to 5 key clinical parameters)
* Model used:

  * Extra Trees Classifier
* Model evaluation using cross-validation

## 📈 Results

* Best Model: Extra Trees (FAET)
* Metrics:

  * Accuracy: 84%
  * AUC: 82%
  * PPV: 91%

## 🔬 Key Contributions

* Developed a **data-efficient ML model** using only 5 input features
* Achieved high predictive performance compared to traditional clinical indices
* Built a **deployable AI web application** for real-time inference
* Designed for **accessibility in low-resource clinical environments**

## 🛠️ Tech Stack

* Python
* Streamlit
* scikit-learn

## 📌 Future Work

* Integration with electronic health records (EHR)
* Deployment on cloud platforms
* Extension using Quantum Machine Learning and Graph-based methods

## 👩‍💻 Author

Shobha Sharma
