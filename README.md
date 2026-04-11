# ☁️ Cloud Fun Facts Generator

A serverless web application that generates random cloud computing facts using AWS services.  
The project demonstrates end-to-end frontend–backend integration with proper CORS handling.

---

## 🚀 Live Demo
👉 https://main.d3vdksth6q358t.amplifyapp.com/

---

## 🛠️ Tech Stack

- **AWS Lambda** – Backend logic (Python)
- **Amazon DynamoDB** – Stores cloud facts
- **AWS Amplify** – Frontend hosting & CI/CD
- **Lambda Function URL** – Backend access
- **HTML, CSS, JavaScript** – Frontend
- **GitHub** – Version control

---

## 📌 Architecture Overview

Frontend (AWS Amplify)
|
v
Lambda Function URL
|
v
Amazon DynamoDB
---


---

## ⚙️ How It Works

1. User clicks **Generate Fun Fact** on the frontend.
2. Frontend sends a request to **Lambda Function URL**.
3. Lambda scans the **DynamoDB table**.
4. A random cloud fact is selected.
5. The fact is returned as a JSON response.
6. Frontend displays the fact dynamically.

---

## 🧠 Key Learnings

- Built a **serverless backend** using AWS Lambda and DynamoDB
- Understood **NoSQL data modeling** (items vs attributes)
- Implemented **CORS for Lambda Function URLs**
- Deployed frontend with **AWS Amplify (Git-based CI/CD)**
- Debugged real-world issues involving CORS and API integration
- Learned the difference between **API Gateway vs Lambda Function URLs**

---

## 🔐 CORS Configuration

CORS was configured directly in **Lambda Function URL settings** to allow requests from the Amplify-hosted frontend domain.

---

## 🧪 Testing

- Backend tested directly via Lambda test events
- Lambda Function URL tested in browser
- Frontend tested after Amplify deployment

---

## 👩‍💻 Author

**Dhanshri Edake**  
Final-year IT Engineering Student  
Interested in Cloud Computing & Serverless Architecture

---

## 📄 License

This project is for learning and demonstration purposes.






