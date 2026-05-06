# 🎬 Plotora: The Story Doesn't Stop Here

> A collaborative movie storytelling platform — where fans don't just watch, they create.

---

## 👤 Team Details

| Name | Roll Number | Email |
|------|-------------|-------|
| Samarpan Malhotra | 2211981340 | samarpan1340.be22@chitkarauniversity.edu.in |

---

## 👩‍🏫 Supervisor

**Dr. Swati Goel** — swati.goel@chitkara.edu.in  
Department of Computer Science and Engineering  
Chitkara University, Punjab

---

## 📋 Project Details

| Field | Details |
|-------|---------|
| **Title** | Plotora: The Story Doesn't Stop Here |
| **Type** | Copyright |
| **Course** | Industry Oriented Hands On Experience (22CS422) |
| **University** | Chitkara University, Punjab |
| **Department** | Computer Science and Engineering |
| **Academic Year** | 2025–26 |

---

## 📖 About the Project

Plotora is a MERN stack web application that transforms movie fans from passive viewers into active creative contributors. Users join genre-based movie clubs, vote democratically on which film to discuss, write alternate endings (20–500 words), upvote or downvote each other's stories, and climb a merit-based leaderboard.

The platform solves a real problem — brilliant fan-written endings get buried in YouTube comments and Reddit threads, unrecognised and unarchived. Plotora gives that creativity a structured, fair, and permanent home.

**Tagline:** *The Story Doesn't Stop Here*

---

## ⚙️ Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Frontend | React.js + Vite | Dynamic SPA — real-time updates without page reloads |
| Backend | Node.js + Express.js | REST API, routing, middleware |
| Database | MongoDB Atlas | NoSQL cloud database for flexible story storage |
| Authentication | JWT + bcrypt | Stateless auth, secure password hashing |
| External API | TMDB API | Real movie/TV data — posters, trailers, cast, ratings |

---

## ✨ Key Features

- 🔐 **JWT Authentication** — Secure login/register with token-based sessions
- 🎭 **Genre-Based Movie Clubs** — Action, Sci-Fi, Drama, Comedy, Thriller
- 🗳️ **One-Vote-Per-User System** — Database-level fairness enforcement
- ✍️ **Alternate Endings** — Submit creative endings with 20–500 word limit
- ⏰ **Automated Deadline Locking** — Phase transitions without manual moderation
- 👍👎 **Upvote / Downvote** — Community rates each story with toggle logic
- 🏆 **Leaderboard** — Score = Stories Written + (Upvotes × 2)
-📚 **Permanent Archive** — All community endings are saved permanently  
🔖 **Watchlist** — Bookmark movies and TV shows  
🗑️ **Delete Own Endings** — Authors can remove their own submissions  

---

## 🗂️ Repository Structure

📁 IPR Submission Proof/  
└── Plotora IPR Submission.pdf  

📁 Report and PPT/  
├── Plotora Presentation.pptx
└── Plotora Project Report.docx  

📁 Source Code/  
└── Plotora Source Code.zip  

📄 README.md

---

## 🚀 How to Run the Project

### Prerequisites
- Node.js v18+
- MongoDB Atlas account

### Backend Setup
```bash
cd backend
npm install
# Create .env file with:
# MONGO_URI=your_mongodb_connection_string
# JWT_SECRET=your_secret_key
# PORT=5000
npm run dev
```

### Frontend Setup
```bash
cd frontend
npm install --legacy-peer-deps
npm run dev
```

Open **http://localhost:5173** in your browser.

---

## 📊 Project Outcomes

| Metric | Result |
|--------|--------|
| Manual moderation reduction | 80% via automated phase transitions |
| Vote integrity | 100% — one vote per user enforced at DB level |
| Word limit enforcement | Dual layer — frontend UI + backend API |
| Content rows | 15 rows — 10 movie genres + 5 TV show categories |
| Leaderboard formula | Score = Stories + (Upvotes × 2) |

---

## 🔮 Future Scope

1. **AI Writing Coach** — LLM feedback on pacing, grammar, plot consistency
2. **Multimedia Endings** — Upload concept art alongside text
3. **Mobile App** — React Native cross-platform application
4. **Sponsored Clubs** — Production houses host official contests with prizes
5. **TMDB Deep Integration** — Auto-populate club pages with full cast and trailers

---

## 📄 License

This project was developed for academic purposes under the IOHE programme at Chitkara University, Punjab.  
© 2025–26 Samarpan Malhotra. All rights reserved.

---

*Department of Computer Science and Engineering | Chitkara University Institute of Engineering and Technology | Punjab, India*
