# 🎙️ Audio-To-Video LLM Model

This project uses **OpenAI Whisper** to convert audio into text and then refines the transcribed text using a **Large Language Model (LLM)** for better accuracy and context.

---

## ✨ Features

- ✅ Converts audio input to text using Whisper  
- ✅ Refines or corrects the transcription with an LLM  
- ✅ Organized **backend** (`llm_server`) and **frontend** structure  
- ✅ Modern stack with **Vite**, **ESLint**, **Node.js**, **Python**, and more

---

## 📂 Project Structure

├── backend/
│ ├── llm_server/
│ │ └── server.js
│ ├── app.py
│ ├── .env
│ ├── package.json
│ ├── package-lock.json
│ ├── requirements.txt
│ └── node_modules/
│
├── frontend/
│ ├── public/
│ ├── src/
│ ├── index.html
│ ├── package.json
│ ├── package-lock.json
│ ├── vite.config.js
│ ├── eslint.config.js
│ └── .gitignore



---

## ⚙️ Tech Stack

**Backend:**  
- Python (Flask, Whisper, OpenAI, Transformers)  
- Node.js server (`llm_server`)

**Frontend:**  
- Vite  
- JavaScript  
- HTML / CSS  
- ESLint for linting

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

git clone https://github.com/jayanth-amujuri/Audio-To-Video-LLM-Model.git

cd Audio-To-Video-LLM-Model

pip install -r backend/requirements.txt

cd backend

python app.py

cd backend/llm_server

node server.js

3️⃣ Setup & Run the Frontend

cd frontend

npm install

npm run dev
