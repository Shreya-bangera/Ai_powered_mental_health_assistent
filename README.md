# 🧠 MindfulAI – AI-Powered Mental Health Companion

MindfulAI is an intelligent mental health assistance platform designed to support users in monitoring and improving their emotional well-being.  

By combining **Artificial Intelligence, Sentiment Analysis, and Psychometric Profiling**, MindfulAI provides users with personalized insights, emotional support, and mental health recommendations.

The platform acts as a **24/7 AI companion** that helps users understand their emotions, track mood patterns, and receive personalized coping strategies.

---

# 🌟 Features

## 🤖 AI Chatbot for Emotional Support
- AI-powered conversational chatbot.
- Generates empathetic responses using **LLM (Large Language Model)**.
- Detects emotional tone during conversations.
- Helps users discuss feelings, stress, and daily challenges.

---

## 📓 Diary-Based Sentiment Analysis
- Users can write **daily journal entries**.
- Sentiment analysis classifies entries as:
  - Positive
  - Neutral
  - Negative
- Uses **Hugging Face Transformer model** to detect emotional patterns.
- Tracks emotional trends over time.

---

## 🧠 Psychometric Personality Profiling
- Uses **Big Five Personality Test dataset**.
- Users complete a personality questionnaire.
- Applies **K-Prototypes clustering algorithm** to group users into personality clusters.
- Helps understand behavioral patterns and personality traits.

---

## 🎯 Personalized Mental Health Recommendations
MindfulAI generates personalized suggestions by combining:

- Sentiment trends from diary entries
- Personality cluster results

Examples of recommendations include:

- Stress relief activities
- Mindfulness exercises
- Emotional coping strategies
- Mental wellness resources

---

## 🔐 Secure User Authentication
- Secure user **Signup & Login**
- Session management
- Stores user-specific data securely
- Ensures **privacy and confidentiality**

---

# ⚙️ Tech Stack

### Backend
- FastAPI (Python)

### Frontend
- HTML
- CSS
- JavaScript

### Machine Learning
- Hugging Face Transformers
- Scikit-learn
- KModes (K-Prototypes Clustering)
- NumPy
- Pandas

### LLM Integration
- OpenRouter API
- mistralai/mistral-7b-instruct

### Database
- MySQL
- SQLModel ORM

---

# 🚀 How It Works

1️⃣ **User Signup / Login**  
Users create an account and securely log in.

2️⃣ **AI Chat Interaction**  
Users can talk to the AI chatbot for emotional support.

3️⃣ **Diary Logging**  
Users write daily journal entries which are analyzed for sentiment.

4️⃣ **Psychometric Assessment**  
Users complete a personality questionnaire.

5️⃣ **Recommendation Engine**  
The system combines mood trends and personality profiles to generate personalized recommendations.

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/MindfulAI.git
cd MindfulAI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the FastAPI server

```bash
uvicorn main:app --reload
```

Open in browser

```
http://localhost:8000
```

---

# 📡 API Endpoints

| Endpoint | Description |
|--------|-------------|
| `/signup` | User registration |
| `/login` | User authentication |
| `/chat` | AI chatbot interaction |
| `/diary` | Save journal entries |
| `/sentiment` | Sentiment analysis |
| `/recommendations` | Personalized suggestions |

---

# ✨ Key Benefits

✔ 24/7 emotional support  
✔ AI-driven mood analysis  
✔ Personalized mental health insights  
✔ Privacy-first design  
✔ Simple and intuitive interface  

---

# 🔮 Future Improvements

- Mobile application  
- Voice-based emotion detection  
- Mental health progress dashboard  
- Therapist consultation integration  
- Advanced emotion detection models  

---

# 👩‍💻 Author

**Shreya Bangera**  

Final Year – Information Science Engineering  
AI & Full Stack Developer
