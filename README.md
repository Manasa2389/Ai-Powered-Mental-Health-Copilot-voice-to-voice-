
🧠 AI-Powered Mental Health Copilot (Google Stack)

A hackathon‑ready, full‑stack web application that provides 24/7 empathetic mental health support using AI, built entirely on Google Firebase & GCP.

⚠️ Disclaimer: This application is not a replacement for professional therapy. It acts as a first‑line emotional support system and crisis‑awareness tool.

🚀 Project Overview

Mental health support is often inaccessible, expensive, and stigmatized. Many people hesitate to seek help or lack immediate access to trained professionals.

The AI‑Powered Mental Health Copilot solves this by offering:

Empathetic AI conversations

Mood & emotion tracking

Stress & anxiety detection

Crisis awareness with safety‑first behavior

Secure, private, real‑time experience

Built using Google Stack (Firebase + GCP) for speed, scalability, and hackathon‑grade reliability.

✨ Key Features
1️⃣ Conversational Emotional Support

AI chatbot with empathetic, non‑judgmental responses

Context‑aware conversations using NLP

Users can discuss stress, anxiety, loneliness, burnout, etc.

2️⃣ Mood & Emotion Tracking

Daily mood check‑ins: 😊 Happy | 😐 Neutral | 😟 Stressed | 😰 Anxious | 😢 Sad

Emotion detection from user messages

Visual mood trends (weekly / monthly)

3️⃣ Stress & Anxiety Detection

Detects early warning signs:

Negative thought patterns

Sudden mood shifts

Prolonged stress indicators

AI‑generated coping strategies:

Guided breathing

Mindfulness exercises

Positive affirmations

4️⃣ Crisis Awareness & Safety

Detects high‑risk messages (self‑harm, extreme distress)

Immediately provides:

Emergency helpline numbers

Encouragement to contact trusted people

Ethical & safety‑first AI behavior

5️⃣ Privacy & Security

Firebase Authentication

Secure Firestore database

No public data sharing

Optional anonymous usage

usage

🧱 Tech Stack (Google Stack)

Frontend

React.js

Material UI (MUI) – clean & calming UI

Chart.js / Recharts – mood analytics

Backend & Cloud

Firebase Authentication – secure login

Firestore – real‑time NoSQL database

Cloud Functions – AI processing & risk detection

Firebase Hosting – fast global deployment

AI & NLP

Gemini API / OpenAI API – conversational AI

Hugging Face Transformers – sentiment & emotion detection

spaCy / NLTK – NLP processing

processing

🏗️ Architecture Diagram (Explanation)

[ React + MUI Frontend ]
  |
  | Firebase Auth
  v
[ Firebase Authentication ]
  |
  v
[ Firestore (Real‑time DB) ] <─── Mood Logs / Chat History
  |
  v
[ Cloud Functions (GCP) ]
├─ Sentiment Analysis
├─ Emotion Classification
├─ Stress Detection
└─ Crisis Risk Detection
   |
   v
[ Gemini / OpenAI API ]

Flow:

1 User logs in using Firebase Auth

2 Chats & mood data stored in Firestore (real‑time)

3 Cloud Functions process messages

4 AI APIs generate empathetic responses

5 Risk detection triggers safety workflows


📂 Project Structure

mental-health-copilot/
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ ├── firebase.js
│ │ └── App.jsx
│ └── package.json
│
├── functions/
│ ├── index.js
│ ├── sentiment.js
│ ├── riskDetection.js
│ └── package.json
│
├── firestore.rules
├── firebase.json
└── README.md

🔐 Authentication

Email & Password Login

Optional Anonymous Login

Firebase handles secure session management

📊 Dashboard

Mood history visualization

Emotional trends over time

Recent conversations

Personalized coping suggestions

⚡ Real‑Time Updates

Firestore listeners update UI instantly

Chat responses appear in real time

Mood analytics auto‑refresh

🛠️ Setup & Installation
1️⃣ Clone Repository
git clone https://github.com/your-username/mental-health-copilot.git
cd mental-health-copilot

2️⃣ Frontend Setup
cd frontend
npm install
npm start

3️⃣ Firebase Setup
npm install -g firebase-tools
firebase login
firebase init
Enable:
. Authentication
. Firestore
. Cloud Functions
. Hosting

4️⃣ Cloud Functions
cd functions
npm install
firebase deploy --only functions

5️⃣ Deploy Website
firebase deploy

🌍 Live Demo

After deployment, Firebase provides a public URL:
http://localhost:8085/presentation.html

🧠 Why Google Stack Is Best
✅ Fastest backend setup for hackathons
✅ Built‑in real‑time database
✅ Secure authentication out of the box
✅ Scales automatically with users
✅ Minimal DevOps – focus on product
Google Stack lets you go idea  →  demo  →  production extremely fast.  


