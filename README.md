Skill Sensei
Empowering learners and job seekers with AI-driven personalized assessments and skill development.

🧠 Overview
Skill Sensei is an AI-powered platform designed to assist students and job seekers in identifying their weak areas through personalized assessments. By analyzing performance trends, it offers targeted resources and realistic practice environments, including interview simulations, to enhance learning outcomes and boost confidence.

🚀 Features
Personalized Assessments: Tailored quizzes to evaluate individual strengths and weaknesses.

Topic-wise Performance Reports: Detailed analytics highlighting areas that need improvement.

Interview Simulations: Realistic mock interviews to prepare users for real-world scenarios.

Resource Recommendations: Curated materials based on user performance to aid in skill enhancement.

Progress Tracking: Monitor improvement over time with comprehensive dashboards.

🎯 Problem Statement
Preparing for exams, interviews, or skill assessments is often time-consuming, unstructured, and lacks personalized feedback. Learners and job seekers typically:

Struggle to Identify Weak Areas: Without clear insights, it's challenging to focus on areas that need improvement.

Waste Time on Generic Resources: Generic study materials may not address specific individual needs.

Lack Instant, Tailored Feedback: Immediate feedback is crucial for effective learning and confidence building.

Face Interview Anxiety: Without realistic practice, interviews can be daunting and stressful.

Skill Sensei addresses these challenges by providing a structured, personalized, and interactive platform for skill development.

🛠️ Technologies Used
Frontend: React, Tailwind CSS, Vite

Backend: Node.js, Express, MongoDB

Authentication: JWT, Cookie-based Auth

AI & Machine Learning: TensorFlow.js, @google/generative-ai

Payment Integration: Stripe

Blockchain: Ethers.js, Hardhat

Cloud Services: Cloudinary for media storage

Others: Axios, React Router, Chart.js, ESLint

🧪 Challenges Faced
Accurate Weak Topic Identification: Initially, breaking down performance to pinpoint weak areas without oversimplification was challenging. We implemented topic tagging for each question and analyzed accuracy trends to generate detailed performance reports.

Realistic Interview Simulations: Creating authentic interview experiences required integrating AI-driven question generation and response evaluation, which was complex but achieved through iterative testing.

Seamless Integration of Diverse Technologies: Combining various tools and libraries posed compatibility issues, resolved through modular architecture and thorough testing.

📦 Installation & Setup
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/skill-sensei.git
cd skill-sensei
Install dependencies:

bash
Copy
Edit
npm install
Set up environment variables:

Create a .env file in the root directory and add the necessary environment variables:

env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
Run the application:

bash
Copy
Edit
npm run dev
The application will be available at http://localhost:3000.

📸 Screenshots

User dashboard showcasing performance metrics.


Personalized assessment interface.


AI-driven interview simulation module.

📽️ Demo Video
For a comprehensive overview, watch our demo video:

[![Watch the demo](https://img.youtube.com/vi/oC-UleEl5vA/0.jpg)](https://youtu.be/oC-UleEl5vA)


