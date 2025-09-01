# పండుగల కథల సేకరణ - Festival Story Collector

## Developers
- S_Naresh_Sai_Aravind  
- reethikareddy  
- bhargavi_kankanala  
- yashwanth_chowdary_19  
- shravan97  

---

## 📖 Project Overview
The **Festival Story Collector** is a **Streamlit-based web application** designed to collect and manage stories related to various festivals, with a primary focus on **Telugu festivals**.  

This project aims to build a rich repository of cultural narratives, making them accessible and preserving them for **future generations**.

---

## ✨ Features
- **Story Submission** → Users can submit new festival stories with relevant details.  
- **Story Viewing** → Browse and read collected festival stories.  
- **API Integration** → Communicates with a backend API (`SwechaAPIClient`) for data persistence and retrieval.  
- **User-Friendly Interface** → Built with **Streamlit** for an interactive and intuitive experience.  
- **Language Support** → Primarily targets **Telugu** stories, with UI elements in Telugu.  

---

## 🚀 Getting Started

### 🔹 Prerequisites
- Python 3.8+  
- pip (Python package installer)  

### 1️⃣ Clone the Repository
```bash
git clone <your-repository-url>
cd festival-story-collector
```

### 2️⃣ Set up a Virtual Environment (Recommended)
```bash
python -m venv venv
# On Linux/Mac
source venv/bin/activate  
# On Windows
venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Environment Variables
Create a `.env` file in the root directory:  

```bash
# .env
SWECHA_API_BASE_URL="http://localhost:8000/api/v1"  # Replace with your actual API endpoint
# Add any other necessary environment variables here, e.g., API keys
```

> ⚠️ The `SWECHA_API_BASE_URL` should point to your backend API.

### 5️⃣ Run the Application
```bash
streamlit run app.py
```

By default, the app will open at:  
👉 http://localhost:8501

---

## 📂 Project Structure
```
festival-story-collector/
│── app.py                  # Main Streamlit application
│── requirements.txt        # Python dependencies
│── .env.example            # Example environment file
└── utils/
    └── api_client.py       # Handles communication with the Swecha API
```

---

## 🤝 Contributing
We welcome contributions to the Festival Story Collector!  
- Submit issues  
- Fork the repository  
- Create pull requests  

---

## 📜 License
This project is licensed under the **MIT License**.
