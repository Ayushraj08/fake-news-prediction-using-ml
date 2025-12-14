# 📰 Fake News Prediction Using Machine Learning

An **ML-powered full-stack web application** that detects **fake vs real news** using **ensemble machine learning techniques**, supporting **text, URL, and document-based analysis** with high confidence scoring.

Built with a **modern frontend**, **serverless ML inference**, and **scalable architecture**, this project demonstrates real-world application of ML beyond notebooks.

---

## 🚀 Live Capabilities

- 🔍 **Text Analysis** – Detect fake/real news from raw text
- 🌐 **URL Analysis** – Extract and analyze news content from links
- 📄 **Document Analysis** – Upload files (PDF/DOC) for verification
- 🧠 **Ensemble Prediction** – Combines multiple ML signals for accuracy
- 📊 **Confidence Scoring** – Transparent prediction probabilities
- ⚡ **Real-time Inference** – Fast predictions via serverless functions
- 🎨 **Modern UI** – Responsive, clean, and intuitive interface

---

## 🧠 How It Works (High Level)

1. User submits **text / URL / document**
2. Content is **cleaned & normalized**
3. Multiple ML models analyze the input
4. Results are combined using **ensemble logic**
5. Final verdict + confidence is returned in real time

---

## 🛠️ Tech Stack

### Frontend
- **React + TypeScript**
- **Vite**
- **Tailwind CSS**
- Responsive & mobile-friendly UI

### Backend / ML Inference
- **Supabase Edge Functions (Serverless)**
- Ensemble ML prediction logic
- URL & document content extraction

### ML Concepts Used
- Text preprocessing & normalization
- Multiple model inference
- Ensemble decision making
- Probability-based confidence scoring

---

## 📂 Project Structure

```text
fake-news-prediction-using-ml/
│
├── frontend/                 # React + TypeScript frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── routes/
│
├── supabase/
│   └── functions/            # Serverless ML logic
│       ├── predict-text/
│       ├── ensemble-predict/
│       ├── extract-url/
│       └── analyze-document/
│
├── README.md
├── .gitignore
└── package.json


---

## ⚙️ Local Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/Ayushraj08/fake-news-prediction-using-ml.git
cd fake-news-prediction-using-ml
```
### 2️⃣ Install Frontend Dependencies
```
cd frontend
npm install
```

### 3️⃣ Configure Environment

**Create a .env file:**
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_anon_key
```

### 4️⃣ Run Frontend
```
npm run dev
```

### 5️⃣ Deploy Supabase Functions
```
supabase functions deploy
```
## 📸 Screenshots
<img width="1899" height="929" alt="Screenshot 2025-12-14 180746" src="https://github.com/user-attachments/assets/de9f5b38-5bbc-45c4-860f-415a34312f92" />
<img width="1903" height="923" alt="Screenshot 2025-12-14 180756" src="https://github.com/user-attachments/assets/61581579-d567-45db-b6ab-5414f5e326b9" />
<img width="1906" height="930" alt="Screenshot 2025-12-14 180808" src="https://github.com/user-attachments/assets/8406addd-cc5a-4fc5-a462-47bd831eee19" />
<img width="1897" height="927" alt="Screenshot 2025-12-14 180817" src="https://github.com/user-attachments/assets/2275264c-6d32-4b02-b05b-922eda7867b4" />
<img width="1894" height="928" alt="Screenshot 2025-12-14 180830" src="https://github.com/user-attachments/assets/67a22def-2478-45c0-974a-51da1fc15ccd" />

## 📈 Why This Project Stands Out

- ✅ **Not a notebook** — a real production-grade application  
- ⚡ **Serverless ML inference** using modern cloud architecture  
- 📄 **Multiple input formats** — text, URL, and document analysis  
- 🔁 **End-to-end ML deployment** (not just model training)  
- 🧩 **Clean, scalable, industry-aligned architecture**

> This project reflects how **machine learning systems are actually built and deployed** in startups and product-driven teams.

---

## 🎯 Use Cases

- 📰 Journalism & media verification  
- 🕵️ Fact-checking platforms  
- 🎓 Educational institutions  
- 📊 Research & policy analysis  
- 🛡️ AI safety & misinformation detection  

---

## 👨‍💻 Author

**Ayush Raj**

- 🔗 GitHub: [https://github.com/Ayushraj08](https://github.com/Ayushraj08)
- 💼 LinkedIn: [https://www.linkedin.com/in/ayussh-raj](https://www.linkedin.com/in/ayussh-raj)

---

## ⭐ Acknowledgements

Inspired by **real-world misinformation challenges** and built to showcase **practical ML engineering**, not just theory.

> If you find this project useful, please ⭐ the repository — it helps a lot!
