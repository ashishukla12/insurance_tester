# 🛡️ Insurance Tester

The Insurance Tester project is totally based on the integration of Machine Learning and FastAPI.
It combines the power of a trained RandomForestClassifier model with a FastAPI backend to provide real-time predictions for insurance-related data.

Machine Learning Layer
⦁ A RandomForestClassifier is trained on insurance datasets to predict outcomes.
⦁ The trained model is serialized using Pickle for deployment.

FastAPI Layer
⦁ FastAPI is used as the backend framework to expose ML predictions as RESTful APIs.
⦁ Input data is validated using Pydantic models, ensuring type safety and preventing invalid requests.
⦁ Built-in documentation (/docs and /redoc) makes the API easy to test and understand.

Streamlit UI
⦁ A simple, interactive frontend built with Streamlit lets users test the insurance prediction model.
⦁ The UI communicates with the FastAPI backend to send inputs and display predictions in real-time.

🔗 In short:
This project demonstrates a complete end-to-end ML deployment pipeline — from training and saving the model, to serving it with FastAPI, validating requests with Pydantic, and creating a user-friendly interface with Streamlit.
---

## 🚀 Features

- ✅ **ML Model**: Trained using `RandomForestClassifier`  
- ✅ **FastAPI Backend**: Serves the ML model as an API  
- ✅ **Pydantic**: For data validation and request handling  
- ✅ **Streamlit Frontend**: User-friendly interface for predictions  
- ✅ **Pickle Deployment**: Model serialized with `.pkl` for lightweight deployment  

---

## 🛠️ Tech Stack

- **Python 3.x**  
- **scikit-learn** → Model training  
- **FastAPI** → Backend API  
- **Pydantic** → Request validation  
- **Streamlit** → Frontend UI  
- **Pickle** → Model persistence  

---
