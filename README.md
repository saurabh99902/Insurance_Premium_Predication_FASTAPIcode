🏥 Insurance Premium Prediction – FastAPI & Streamlit

This project predicts an insurance premium category (Low / Medium / High) based on user demographics and lifestyle information.
It uses a machine learning model served via FastAPI and a Streamlit UI for interaction.

🚀 Features

📊 Machine Learning–based premium category prediction

⚡ FastAPI backend with validated request schema

🎨 Streamlit frontend for user interaction

🧠 Feature engineering (BMI, age group, lifestyle risk, city tier)

🐳 Docker support for easy deployment

🧪 Interactive Swagger UI (/docs)

🏗️ Tech Stack

Python

FastAPI – backend API

Streamlit – frontend UI

scikit-learn – ML model

Pandas / NumPy – data processing

Docker – containerization

📁 Project Structure
Insurance_Premium_Predication_FASTAPIcode/
│
├── app.py                 # FastAPI application
├── frontend.py            # Streamlit UI
├── requirements.txt       # Python dependencies
├── Dockerfile             # Docker configuration
├── model/
│   └── model.pkl          # Trained ML model (local use)
├── schema/
│   └── user_input.py      # Pydantic request schema
├── config/                # Helper configs (city tier etc.)
└── README.md              # Project documentation
