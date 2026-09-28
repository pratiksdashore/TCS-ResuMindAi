# ResuMindAI ☁️📄

ResuMindAI is a Cloud-Enabled AI-powered resume analysis and ATS optimization platform designed to help candidates improve resumes through intelligent job matching, semantic analysis, ATS scoring, and AI-driven recommendations using scalable cloud architecture and modern NLP technologies.

---

## 🚀 Features

* 📄 Resume Upload & Parsing
* 🤖 AI-Powered Resume Analysis
* 🎯 Intelligent Job Description Matching
* 📊 ATS Compatibility Scoring
* 🧠 Smart Skill Gap Detection
* ✨ AI-Based Resume Suggestions
* 🔍 Keyword Optimization Engine
* 📈 Resume Match Percentage Calculation
* 🌐 Modern Responsive User Interface
* 🔐 Secure Backend APIs
* ☁️ Cloud Deployment Architecture
* ⚡ Fast & Scalable Processing Workflow

---

## ☁️ Cloud-Focused Architecture

The project was deployed on AWS using cloud infrastructure for application hosting, storage, and content delivery.

### AWS Services Used

* **Amazon EC2** → Backend application hosting
* **Amazon S3** → Frontend static hosting and file storage
* **Amazon CloudFront** → Content delivery and optimized frontend access
* **AWS IAM** → Identity and access management
* **AWS VPC** → Secure network infrastructure
* **Amazon CloudWatch** → Monitoring and logging

### AWS Services Planned / Future Enhancements

* **Application Load Balancer (ALB)** → Traffic distribution and application load balancing
* **EC2 Auto Scaling** → Automatic scaling based on application demand
* **Amazon Route 53** → Custom domain and DNS management
* **AWS Certificate Manager (ACM)** → SSL/TLS certificate management
* **Amazon RDS** → Managed relational database
* **AWS Lambda** → Serverless processing and event-driven workloads

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* JavaScript

### Backend

* Python
* Flask / FastAPI
* REST APIs

### AI / NLP

* Gemini API / OpenAI
* Resume Parsing Engine
* Semantic Matching
* NLP-Based Resume Analysis
* ATS Optimization Logic

### Cloud & DevOps

* AWS Cloud Services
* Amazon EC2
* Amazon S3
* Amazon CloudFront
* AWS IAM
* AWS VPC
* Amazon CloudWatch
* Git & GitHub
* CI/CD Workflow

---

## 📂 Project Structure

```bash
TCS-ResuMindAI/
│
├── Backend/                 # Python backend APIs
│
├── Documents and Videos/    # Project reports & demo assets
│
├── frontend/                # React frontend application
│
├── .gitignore               # Git ignored files
│
├── run_backend.ps1          # Backend startup script
│
└── README.md                # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd TCS-ResuMindAI
```

---

### 2️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

### 3️⃣ Backend Setup

```bash
cd Backend

python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Run Backend Server

```bash
python app.py
```

Backend runs on:

```bash
http://localhost:5000
```

---

## 🔥 System Workflow

1. Upload Resume (PDF/DOCX)
2. Paste Job Description
3. AI Engine Performs:

   * Resume Parsing
   * Skill Extraction
   * ATS Keyword Analysis
   * Semantic Matching
   * Missing Skill Detection
4. Generate:

   * ATS Score
   * Resume Match Percentage
   * AI-Based Suggestions
   * Skill Improvement Insights

---

## 🔒 Security Features

* Secure API Architecture
* Protected Backend Endpoints
* Secure File Upload Handling
* Input Validation & Error Handling
* Role-Based Access Control
* AWS IAM-Based Access Control
* AWS VPC Network Isolation
* Cloud Security Best Practices

---

## 🚀 Deployment

The platform was deployed and tested using AWS cloud infrastructure.

### Deployment Architecture

* **Amazon S3** → Hosted the React frontend and static assets
* **Amazon CloudFront** → Distributed frontend content through AWS edge locations
* **Amazon EC2** → Hosted the backend application
* **AWS IAM** → Managed AWS access and permissions
* **AWS VPC** → Provided the underlying network infrastructure
* **Amazon CloudWatch** → Supported monitoring and logging

The AWS deployment resources are currently not running to avoid ongoing infrastructure costs. The application can be redeployed using the project's AWS architecture and configuration.

### Future Cloud Infrastructure

The architecture can be further extended using:

* **Application Load Balancer (ALB)**
* **EC2 Auto Scaling**
* **Amazon Route 53**
* **AWS Certificate Manager (ACM)**
* **Amazon RDS**
* **AWS Lambda**

This would provide a more scalable and production-oriented cloud architecture.

---

## 🚀 Future Enhancements

### ☁️ Cloud & Infrastructure

* Application Load Balancer (ALB)
* EC2 Auto Scaling
* Amazon Route 53 Custom Domain
* AWS Certificate Manager (ACM)
* Amazon RDS Integration
* Serverless Processing with AWS Lambda
* Enhanced CloudWatch Monitoring

### 🤖 AI & Platform

* AI Resume Rewriting
* Multi-Resume Comparison
* Smart Job Recommendation Engine
* LinkedIn Profile Analysis
* AI Interview Question Generator
* PDF Report Export
* Real-Time Career Insights

---

## 🎯 Project Objective

The objective of ResuMindAI is to leverage Artificial Intelligence, NLP, and Cloud Computing technologies to build a scalable and intelligent resume analysis platform capable of improving ATS compatibility, resume quality, and job matching efficiency.

---

## ☁️ Cloud Deployment & 👨‍💻 Infrastructure Management By

**Pratik Dashore**
Cloud & DevOps Engineer

---

## 📜 License

This project is developed as part of a TCS training task, academic learning activity, and cloud & AI skill development practice.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

Repository: https://github.com/pratiksdashore/TCS-ResuMindAi

---
