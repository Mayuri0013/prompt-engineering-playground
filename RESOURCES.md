# 📚 Prompt Engineering Playground — Resources

Welcome to the Prompt Engineering Playground!

This document contains the resources, setup instructions, and guidelines needed to understand the project and contribute to it.

---

## 1. Project Overview

Prompt Engineering Playground is a beginner-friendly application that helps users create, compare, and evaluate AI prompts.

Users can:
- Create improved prompts using a prompt builder.
- Compare AI-generated responses from two prompts.
- Evaluate prompt quality using a rule-based scoring system.

---

## 2. Key Concepts

### Prompt Engineering
The process of designing and improving instructions given to an AI model to obtain more useful responses.

### Prompt Templates
Reusable prompt structures that can be customized for different topics, audiences, and purposes.

### Prompt Evaluation
Assessing prompt quality using criteria such as specificity, clarity, context, and structure.

### API
An Application Programming Interface allows different software applications to communicate with each other.

### FastAPI
A Python framework used to build the backend API.

### Groq API
The API used by this project to generate AI responses.

---

## 3. Prerequisites

Before contributing, you should have:

- Basic knowledge of HTML, CSS, and JavaScript.
- Basic Python knowledge.
- Python 3.10 or later.
- Git and GitHub.
- A code editor such as Visual Studio Code.
- A Groq API key for testing AI response generation.

---

## 4. Project Structure

```text
prompt-engineering-playground/
│
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   └── .env
│
├── index.html
├── style.css
├── script.js
├── README.md
├── RESOURCES.md
└── .gitignore
```

---

## 5. Setup Instructions

### Step 1: Clone the Repository

```bash
git clone https://github.com/Mayuri0013/prompt-engineering-playground.git
cd prompt-engineering-playground
```

### Step 2: Create a Virtual Environment

```bash
cd backend
python -m venv venv
```

Activate it on Windows PowerShell:

```powershell
.\venv\Scripts\Activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Configure the API Key

Create a `.env` file inside the `backend` folder.

Add:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Replace the placeholder with your own API key.

**Never commit your API key to GitHub.**

### Step 5: Start the Backend

```bash
uvicorn main:app --reload
```

The backend runs at:

http://127.0.0.1:8000

API documentation:

http://127.0.0.1:8000/docs

### Step 6: Start the Frontend

Open the project folder in VS Code.

Use the Live Server extension to open `index.html`.

---

## 6. Learning Resources

### HTML, CSS, and JavaScript
- MDN Web Docs: https://developer.mozilla.org/
- JavaScript Guide: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide

### Python
- Python Tutorial: https://docs.python.org/3/tutorial/

### FastAPI
- Official Documentation: https://fastapi.tiangolo.com/

### Git and GitHub
- Git Documentation: https://git-scm.com/doc
- GitHub Docs: https://docs.github.com/

### Prompt Engineering
- OpenAI Prompt Engineering Guide: https://platform.openai.com/docs/guides/prompt-engineering

### Groq API
- Groq Documentation: https://console.groq.com/docs

---

## 7. Tools Used

- Visual Studio Code
- Git and GitHub
- Python
- FastAPI
- Groq API
- HTML, CSS, and JavaScript

---

## 8. Before Picking an Issue

Before starting work:

1. Read the project README.
2. Read the issue description carefully.
3. Check the acceptance criteria.
4. Set up the project locally.
5. Test the existing functionality.
6. Ask questions in the issue if anything is unclear.

---

## 9. Pull Request Submission Guidelines

1. Fork the repository.
2. Clone your fork locally.
3. Create a new branch for your changes.
4. Implement the feature or fix.
5. Test your changes.
6. Commit your work with a clear commit message.
7. Push your branch to GitHub.
8. Open a pull request against the original repository.
9. Describe your changes and reference the related issue.

---

## 10. Glossary

| Term | Meaning |
|---|---|
| API | Application Programming Interface |
| AI | Artificial Intelligence |
| Backend | Server-side application logic |
| Frontend | User-facing interface |
| Prompt | Instruction provided to an AI model |
| Prompt Template | Reusable prompt structure |
| Evaluation | Assessment of prompt quality |
| Repository | A project stored and managed using Git |
| Pull Request | A request to merge proposed code changes |

---

## 11. Contribution

Contributions are welcome!

Explore the open issues, choose one that interests you, and follow the contribution guidelines.

Please test your changes before submitting a pull request.

---

**Happy Building! 🚀**