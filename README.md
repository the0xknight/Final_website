# 🌐 Intrisia — Career Guidance Platform

> A full-stack career guidance platform designed to help students explore careers, discover their interests, build career roadmaps, and connect with professionals.

## ✨ Features

* 🔎 **Career Exploration** — Search and explore different career paths with detailed information about skills, education, salary, opportunities, challenges, and future scope.
* 🧠 **Career Interest Quiz** — Interactive quiz that analyzes user responses using rule-based logic and suggests suitable career domains.
* 🗺️ **Career Roadmaps** — Follow structured career paths, complete individual steps, and track progress.
* 👨‍💼 **Shadow a Professional** — Explore professional profiles and request shadowing sessions.
* 💾 **Persistent Data** — Quiz results, roadmap progress, and shadowing bookings are stored through the backend.

## 🏗️ Architecture

```text
React + Vite
     │
     │ REST API / JSON
     ▼
Flask Backend
     │
     │ PyMongo
     ▼
MongoDB
```

## 🛠️ Tech Stack

**Frontend**

* React
* Vite
* React Router
* Tailwind CSS

**Backend**

* Python
* Flask
* Flask-PyMongo
* PyMongo
* Flask-CORS

**Database**

* MongoDB

## 📂 Project Structure

```text
Final_website/
├── frontend/
│   └── src/
│       ├── components/
│       ├── data/
│       ├── pages/
│       └── App.jsx
│
├── backend/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── app.py
│
└── README.md
```

## 🔌 Main API Routes

```text
/api/careers
/api/quiz
/api/roadmaps
/api/shadow
```

These APIs handle career data, quiz submissions, roadmap progress, and professional shadowing.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/the0xknight/Final_website.git
cd Final_website
```

### 2. Backend

```bash
cd backend
python -m venv venv

# Windows
venv\Scripts\activate

pip install -r requirements.txt
python app.py
```

Create a `.env` file with the required MongoDB and other environment variables.

### 3. Frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

The frontend will run through Vite and communicate with the Flask backend.

## 🔄 User Flow

```text
Explore Careers
       ↓
Learn About Careers
       ↓
Take Career Quiz
       ↓
Get Career Direction
       ↓
Follow Career Roadmap
       ↓
Track Progress
       ↓
Shadow a Professional
```

## 🚧 Future Improvements

* AI/ML-based career recommendations
* Complete user authentication and profiles
* Personalized dashboards
* Dynamic professional profiles
* Advanced roadmap analytics
* Notifications and scheduling
* Improved automated testing
* Production deployment


## 📄 License

This project is licensed under the MIT License.

---

**Intrisia** — *Explore careers. Discover your interests. Build your path.*
