MindfulAI – Your AI-powered Mental Health Companion
MindfulAI is an intelligent mental health assistance platform designed to support users in monitoring their emotional well-being. By leveraging AI, sentiment analysis, and psychometric profiling, MindfulAI provides personalized insights, recommendations, and a conversational companion to improve mental health outcomes.

🌟 Features
1. AI Chatbot for Emotional Support
2. Provides empathetic, conversational responses using LLM.
3. Helps users to engage in conversations with an AI chatbot trained to respond to mood and emotional states.
4. Diary-Based Sentiment Analysis
5. Users can write journal entries.
6. The system analyzes sentiment int the text as positive, neutral, or negative using Hugging Face transformer to track emotional trends over time.
7. Psychometric Profiling based on a questionnare.
8. Uses the Big Five Personality Test dataset.
9. Applies K-Prototypes clustering to group users into different personality clusters.
10.Personalized Recommendations
11.Combines sentiment + psychometric score to generate mental health insights.
12.Suggests activities, resources, and coping strategies based on mood trends and psychometric profile.
13.Secure User Authentication
14.Login, signup, session handling
15.Stores user-specific data for personalized tracking. and ensures confidentiality of user data.


🛠️ Tech Stack
1.Backend: FastAPI (Python)
2.Database: MySQL (SQLModel ORM)
3.Machine Learning: Hugging Face Transformer - cardiffnlp/twitter-roberta-base-sentiment ( NLP ), Scikit-learn (KModes), NumPy, Pandas
4.OpenRouter API LLM: mistralai/mistral-7b-instruct
5.Frontend: HTML, CSS, JavaScript
6.APIs: Custom endpoints for diary logging, chatbot interaction, and recommendation retrieval


⚡ How It Works
User Signup/Login – Secure authentication to manage personal data.
Chatbot Interaction – Users can converse with the AI, which detects sentiment in real-time.
Diary Entries – Daily logs are analyzed for sentiment and emotional trends.
Psychometric Assessment – Personality quiz and clustering classify users into mental health profiles.
Recommendations – Tailored suggestions are generated based on mood trends and psychometric results.



✨ Key Benefits
1. 24/7 emotional support
2. Privacy-first design
3. Personalized insights
4. Simple and intuitive interface
5. Improves awareness of emotional patterns
