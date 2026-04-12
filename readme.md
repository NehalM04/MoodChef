<div align="center">

# 🍳 MoodChef

### *Where Your Mood Meets Your Meal*

A full-stack, mood-driven recipe discovery platform that maps emotional states to culinary choices — helping you find the perfect meal for how you feel right now.

<br/>

![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

</div>

---


## 📖 About the Project

MoodChef bridges the gap between how you feel and what you eat. Instead of searching by ingredient or cuisine alone, the platform lets users discover meals through emotional context — whether they are craving something *cozy*, need an *energy boost*, or want something *fresh and light*.

Built on a modern full-stack architecture with end-to-end type safety, MoodChef prioritizes both developer experience and a seamless in-kitchen UI.

---

## ✨ Features

| Feature | Description |
|---|---|
| **Mood-Based Discovery** | Filter recipes through emotional tags — *Cozy, Fresh, Comfort, Energized* |
| **Advanced Explorer** | Combine Cuisine (Italian, Asian, Indian), Dietary Type (Vegan, Keto, Paleo), and prep time filters |
| **Cooking Mode** | Distraction-free, step-by-step UI designed to minimize cognitive load in the kitchen |
| **Randomizer Engine** | Instant meal suggestion for indecisive users |
| **Secure Authentication** | Session management via Passport.js-based authentication hooks |

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| **Frontend** | React 19, TypeScript, Tailwind CSS | Responsive, declarative UI with utility-first styling |
| **Animations** | Framer Motion | High-fidelity micro-interactions and transitions |
| **Backend** | Node.js, Express.js | Modular REST API with middleware-based authentication |
| **Database** | PostgreSQL + Drizzle ORM | Type-safe SQL operations with automated migrations |
| **Validation** | Zod (Shared Schema) | Runtime validation and static type inference across the full stack |

---

## 📂 Project Structure

```
MoodChef/
│
├── client/           # Frontend — React components, hooks, and UI logic
│   └── src/
│       ├── components/   # Reusable Radix UI components
│       ├── hooks/        # Custom React hooks
│       └── pages/        # Route-level page components
│
├── server/           # Backend — Express API, auth, and database controllers
│   ├── routes/           # API route definitions
│   ├── controllers/      # Business logic handlers
│   └── seed/             # Recipe seeding scripts
│
├── shared/           # Cross-stack — Shared Zod schemas and TypeScript types
│
└── migrations/       # Infrastructure — Drizzle-generated SQL migration files
```

---

## 🚀 Getting Started

### Prerequisites

Ensure the following are installed on your system before proceeding:

- **Node.js** — v20.0.0 or higher ([Download](https://nodejs.org/))
- **PostgreSQL** — A running local or hosted instance ([Download](https://www.postgresql.org/download/))
- **npm** — Included with Node.js

### Installation

**1. Clone the repository**

```bash
git clone <repository-url>
cd MoodChef
```

**2. Install all dependencies**

```bash
npm install
```

**3. Configure environment variables**

Create a `.env` file in the root directory and add your database connection string:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/moodchef
```

> **Note:** Replace `user`, `password`, and `moodchef` with your actual PostgreSQL credentials and database name.

**4. Synchronize the database schema**

```bash
npm run db:push
```

**5. Start the development server**

```bash
npm run dev
```

The application (client + API) will be served concurrently at:

```
http://localhost:5000
```

---

## 💡 Usage

Once running, navigate to `http://localhost:5000` in your browser.

1. **Select your mood** from the home screen (e.g., *Cozy, Energized, Fresh*)
2. **Browse filtered recipes** that match your emotional state
3. **Refine results** using the Advanced Explorer (cuisine, diet, prep time)
4. **Open Cooking Mode** on any recipe for a step-by-step guided experience
5. **Not sure what you want?** Hit the **Randomizer** for an instant suggestion

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m 'feat: add your feature'`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please ensure your code follows the existing TypeScript conventions and passes any relevant validation before submitting.

---
*Developed by **Nehal Mehta**, **Rushikesh Korde**, and **Om Jumle***.

<div align="center">

</div>
