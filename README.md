# JobPrep: AI Interview Preparation Platform 

A full-stack application designed to streamline technical interview preparation. The system uses AI to parse user resumes and dynamically generate interview questions tailored to the candidate's specific skill set.

## Tech Stack
- **Frontend:** React.js (Component-based UI, State Management)
- **Backend:** Django & Django REST Framework (DRF)
- **Authentication:** JWT (JSON Web Tokens) for secure, stateless sessions
- **AI Integration:** Large Language Model (LLM) for resume parsing & question generation
- **Language:** Python, JavaScript

## Key Features
- **Smart Resume Parsing:** Automatically extracts Skill Sets, Certifications, and Projects from uploaded resumes.
- **Dynamic Question Generation:** Uses an LLM to generate high-context interview questions based on extracted data.
- **Personalized Feedback:** Evaluates user responses and provides actionable suggestions for improvement.
- **Secure Authentication:** Robust user login and profile management using JWT.

## System Architecture
1. **User Auth:** Secure login/registration.
2. **Profile & Upload:** Resume ingestion and metadata extraction.
3. **AI Logic:** LLM analyzes parsed data to create a custom questionnaire.
4. **Evaluation:** Real-time feedback loop based on user input.

## Impact
This project bridges the gap between static resume writing and active interview practice, providing a personalized coaching experience at scale.
