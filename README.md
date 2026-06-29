# ☁️ Secure Cloud Log Analyzer with MapReduce

A cloud-based web application that efficiently analyzes large log files using a parallel **MapReduce** engine. The system processes uploaded log files, identifies HTTP error frequencies and peak traffic hours, and provides secure access to analytics through authentication and role-based access control.

---

## 📌 Project Overview

Traditional log analysis becomes slow when dealing with large datasets. This project implements a MapReduce-based parallel processing approach to divide log files into smaller chunks, process them concurrently, and combine the results to generate meaningful insights.

The application is deployed on **Railway**, uses **Neon DB** for cloud database storage, and follows secure cloud computing practices by storing sensitive credentials in environment variables.

---

## ✨ Key Features

- 📂 Upload large log files
- ⚡ Parallel log processing using MapReduce
- 📊 HTTP Error Analysis (404, 403, 500, etc.)
- ⏰ Peak Traffic Hour Detection
- 🔐 User Authentication & Role-Based Access Control
- ☁️ Cloud Database Integration (Neon DB)
- 🚀 Live Deployment on Railway
- 📈 Interactive Dashboard with Charts

---

## 🛠️ Technologies Used

- Python
- Flask
- SQLAlchemy
- Flask-Login
- Hadoop MapReduce (Simulation)
- Multiprocessing
- PostgreSQL (Neon DB)
- HTML
- Tailwind CSS
- Chart.js
- Git & GitHub
- Railway

---

## ⚙️ System Workflow

1. User uploads a log file.
2. The log file is divided into multiple chunks.
3. Each chunk is processed in parallel.
4. HTTP status codes and request hours are extracted.
5. MapReduce combines the results.
6. Final analytics are displayed on the dashboard.

---

## 🔒 Security Features

- Password Hashing
- Secure User Authentication
- Role-Based Access Control
- Session Management
- Environment Variables for Secrets Management

---

## 📊 Analysis Results

The application generates:

- HTTP Error Frequency
- Peak Traffic Hours
- Log Summary Reports
- Interactive Charts

---

## ☁️ Cloud Services

- **Hosting:** Railway
- **Database:** Neon PostgreSQL
- **Version Control:** GitHub

---

## 📂 Project Structure

```text
Secure-Cloud-Log-Analyzer/
│── app.py
│── templates/
│── static/
│── models.py
│── requirements.txt
│── runtime.txt
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Configure environment variables.
4. Run the Flask application.

```bash
python app.py
```

5. Open the application in your browser.

---

## 🎓 Academic Information

**Course:** Cloud Computing

**Project:** Secure Cloud Log Analyzer with MapReduce

---

## 👩‍💻 Author

**Ayesha Ramzan**

BS Computer Science
