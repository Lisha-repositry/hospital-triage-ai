# 🏥 Hospital Appointment System with Rule-Based Triage & Authentication

## 📌 Project Overview
This project is a web-based hospital appointment system that simulates patient triage, doctor assignment, and secure authentication flow. Patients can enter symptoms through a web interface, and the system assigns departments and urgency levels using rule-based logic. Authentication is handled using Auth0 for secure session management.

---

## 🎯 Problem Statement
Patients often face delays in identifying the correct department, booking appointments, and managing records securely, leading to inefficiency and delayed treatment in healthcare systems.

---

## 💡 Solution
This system automates basic hospital workflow by:
- Assigning departments based on symptoms
- Classifying urgency levels
- Managing secure authentication using Auth0
- Storing structured patient records

---

## ⚙️ Features

### 🧠 Rule-Based Triage System
- Accepts patient symptoms via web form
- Applies condition-based logic:
  - Chest pain → Cardiology (High urgency)
  - Fever/Cough → Internal Medicine
  - General symptoms → General Physician

### 🔐 Authentication System
- Integrated Auth0 authentication
- OAuth-based login flow
- Token generation for secure session handling

### 🖥️ Web Application
- Built using Node.js backend
- Simple frontend form interface
- Real-time processing of patient input

### 📊 Data Management
- Patient records stored in JSON format
- Stores symptoms, department, urgency level, and token

---

## 🧰 Tech Stack
- Backend: Node.js  
- Frontend: HTML, CSS  
- Authentication: Auth0 (OAuth 2.0)  
- Data Storage: JSON  
- Logic: Rule-based system  

---

## 🔄 Workflow
1. Patient enters symptoms in web form  
2. Node.js backend processes input (`app.js`)  
3. Rule-based logic assigns department and urgency  
4. Auth0 generates authentication token  
5. Data is stored in JSON file  
6. Result is displayed on webpage  

---

## ⚠️ Limitations
- Rule-based system (no ML model used)  
- Runs on localhost (not deployed)  
- JSON used instead of database  

---

## 🚀 Future Improvements
- Machine learning-based triage system  
- Database integration (MongoDB / SQL)  
- Cloud deployment (AWS / Vercel)  
- Notification system (Email/SMS)  
- Doctor dashboard for live management  

---

## 🎯 Impact
This project demonstrates a basic but functional healthcare workflow system that improves:
- Patient routing efficiency  
- Appointment organization  
- Secure authentication handling  
- Healthcare process automation concepts  

It serves as a prototype for future AI-enabled hospital management systems.
