# **Mini Project Collection**

This repository contains small, focused projects designed to practice and showcase backend development and AI/ML skills. Each project serves as a standalone module and can be integrated into larger applications. Here's a list of projects included in this repository.

---

| **#** | **Project Name**                              | **Type**          | **Technologies**                              | **Status**      |
|-------|-----------------------------------------------|-------------------|----------------------------------------------|-----------------|
| **1** | File Upload API                               | Backend           | Express.js, Multer, Node.js                  | **Ongoing**     |
| **2** | Email Verification System                    | Backend           | Node.js, Express, Nodemailer                 | **Ongoing**     |
| **3** | Real-time Notification Demo                  | Backend           | Express.js, Socket.io                        | **Completed**   |
| **4** | Realtime Location Tracker                    | Backend           | Express.js, Socket.io, Leaflet.js            | **Completed**   |
| **5** | WebRTC-based Audio/Video Call Demo           | Backend           | Express.js, WebRTC, Socket.io                | **Ongoing**     |
| **6** | One-Time Link/Token Generation               | Backend           | Express.js, JWT                              | **Ongoing**     |
| **7** | Real-Time Status Updates with WebSockets     | Backend           | Express.js, Socket.io                        | **Ongoing**     |
| **8** | Realtime Progress Tracker (Like Delivery)    | Backend           | Express.js, Socket.io                        | **Ongoing**     |
| **9** | Real-Time Collaborative Editor               | Backend           | Express.js, Socket.io, QuillJS               | **Ongoing**     |
| **10**| Role-Based Access Control (RBAC)             | Backend           | Express.js, JWT                              | **Ongoing**     |
|  | **AI-BASED PROJECTS**                                                                                                                                                               |
| **11**| Image to Text Summarization API              | AI/ML             | Flask, Tesseract OCR, GPT-3/BERT             | **Ongoing**     |
| **12**| Sentiment Analysis on User Reviews           | AI/ML             | Flask, Hugging Face transformers             | **Ongoing**     |
| **13**| Speech to Text (Audio Transcription using DL)| AI/ML             | Python, DeepSpeech, Flask                    | **Ongoing**     |
| **14**| Personalized Recommendation System           | AI/ML             | Flask, Scikit-learn, TensorFlow              | **Ongoing**     |
| **15**| AI-based Chatbot for FAQ Automation          | AI/ML             | Rasa, DialogFlow, Flask                      | **Ongoing**     |
---
## **Projects**

### **1. File Upload API**
A simple API for uploading files with validation, encryption, and storage capabilities.

- **Technologies:** Express.js, Multer, Node.js
- **Features:**
  - File size and type validation
  - Local/Cloud storage support
  - File metadata in response
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **2. Email Verification System**
A system for verifying email addresses using one-time links.

- **Technologies:** Node.js, Express, Nodemailer
- **Features:**
  - Token-based link generation
  - Secure, single-use tokens
  - Link expiry validation
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **3. Real-time Notification Demo**
Real-time notification delivery using WebSockets.

- **Technologies:** Express.js, Socket.io
- **Features:**
  - Server-push notifications
  - Multi-client support
  - Native browser notifications (optional)
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **4. Realtime Location Tracker**
Track and display real-time user locations on a map.

- **Technologies:** Express.js, Socket.io, Leaflet.js
- **Features:**
  - Location tracking with WebSocket updates
  - Geographical map integration
  - Live location marker updates
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **5. WebRTC-based Audio/Video Call Demo**
A peer-to-peer audio/video calling application.

- **Technologies:** Express.js, WebRTC, Socket.io
- **Features:**
  - Direct user connections
  - Audio/Video communication
  - Disconnection handling
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **6. One-Time Link/Token Generation**
Generate secure one-time-use links or tokens.

- **Technologies:** Express.js, JWT
- **Features:**
  - Time-bound token validity
  - Secure API validation
  - Email notification integration
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **7. Real-Time Status Updates with WebSockets**
Track the real-time status of operations or processes.

- **Technologies:** Express.js, Socket.io
- **Features:**
  - Dynamic status updates
  - Broadcasting changes to clients
  - Flexible integration into other workflows
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **8. Realtime Progress Tracker (Like Delivery Status)**
Track progress for deliveries or other multi-step processes.

- **Technologies:** Express.js, Socket.io
- **Features:**
  - Progress tracking with live updates
  - UI-friendly progress indicators
  - Multi-task dashboard support
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **9. Real-Time Collaborative Editor**
Collaborate on a single document with multiple users in real-time.

- **Technologies:** Express.js, Socket.io, QuillJS
- **Features:**
  - Live text synchronization
  - Real-time cursor and user tracking
  - Document change tracking
- [GitHub Repository](#)  
- [Live Demo](#)

---

### **10. Role-Based Access Control (RBAC)**
Manage resource access based on user roles.

- **Technologies:** Express.js, JWT
- **Features:**
  - Role-based route protection
  - Middleware-based role validation


---

## **AI/ML-Based Projects**

### **1. Image to Text Summarization API**
Extract and summarize text from images.

- **Technologies:** Flask, Tesseract OCR, GPT-3/BERT
- **Features:**
  - OCR for image text extraction
  - Text summarization using NLP

### **2. Sentiment Analysis on User Reviews**
Classify user feedback into positive, negative, or neutral sentiments.

- **Technologies:** Flask, Hugging Face transformers
- **Features:**
  - Sentiment classification API
  - Data visualization support

### **3. Speech to Text (Audio Transcription using DL)**
Convert audio files into text transcriptions.

- **Technologies:** Python, DeepSpeech, Flask
- **Features:**
  - High-accuracy audio-to-text conversion
  - Multi-language support

### **4. Personalized Recommendation System**
Recommend personalized content or items.

- **Technologies:** Flask, Scikit-learn, TensorFlow
- **Features:**
  - Collaborative and content-based filtering
  - Dynamic user preference adaptation

### **5. AI-based Chatbot for FAQ Automation**
Automate FAQs with an AI chatbot.

- **Technologies:** Rasa, DialogFlow, Flask
- **Features:**
  - NLP-powered intent detection
  - Scalable FAQ dataset integration

---

## **How to Run**

### **Backend Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mini-projects.git
   cd mini-projects
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the server:
   ```bash
   npm start
   ```

### **Frontend Setup (If applicable)**
1. Navigate to the corresponding frontend directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

### **AI Projects**
1. Navigate to the AI project directory.
2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start the Flask server:
   ```bash
   python app.py
   ```

---

## **Folder Structure**
```
project/
│
├── backend/                # Backend code (Node.js/Express.js)
├── frontend/               # Frontend (React/Angular/Vue)
├── ai-projects/            # AI/ML Projects (Python/Flask)
│   ├── image-to-text/
│   ├── sentiment-analysis/
│   └── ...
├── README.md               # Project documentation
```

---

## **Future Improvements**
- Integrate small projects into larger applications.
- Extend AI projects with advanced ML models.
- Enhance real-time systems with improved scaling.

---

## **Contributors**
- Alekha Kumar Swain

---

## **License**
This repository is licensed under the MIT License. See `LICENSE` for details.

--- 

This template provides detailed documentation for each project with instructions on setup and execution. Let me know if you'd like to tweak any section or add more!
