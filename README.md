# Compare Base

Compare Base is a modern, fast web application for comparing businesses side-by-side. It helps users quickly identify differences and performance gaps across companies with a clean, visually rich interface powered by interactive charts.

## 🚀 Features

- 🔍 Side-by-side business comparison
- ⚡ Instant search and filtering across the company directory
- 📊 Interactive radar charts and score breakdowns
- 🧠 Easy-to-use comparison dashboard
- 🌐 Runs directly in the browser
- 🔒 Authentication-protected comparison view (client-side, no backend)

## 📌 Use Cases

- Compare two or more companies across key performance metrics
- Review innovation, sustainability, and customer satisfaction scores
- Identify top-performing businesses in a category
- Analyze structured company data variations at a glance

## 🛠️ Tech Stack

- **Frontend:** React 19 + Vite 8
- **Routing:** React Router v7
- **Charts:** Recharts
- **Styling:** Tailwind CSS v4
- **Hosting:** Vercel

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/compare-base.git
cd compare-base
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open your browser:

```
http://localhost:5173
```

## 🌍 Deployment

This project is deployed using **Vercel**.

To deploy:

```bash
vercel
```

Or connect the repository directly on [vercel.com](https://vercel.com) for automatic deployments on every push.

## 📁 Project Structure

```
Compare Base/
├── public/                  # Static assets (logo, favicon)
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   ├── CompanyCard.jsx
│   │   ├── SearchFilter.jsx
│   │   ├── RadarComparisonChart.jsx
│   │   ├── ScoreComparison.jsx
│   │   └── ProtectedRoute.jsx
│   ├── context/             # Auth state (React Context)
│   ├── data/
│   │   └── companies.json   # Sample company dataset
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Companies.jsx
│   │   ├── Compare.jsx      # Protected comparison dashboard
│   │   ├── About.jsx
│   │   ├── Login.jsx
│   │   └── Signup.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── vite.config.js
└── package.json
```

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the dev server with hot reload |
| `npm run build` | Build production bundle to `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint across the project |

## 🔐 Authentication

The `/compare` route is protected using a client-side auth context. Users must log in or sign up before accessing the comparison dashboard. No real backend is required — this is a demo implementation.

## 📄 License

This project is for personal/demo use. All rights reserved © Compare Base.
