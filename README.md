# 🎓 SPPU AI Animator 

An intelligent, cloud-native educational tool designed to simplify **SPPU Computer Engineering** syllabus topics through Generative AI storytelling and narration.

## 🚀 The Architecture
The application follows a **Full-Stack Serverless** pattern:
1. **Frontend:** A responsive Vanilla JS interface that captures user topics and characters.
2. **Cloud Logic:** An **AWS Lambda** function (Python) triggered via a Function URL.
3. **AI Core:** Integration with **Google Gemini 2.5 Flash** for high-speed, contextual content generation.
4. **Voice Engine:** Utilization of the browser's **Web Speech API** for real-time pedagogical narration.



## 🛠️ Tech Stack & Skills Demonstrated
* **Cloud:** AWS Lambda, IAM Role Management, CORS Configuration.
* **Backend:** Python 3.x, `urllib` for low-latency API calls (no external bloat).
* **AI:** Prompt Engineering for educational consistency.
* **Frontend:** Asynchronous JavaScript (Fetch API), CSS3 Transitions, HTML5.
* **DevOps:** Version control via Git and automated deployment via GitHub Pages.

## 📖 How to Use
1. Enter a complex engineering topic (e.g., "Binary Search Trees").
2. Define an AI Character (e.g., "Sumedh the Rabbit").
3. Click **Generate** to receive a custom-tailored 3-sentence visual explanation.
4. Click **Listen to Story** to hear the AI narrator explain the concept.

---
*Developed as a portfolio project to demonstrate AWS Serverless and Generative AI integration.*
