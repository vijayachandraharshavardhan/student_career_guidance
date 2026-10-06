# Student Career Guidance

The learning site and exam are HTML/CSS-only. The only JavaScript is inline in `certificate.html`, where it scores the submitted exam and displays the result.

## Project structure

- `index.html`: landing page
- `login.html`, `register.html`: static account-flow previews
- `dashboard.html`, `courses.html`, `curriculum.html`: student learning pages
- `curriculum.html`: separate course directory
- `python-curriculum.html`, `python-course.html`: Python roadmap and its 29 detailed lessons
- `java-course.html`: Java Full Stack, 14 modules
- `mern-course.html`: MERN Stack, 14 modules
- `genai-course.html`: Python Full Stack + GenAI, 16 modules
- `quiz.html`, `course-test.html`: CSS-only assessment demos
- `final-test.html`: 100-question GET form (25 Frontend, 25 Python, 25 Django/Backend, 25 Database)
- `certificate.html`: browser-side score check; passes at 40/100 and displays a named printable certificate
- `placement.html`: general campus placement guidance
- `css/`: shared and page-specific stylesheets
- `images/logo.svg`: project mark

## Run

Open `index.html` in a modern browser. The pages link to each other and do not require a local server.

## Learning pathways

- Python Full Stack: 29 modules across frontend (5), Python + backend (13), and database (11), followed by course assessments and a Grand Final.
- Java Full Stack: 14 modules from Java fundamentals through Spring Boot, SQL/JPA, React, testing, security, deployment, and capstone.
- MERN Stack: 14 modules covering MongoDB, Express, React, Node, API integration, security concepts, testing, deployment, and capstone.
- Python Full Stack + GenAI: 16 modules spanning Python web foundations, model APIs, prompt design, embeddings, RAG, evaluation, safety, and capstone.

The Python syllabus includes concept outlines, practice tasks, project assessments, and a Grand Final. The 100-question final is split evenly across Frontend, Python, Django/Backend, and Database.

## Static prototype limits

The score is calculated in the browser from GET parameters and is not tamper-proof or stored on a server. A secure official certificate, saved attempts, real accounts, or protected admin roles require a backend. Sign-in and registration remain mockups.
