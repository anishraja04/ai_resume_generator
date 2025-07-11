#  AI Resume Generator

A full-stack AI-powered resume builder built with **Spring Boot** and **React (Vite)**. Users can generate a professional, structured resume by entering a career-related prompt. The app parses the input using AI logic and displays a ready-to-copy resume output.

---

# Tech Stack

- **Frontend:** React.js (Vite), Tailwind CSS
- **Backend:** Java 17+, Spring Boot, REST APIs
- **Build Tools:** Maven, npm
- **Language Model (Pluggable):** Compatible with OpenAI, DeepSeek, or local LLMs

---

## 🎯 Features

- Generate structured resumes using AI prompt input
- Clean JSON-based data output (name, skills, experience, education, etc.)
- Responsive UI with real-time result rendering
- Copy-to-clipboard integration for resume output
- Backend-ready for LLM or OpenAI API connection

---

## 📁 Project Structure

ai_resume_generator/
├── resume-ai-backend/ # Spring Boot REST API backend
├── resume_frontend/ # React frontend (Vite-based)
└── README.md # You are here!


---

## ⚙️ How to Run Locally

###  Backend (Spring Boot)

1. Make sure **Java 17+** is installed.
2. Navigate to the backend folder:
   ```bash
   cd resume-ai-backend
3. Run the Spring Boot application:

bash
Copy
Edit
./mvnw spring-boot:run -DskipTests
4. App will run on: http://localhost:8080

###  Frontend (React + Vite)
1. Navigate to the frontend folder:
cd resume_frontend

2. Install dependencies:
npm install

3. Run the frontend app:
npm run dev
App will open at: http://localhost:5173

##Example APi Uses

{
  "prompt": "Generate a resume for a front-end developer with 2 years of React experience and good communication skills."
}


📄 License
This project is licensed under the MIT License.

🙌 Acknowledgments
Project inspired by the tutorial from @LearnCodeWithDurgesh(Youtube)
Extended and documented by Anish Ahamad.
