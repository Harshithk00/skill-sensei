# ATLAS-AI 🚀 – Personalized Learning & Job Prep Assistant

[![Watch the demo](https://img.youtube.com/vi/oC-UleEl5vA/0.jpg)](https://youtu.be/oC-UleEl5vA)

> A hackathon project submitted to [Hackathon Name], ATLAS-AI is a smart, AI-driven platform that helps students and job seekers prepare for exams, interviews, and upskilling — with personalized feedback and realistic mock simulations.

---

## 🌟 Problem Statement

Preparing for exams, interviews, or skill assessments is often time-consuming, unstructured, and lacks personalized feedback. Learners and job seekers typically:
- Don’t know which topics they are weak in
- Waste time on generic resources that don't match their skill gaps
- Lack instant, tailored feedback
- Struggle with interview anxiety and don’t get enough realistic practice
- Don’t have a clear roadmap to reach their goals

---

## ✅ Our Solution

We built **ATLAS-AI** – an all-in-one personalized learning assistant that:
- Evaluates users based on MCQ and subjective answers
- Analyzes topic-wise performance using AI
- Identifies weak topics and recommends targeted resources
- Simulates mock interviews with emotional analysis
- Supports voice-based Q&A with transcription and response
- Helps users discover jobs and apply easily

---

## 🔍 Key Features

- 🎯 **Topic-wise performance report**
- 🧠 **AI-generated questions & answers**
- 📊 **Weak topic detection using label accuracy**
- 💬 **Mock interview with facial expression & voice emotion detection**
- 🎤 **Speech-to-text & Text-to-speech interface**
- 💼 **Job discovery & recommendation**
- 🧾 **Personalized feedback for every submission**
- 💻 **Integrated ETH payment (via Ethers.js)**

---

## 🧪 How We Built It

- FastAPI backend for question generation, scoring, and feedback
- Whisper for speech-to-text transcription
- DeepFace for emotion detection in video interviews
- Groq LLM for answer analysis
- React + Tailwind frontend
- Ethers.js for ETH-based payments
- Cloudinary for image/video uploads

---

## 🎓 Identifying Weak Topics Accurately

We struggled to break down performance in a way that clearly identifies a user's weak areas without being overly simplistic.

### ✅ Solution:
We tagged each question with a topic label and analyzed accuracy trends across those tags to build a **topic-wise performance report**.

---

## 🛠 Tech Stack

- **Frontend**: React, TailwindCSS, React Router
- **Backend**: FastAPI, Python
- **AI Models**: OpenAI/Groq, DeepFace, Whisper
- **Blockchain**: Ethers.js
- **Storage**: Cloudinary
- **Deployment**: Vercel, Render

---

## 🧾 How to Run

### 🔧 Development

```bash
# Install dependencies
npm install

# Run in dev mode
npm run dev
