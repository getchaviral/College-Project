SentimentSphere – AI-Powered Sentiment & Emotion Analysis
Overview

SentimentSphere is an AI-powered Natural Language Processing (NLP) application that analyzes text and identifies both sentiment and emotions. The system leverages transformer-based models to provide accurate predictions along with explainable AI insights.

The project combines modern machine learning techniques with an interactive dashboard to help users understand the reasoning behind predictions.

Features
Sentiment Classification (Positive, Negative, Neutral)
Emotion Detection
Confidence Score Analysis
Explainable AI using LIME
Interactive Dashboard
FastAPI REST API
Real-time Text Analysis
Data Visualization and Insights
Tech Stack
Frontend
Streamlit
Backend
FastAPI
Python
Machine Learning
DistilBERT
Transformers (Hugging Face)
PyTorch
Explainable AI
LIME
Data Processing
Pandas
NumPy
Visualization
Matplotlib
Plotly
System Architecture
User Input
     │
     ▼
FastAPI Backend
     │
     ▼
DistilBERT Model
     │
     ├── Sentiment Prediction
     ├── Emotion Detection
     └── Confidence Scores
     │
     ▼
LIME Explainability
     │
     ▼
Streamlit Dashboard
Project Workflow
User submits text input.
FastAPI receives the request.
DistilBERT processes the text.
Sentiment and emotion predictions are generated.
LIME explains important words influencing the prediction.
Results are displayed through the Streamlit dashboard.
Example Output
Input
I am extremely happy with the product and its performance.
Output
Sentiment: Positive
Emotion: Joy
Confidence: 97.2%
Installation
Clone Repository
git clone https://github.com/your-username/SentimentSphere.git
cd SentimentSphere
Create Virtual Environment
python -m venv venv
Activate Environment

Windows:

venv\Scripts\activate

Linux/Mac:

source venv/bin/activate
Install Dependencies
pip install -r requirements.txt
Run FastAPI Server
uvicorn app:app --reload

API will run on:

http://localhost:8000
Run Streamlit Dashboard
streamlit run dashboard.py

Dashboard will run on:

http://localhost:8501
API Endpoint
Analyze Text
POST /predict

Request:

{
  "text": "This project is amazing!"
}

Response:

{
  "sentiment": "Positive",
  "emotion": "Joy",
  "confidence": 0.98
}
Key Learnings
Natural Language Processing (NLP)
Transformer Models
Sentiment Analysis
Emotion Detection
Explainable AI (XAI)
REST API Development
Interactive Dashboard Design
Future Improvements
Multilingual Sentiment Analysis
Social Media Sentiment Monitoring
Speech-to-Text Sentiment Analysis
Real-Time Data Streaming
Advanced Business Intelligence Dashboard
Author

Aviral Shukla

B.Tech Computer Science
Aspiring Software Engineer & AI Developer
