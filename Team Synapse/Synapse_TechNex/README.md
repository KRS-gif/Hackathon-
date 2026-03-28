# Sampatti AI  

## 👨‍💻 Student Participants  

| Name | Department | College | Email |
|------|-----------|--------|-------|
| **Pratik Rai** | Department of Computer Technology | Yeshwantrao Chavan College of Engineering, Nagpur | raipratik0101@gmail.com |
| **Archit Gulhane** | Department of Computer Technology | Yeshwantrao Chavan College of Engineering, Nagpur | archilghulhane6@gmail.com |
| **Piyush Bhoyar** | Department of Computer Technology | Yeshwantrao Chavan College of Engineering, Nagpur | piyushbhoyar64805@gmail.com |
| **Priyanshu Behere** | Department of Computer Technology | Yeshwantrao Chavan College of Engineering, Nagpur | priyanshu7behere@gmail.com |

---

## 👨‍🏫 Faculty Mentor  

| Name | Department | College | Email |
|------|-----------|--------|-------|
| **Dr. Kavita Singh** | Department of Computer Technology | Yeshwantrao Chavan College of Engineering, Nagpur | singhkavita19@gmail.com |

---

## 🌐 Live Link
**https://synapse-tech-nex.vercel.app/**  

<p align="center">
  <img src="https://github.com/user-attachments/assets/8ab91bb0-f552-43ef-b0ad-bc051c37d1d7" width="45%" />
  <img src="https://github.com/user-attachments/assets/00a28018-73f6-42f7-9f4e-019191c19bd6" width="45%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6ced0ea3-4ba3-4e8d-b575-f893299453a4" width="45%" />
  <img src="https://github.com/user-attachments/assets/0950ec54-65f1-4804-bfe1-03e3e1fa6fe5a9" width="45%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/544271db-294a-48b5-82ac-51746d8115e9" width="40%" />
</p>

---

## 📌 About the Project

**Sampatti AI** is a comprehensive financial ecosystem designed to revolutionize mutual fund investing. It combines machine learning-based return predictions with a voice-enabled Generative AI advisor to help users make data-backed financial decisions.

While the flagship experience is built natively for **macOS** using SwiftUI, Sampatti AI is a cross-platform solution. The predictive engine and AI backend serve a **Web App** and a **Mobile App**, ensuring users can access their financial insights from any device.

---

## 📊 Model Performance & Accuracy

Sampatti AI utilizes a high-precision Machine Learning model hosted on Google Cloud Run. The model has been rigorously tested and demonstrates high accuracy, particularly for long-term return forecasts (3-year and 5-year horizons), making it a reliable tool for long-term investment planning.

### Performance Metrics

| Prediction Horizon | RMSE | R² Score | Accuracy Level |
|-------------------|------|---------|---------------|
| **1 Year Return** | 4.38 | 0.369 | Moderate |
| **3 Year Return** | 3.98 | **0.878** | **High** |
| **5 Year Return** | 1.66 | **0.741** | **High** |

The model achieves an impressive **R² score of 0.878 for 3-year predictions**, showing a strong correlation between predicted and actual performance.

---

## 🚀 Key Features

### 🤖 AI-Powered Advisor (Gemini Integration)
- Conversational finance assistant **“Alpha”**
- Powered by **Gemini 1.5 Flash**
- Voice-enabled using native Text-to-Speech (AVFoundation)
- Context-aware responses for risk, SIP, and portfolio planning

### 📈 ML Return Predictions
- Custom Python/Flask prediction engine
- Long-term return forecasting (1Y, 3Y, 5Y)
- Input advanced financial parameters:
  - Alpha
  - Beta
  - Sharpe Ratio
  - Sortino Ratio
  - Expense Ratio
  - Risk Level

### 📊 Interactive Dashboard
- Live NAV charts
- Benchmark comparison tool
- Fund analytics dashboard
- Database of **40+ Asset Management Companies (AMCs)**

---

## 🖥️ Cross-Platform Ecosystem

Sampatti AI follows a **single-backend multi-platform architecture**:

1. **macOS Native App**  
   Premium experience with native SwiftUI charts and voice integration.

2. **Web Application**  
   Fully responsive web version accessible from any browser.

3. **Mobile Application**  
   Lightweight companion app for quick predictions and advisor chat.

All platforms communicate with the same hosted backend, ensuring consistent predictions and real-time updates.

---

## 📸 Screenshots

| Dashboard | AI Chat Advisor |
|----------|----------------|
| <img width="1440" height="900" src="https://github.com/user-attachments/assets/32a208b1-9342-45b8-9fea-136b3220005e" /> | <img width="1440" height="900" src="https://github.com/user-attachments/assets/3e3b9fff-0e76-4e8b-9530-1214aa19c18e" /> |

---

## 🛠️ Tech Stack

### Frontend
- Swift
- SwiftUI (macOS Ventura/Sonoma)
- React (Web)
- Native Mobile Framework

### Backend
- Python
- Flask
- Google Cloud Run

### AI & ML
- Google Gemini API
- Machine Learning Prediction Model
- Financial Data Analytics

### Other Tools
- Swift Charts
- AVFoundation (Voice Output)
- URLSession (Networking)

---

## ⚙️ Installation & Setup (macOS)

### Prerequisites
- macOS 13.0 or later
- Xcode 14 or later
- Google Gemini API Key

### Steps

```bash
git clone https://github.com/yourusername/sampatti-ai.git
cd sampatti-ai
