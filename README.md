
# 👗 FitFindr — Your AI Stylist for Every Body

FitFindr is an AI-powered fashion recommendation app that personalizes outfit ideas based on your body shape, style, and confidence.
Upload a photo or describe your vibe — FitFindr uses computer vision, Gemini AI, and web intelligence to curate outfits that fit you, not just your size.

## 🌟 Features

👕 Smart Outfit Classification: YOLO model classifies clothing types from Pinterest images.

🧠 AI Style Reasoning: Gemini Pro explains why specific fits work for your body and aesthetic.

❤️ Personalized Recommendations: Combines your style input + AI reasoning to suggest curated outfits.

🔁 Feedback Loop: Like/dislike to refine your future recommendations.

💾 Lightweight Architecture: JSON datastore for simple, fast MVP performance.

## 🧱 Tech Stack

Frontend: ReactTS + CSS + HTML 
Backend: Python (FastAPI)
AI Models: YOLOv8, Google Gemini 2.5 Pro, CLIP Embeddings
Data: Pinterest-scraped outfit images, hierarchical JSON fashion taxonomy

## 🚀 Getting Started
1️⃣ Clone the repo
git clone https://github.com/yourusername/fitfindr.git
cd fitfindr

2️⃣ Backend Setup
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

3️⃣ Frontend Setup
cd frontend
npm install
npm start

4️⃣ Open in browser

Go to http://localhost:3000 and start exploring your AI stylist 🎨

## 🧠 Inspiration

We built FitFindr because fashion shouldn’t be intimidating or exclusive.
People deserve clothes that celebrate who they are — not who the internet thinks they should be.
So we created a bridge between AI and self-confidence — helping people discover their best fits effortlessly.
