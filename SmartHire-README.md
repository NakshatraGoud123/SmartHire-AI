# 🤖 SmartHire — AI-Powered Job Application Tracker

> **Track smarter. Apply better. Land faster.**  
> An AI-powered full-stack web app that helps job seekers manage applications, get AI-generated cover letters, and analyse job descriptions — all in one place.

![SmartHire Banner](https://img.shields.io/badge/SmartHire-AI%20Powered-0F3460?style=for-the-badge&logo=openai&logoColor=white)
![React](https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 📋 **Application Tracker** | Add, update, and manage all your job applications in one dashboard |
| 🤖 **AI Cover Letter Generator** | Paste a job description → get a tailored cover letter instantly via OpenAI API |
| 🔍 **JD Skill Analyser** | Extracts required skills from any job description and highlights your resume gaps |
| 📊 **Visual Pipeline** | See your job search funnel: Applied → Shortlisted → Interview → Offer |
| 🔐 **Secure Auth** | JWT-based login with role-based access control |
| 📱 **Responsive UI** | Works seamlessly on desktop and mobile |

---

## 🛠️ Tech Stack

**Frontend**
- React.js (Hooks, Context API)
- CSS3 / Responsive Design
- Axios for API calls

**Backend**
- Python 3.x
- Flask (REST API)
- JWT Authentication
- MySQL (database)

**AI & Cloud**
- OpenAI API (GPT) — cover letter & JD analysis
- Firebase Hosting — deployment
- Firebase Auth — user management

---

## 📸 Screenshots

> *(Add your screenshots here after building the project)*

```
/screenshots
  dashboard.png
  tracker.png
  ai-cover-letter.png
  jd-analyser.png
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js >= 16
- Python >= 3.8
- MySQL installed locally
- OpenAI API key ([get one here](https://platform.openai.com))

### 1. Clone the repository
```bash
git clone https://github.com/NakshatraGoud123/SmartHire-AI.git
cd SmartHire-AI
```

### 2. Setup Backend (Flask)
```bash
cd backend
pip install -r requirements.txt

# Create a .env file
cp .env.example .env
# Add your OpenAI API key and MySQL credentials in .env
```

### 3. Setup Database
```bash
mysql -u root -p
CREATE DATABASE smarthire;
# Then run the schema
mysql -u root -p smarthire < schema.sql
```

### 4. Run the Backend
```bash
cd backend
python app.py
# Runs on http://localhost:5000
```

### 5. Setup & Run Frontend
```bash
cd frontend
npm install
npm start
# Runs on http://localhost:3000
```

---

## 📁 Project Structure

```
SmartHire-AI/
├── frontend/
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Dashboard, Tracker, Analyser
│   │   ├── context/         # Auth & App state
│   │   └── App.js
│   └── package.json
│
├── backend/
│   ├── routes/              # API endpoints
│   ├── models/              # DB models
│   ├── ai/                  # OpenAI integration
│   ├── app.py               # Flask entry point
│   └── requirements.txt
│
├── schema.sql               # MySQL schema
└── README.md
```

---

## 🔮 Future Enhancements

- [ ] Chrome extension to auto-fill job applications
- [ ] Email reminders for interview follow-ups
- [ ] Resume scoring against job descriptions
- [ ] Integration with LinkedIn Jobs API

---

## 👤 Author

**D. Nakshatra**  
📧 danturinaksh772@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/naksh-danturi)  
💻 [GitHub](https://github.com/NakshatraGoud123)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you found this useful, please star the repo!**
