# 🧑🏻‍🏫 MentorConnect

*Empowering students and mentors to connect, collaborate, and grow together.*  
MentorConnect is a web-based platform that helps university students find and connect with mentors for academic guidance. The platform offers appointment scheduling, real-time notifications, and profile management for both mentors and students.

---

## 🚀 Features

### 🎓 For Students
- Browse mentors by course or name
- Send appointment requests with custom notes
- Receive real-time SMS notifications on appointment status
- View history of past sessions

### 🧑‍🏫 For Mentors
- Set hourly rates and available time slots
- Accept or reject student requests with reasoning
- View past sessions and track interactions

---

## 🛠 Tech Stack

| Layer       | Technology             |
|-------------|------------------------|
| *Frontend*| React, TypeScript, Tailwind CSS |
| *Backend* | Supabase (PostgreSQL + Auth)     |
| *Notifications* | Supabase Edge Functions / Webhooks |
| *Build Tools* | Vite, Bun (alternative to npm) |
| *Deployment* | Vercel or Netlify (optional)  |

---

## 📁 Project Structure

```
MentorConnect/
├── public/                        # Static assets
│   └── index.html                 # HTML template
├── src/
│   ├── components/                # UI components (Navbar, Footer, etc.)
│   ├── pages/                     # Main views (Home, Login, Register)
│   ├── services/                  # API and utility logic
│   ├── supabase/                  # Supabase client setup
│   ├── App.tsx                    # Root app component
│   └── index.tsx                  # React DOM entry point
├── .gitignore                     # Git ignore file
├── README.md                      # Project documentation
├── bun.lockb                      # Bun package manager lock
├── eslint.config.js               # Linting rules
├── package.json                   # Project metadata
├── postcss.config.js              # PostCSS config
├── tailwind.config.ts             # Tailwind CSS theme and settings
├── tsconfig.*.json                # TypeScript config
└── vite.config.ts                 # Vite dev/build config
```

---

## ⚙ Setup Instructions

### 🔧 Prerequisites

- *[Bun](https://bun.sh)* installed (curl https://bun.sh/install | bash)
- A *Supabase* project (Auth + Database)
- Optional: Twilio account for SMS notifications

### 🔨 Installation

1. *Clone the Repository*

bash
git clone https://github.com/pruthvi2602/MentorConnect.git
cd MentorConnect


2. *Install Dependencies*

bash
bun install


3. *Environment Configuration*

Create a .env file in the root with the following:

env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_anon_key


4. *Run the Development Server*

bash
bun dev


Visit http://localhost:5173 to view the app.

---

## 🧠 Challenges Faced

- Migrating from traditional backend to Supabase serverless architecture
- Learning and integrating Bun package manager
- Styling and responsiveness with Tailwind CSS
- Implementing secure real-time updates

---

## 📈 Future Enhancements

- 📊 Mentor rating and feedback system  
- 📹 In-app video calling with scheduling  
- 💳 Credit-based session system  
- 🧪 Skill-based quizzes and onboarding tests  
- 🔔 Push notifications and calendar integration  

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repo
2. Create a new branch: git checkout -b feature-name
3. Make your changes
4. Commit: git commit -m "Add feature"
5. Push: git push origin feature-name
6. Submit a Pull Request

---

## 📞 Contact

- 📧 Email: pruthvubhudhecha02@gmail.com
- 🐙 GitHub: [@pruthvi2602](https://github.com/pruthvi2602)
