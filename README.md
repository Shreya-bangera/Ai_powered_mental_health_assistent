MindfulAI – Your AI-powered Mental Health Companion
MindfulAI is an intelligent mental health assistance platform designed to support users in monitoring their emotional well-being. By leveraging AI, sentiment analysis, and psychometric profiling, MindfulAI provides personalized insights, recommendations, and a conversational companion to improve mental health outcomes.

🌟 Features
AI Chatbot for Emotional Support
Provides empathetic, conversational responses using LLM.

Helps users to engage in conversations with an AI chatbot trained to respond to mood and emotional states.

Diary-Based Sentiment Analysis
Users can write journal entries.

The system analyzes sentiment int the text as positive, neutral, or negative using Hugging Face transformer to track emotional trends over time.

Psychometric Profiling based on a questionnare.
Uses the Big Five Personality Test dataset.

Applies K-Prototypes clustering to group users into different personality clusters.

Personalized Recommendations
Combines sentiment + psychometric score to generate mental health insights.

Suggests activities, resources, and coping strategies based on mood trends and psychometric profile.

Secure User Authentication
Login, signup, session handling

Stores user-specific data for personalized tracking. and ensures confidentiality of user data.

🛠️ Tech Stack
Backend: FastAPI (Python)
Database: MySQL (SQLModel ORM)
Machine Learning: Hugging Face Transformer - cardiffnlp/twitter-roberta-base-sentiment ( NLP ), Scikit-learn (KModes), NumPy, Pandas
OpenRouter API LLM: mistralai/mistral-7b-instruct
Frontend: HTML, CSS, JavaScript
APIs: Custom endpoints for diary logging, chatbot interaction, and recommendation retrieval
⚡ How It Works
User Signup/Login – Secure authentication to manage personal data.
Chatbot Interaction – Users can converse with the AI, which detects sentiment in real-time.
Diary Entries – Daily logs are analyzed for sentiment and emotional trends.
Psychometric Assessment – Personality quiz and clustering classify users into mental health profiles.
Recommendations – Tailored suggestions are generated based on mood trends and psychometric results.
✨ Key Benefits

24/7 emotional support

Privacy-first design

Personalized insights

Simple and intuitive interface

Improves awareness of emotional patterns
