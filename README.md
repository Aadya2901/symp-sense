# 🌡️ SympSense — AI Symptom Analysis Assistant  
An AI-powered symptom analysis chatbot that helps users receive instant, reliable health insights. Built with **Vertex AI**, **PaLM API**, and a minimal frontend-first MVP architecture.

---

## 🚀 Overview
SympSense is an intelligent medical assistant that analyzes user symptoms, identifies possible conditions, and offers guidance with a structured safety layer.  
This MVP runs on a **static frontend** with a **Google Cloud Function backend** that communicates with **Vertex AI Agents**.

> ⚠️ *Disclaimer:* This tool is for educational/hackathon use only. It is **not a medical diagnosis system**.

---

## ✨ Features
- 🤖 AI-powered symptom interpretation  
- 🧠 Vertex AI Agents for structured health reasoning  
- 🗣️ Natural language chat interface  
- 🔊 Voice input support  
- 🌙 Modern UI with dark mode  
- ⚡ Lightweight and deployable on any static hosting  
- 🔐 Secure backend proxy for API calls  

---

## 🧩 Tech Stack

### **Frontend**
- HTML5, CSS3, JavaScript  
- TailwindCSS  
- SpeechRecognition API

### **Backend**
- **Google Cloud Functions (Node.js 18)**
- Vertex AI (PaLM)**

### **Other**
- Fetch API  
- JSON API middleware  
- CORS-secure gateway  

---

## 📁 Project Structure

```
SympSense/
│
├── frontend/
│ ├── index.html
│ ├── script.js
│ ├── style.css
│ └── assets/
│ ├── ui_chat.png
│ ├── severity_output.png
│ └── voice_input.png
│
├── backend/
│ ├── index.js
│ ├── package.json
│ └── README.md
│
├── docs/
│ ├── architecture.png
│ ├── prompts.md
│ ├── workflow.md
│ └── api_integration.md
│
├── .gitignore
├── LICENSE
└── README.md
```


---

## 📸 Screenshots

| Chat UI | Output Insight | Voice Input |
|--------|----------------|-------------|
| ![](frontend/assets/ui_chat.png) | ![](frontend/assets/severity_output.png) | ![](frontend/assets/voice_input.png) |

---

## ⚙️ Setup Instructions

### **1. Clone repository**

```
git clone https://github.com/your-username/sympsense.git
cd sympsense
```

### **2. Install backend dependencies**

```
cd backend
npm install
```

## **3. Add your Google Cloud credentials**

Create .env inside backend/

```
PROJECT_ID=<your_project_id>
LOCATION=us-central1
VERTEX_AGENT_ID=<agent_id>
```

## **4. Deploy Cloud Function**

```
gcloud functions deploy sympsense-api \
  --runtime=nodejs18 \
  --trigger-http \
  --allow-unauthenticated
```

## **5. Update frontend script.js**

```
const API_URL = "https://<your-cloud-function-url>";
```

## 🧠 How It Works — Architecture

```
[ User ]
   ↓
Frontend (HTML/JS)
   ↓ fetch()
Cloud Function (Node.js)
   ↓
Vertex AI Agents (PaLM)
   ↓
Structured Medical Output
```

## 🧑‍💻 Contributors

|     Name          |
|-------------------|
| @aadya2901        | 
| @iam-anish15      | 
| @ananyamishra13   | 

---

## 🤝 Contributing

We welcome contributions, improvements, and bug fixes:

1. Fork the project  
2. Create your feature branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m 'Add your feature'`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

---

## 📝 License

This project is open source under the **MIT License**. Use it for personal or educational purposes.  

---

## 💬 Final Note

*"Sense Your Symptoms. Stay Ahead.!"* ⚡

