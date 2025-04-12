# Smart India Hackathon Workshop
# Date: 12.04.2025
## Register Number:212224230091
## Name: HARISH KUMAR S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

SIMU-BOARD is an AI-powered web platform that simulates real-life boardroom interviews for candidate selection and promotion. It generates personalized, domain-relevant questions and evaluates candidate responses using NLP-based relevance scoring. Experts can join live or review interviews asynchronously. The system provides unbiased, quantifiable scores for both questions and answers. A final report helps assess overall candidate suitability for the post.

## Proposed Solution / Architecture Diagram
![ChatGPT Image Apr 12, 2025, 02_13_35 PM](https://github.com/user-attachments/assets/5c350bec-6047-4b17-a5b3-4540b47b8aed)


## Use Cases
1. Candidate Simulation
Real-time interview simulation with a virtual expert.

Ice-breaking → Techno-functional → Managerial questions based on profile.

2. Expert Panel Evaluation
Experts can pose manual or AI-suggested questions.

System evaluates and scores candidate responses based on relevance.

3. Automated Scoring
NLP-based analysis to check response relevance.

AI assigns scores to questions and answers.

4. Reporting & Recommendation
Dashboard summarizing interview performance.

Recommendation engine highlights top candidates based on scores.



## Technology Stack

Layer	Technology
Frontend	React.js, Tailwind CSS
Backend	Node.js, Express.js
Database	PostgreSQL (Relational DB), MongoDB
AI/NLP Engine	Python (Transformers, spaCy, BERT models)
Interview Simulation	WebRTC, Three.js for 3D boardroom visuals
Authentication	OAuth2, JWT
Hosting/DevOps	Docker, Kubernetes, AWS/GCP/Azure

## Dependencies
spaCy / NLTK / HuggingFace Transformers – For NLP tasks like question-answer relevancy.

LangChain / OpenAI / Cohere APIs – For advanced conversational AI.

PostgreSQL – Structured data (users, scores).

MongoDB – Semi-structured data (QA logs, feedback).

React + WebRTC – For real-time video simulation.

Socket.IO – Real-time interaction handling.

D3.js / Chart.js – Dynamic result and analytics dashboard.


