# 🌠 DayPilot – AI Daily Planner & Task Generator

An interactive web app that lets users **generate personalized daily to-do lists, schedule tasks, and receive productivity tips** — all powered by **Google’s Gemini API**.  

Built with **React, Vite, Tailwind CSS, and TypeScript**, this app provides a modern, responsive, and fast frontend experience.

---

## 🎯 Project Objective

To create a **fully interactive, front-end web app** where users can **generate structured daily plans** instantly using AI, without a backend. The app focuses on usability, speed, and clarity, and works on both desktop and mobile browsers.

---

## 🚀 Live Demo

🔗 [Visit the Website](https://day-pilot-tangerine.lovable.app/)  

**GitHub Repo:** [https://github.com/Aadya2901/day-pilot](https://github.com/Aadya2901/day-pilot)

### Demo Video
[Watch Demo on YouTube](https://youtu.be/a1ljZ7UO0uI?si=Woa-moxh4CMqbfzz)

---

## 🖥️ Tech Stack

- **React 18 + TypeScript**  
- **Vite** for fast development and bundling  
- **Tailwind CSS + shadcn/ui** for responsive UI components  
- **Google Gemini API** via AI Studio for AI-generated daily plans  
- Fully front-end, no backend required  

---

## 🌟 Features

### *QuickPlan*
- 📝 Enter daily goals or tasks  
- Click **Generate Plan** to get a structured schedule  
- AI generates **priority tasks, estimated time blocks, and productivity tips**  

### *SmartBreaks*  
- ⏱️ Suggested break times to maximize focus  
- Reduces decision fatigue and keeps the user on track  

### *ProductivityTips*  
- 💡 Quick actionable tips based on tasks  
- Helps users improve efficiency and organization  

### *User-Friendly Interface*  
- ✨ Clean UI for desktop and mobile  
- Output panel displays AI-generated plan clearly  
- Copy or save the generated plan  

---

## 📁 Folder Structure

```
day-pilot/
├── public/ # Static assets
├── src/
│ ├── components/ # Reusable React components
│ ├── pages/ # Pages (Landing, Planner, etc.)
│ ├── App.tsx # Main app component
│ ├── main.tsx # ReactDOM render
│ └── index.css # Global styles
├── .env # API keys
├── package.json # Dependencies
├── tsconfig.json # TypeScript config
├── tailwind.config.ts # Tailwind config
├── vite.config.ts # Vite config
└── README.md # This file
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/<your-username>/day-pilot.git
cd day-pilot
```

2. Install Dependencies
   
```
npm install
```

3. Add Gemini API Key

Create a .env file in the root:

```
VITE_GEMINI_API_KEY=your_api_key_here
```

4. Run Locally

```
npm run dev
```

Open the URL shown in the terminal to see your app running locally.

5. Build for Production

```
npm run build
```

Deploy the dist folder on Vercel, Netlify, or GitHub Pages.

---

## 📸 Screenshots / Demo Video

### Landing Page
![Landing Page](images/landing_page_ss.png)

### Prompt Page
![Prompt Page](images/give_agenda_ss.png)

### AI Generated Plan
![Generated Plan](images/generated_plan_ss.png)


---


👥 Contributors

| Name | Role |
|------|------|
| @aadya2901 | Leader, AI Integration, Landing Page, Deployment, Documentation |
| @iam-anish15 | UI Design, Styling, Frontend Enhancements |
| @ananyamishra13 | Pages & Components Development, Output Panel |


---


## 🤝 Contributing

We welcome contributions, improvements, and bug fixes:

1. Fork the project  
2. Create your feature branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m 'Add your feature'`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

---

📝 License

This project is open source under the MIT License. Use it for personal or educational purposes.

---

💬 Final Note

"Plan your day in seconds, stay productive, and reduce overwhelm — powered by AI!" 🚀

---


