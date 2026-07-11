# Month 01 Sprint B - Final Projects

## Overview

This is the submission repository for the Month 1 Sprint B final projects.

Build any AI-powered application of your choice using the skills you've learned throughout this sprint — FastAPI, Pydantic, authentication, rate limiting, LLM integration, and deployment.

You can pick one of the suggested project ideas or come up with your own. The only requirement is that it must have a FastAPI backend connected to an LLM, a frontend of your choice, and must be deployed live.

---

## Submission Guidelines

### 1. Fork the Repository

Click the **Fork** button at the top-right of this repository.

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/month-01-sprint-B-projects.git
cd month-01-sprint-B-projects
```

### 3. Create a Folder with Your Name

Use lowercase letters and hyphens — no spaces.

```
month-01-sprint-B-projects/
└── john-doe/
    ├── backend.py
    ├── frontend.py        (or index.html / App.jsx / app.py etc.)
    ├── requirements.txt
    ├── .env.example
    ├── .gitignore
    └── README.md
```

> ⚠️ Place all your files inside your named folder. Do not put them in the root of the repo.

### 4. Add a README Inside Your Folder

Your named folder must contain a `README.md` that includes:

```markdown
## Project Name

## What it does
A short description of your project.

## Tech Stack
- Backend: FastAPI
- Frontend: Streamlit / React / HTML etc.
- LLM: Groq (model name)
- Other libraries used

## Live URLs
- Frontend: https://your-frontend-url
- Backend: https://your-backend-url

## How to run locally
Steps to set up and run the project locally.

## Environment Variables
Refer to .env.example for required keys.
```

### 5. Commit and Push

```bash
git add .
git commit -m "Add submission - John Doe"
git push origin main
```

### 6. Open a Pull Request

1. Go to your fork on GitHub
2. Click **Contribute → Open Pull Request**
3. Set the PR title to: `Submission - John Doe`
4. Add the following in the PR description:

```
Project: <your project name>
Frontend URL: https://your-frontend-url
Backend URL: https://your-backend-url
```

> 📌 Your submission is complete once the PR is opened.

---

## What to Submit

| File | Required |
|---|---|
| `backend.py` (or equivalent) | ✅ Yes |
| `frontend.py` / `index.html` / equivalent | ✅ Yes |
| `requirements.txt` | ✅ Yes |
| `.gitignore` | ✅ Yes |
| `.env.example` | ✅ Yes |
| `README.md` inside your folder | ✅ Yes |
| `.env` | ❌ Never commit this |

---

## Deployment

- Deploy your FastAPI backend to **Render** or **Railway**
- Deploy your frontend to **Streamlit Cloud** / **Vercel** / **Netlify** / **GitHub Pages**
- Make sure your frontend calls your **deployed backend URL**, not `localhost`
- Both URLs must be live and working at submission time
