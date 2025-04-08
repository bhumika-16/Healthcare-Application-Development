# 🏥 Health Information System (HIS) with Doctor App

A comprehensive full-stack healthcare platform designed to streamline hospital workflows with role-specific modules for **Doctors, Nurses, Receptionists, Pharmacists**, and **Admins**. Built using **React Native (Expo Go)**, **Spring Boot (Java)**, and **MySQL**, with a focus on **security, usability**, and **scalability**.

---

## 🚀 Features

### 🔐 Security
- **JWT Authentication** with Spring Security
- **AES Encryption** for sensitive data
- **OTP Verification** for secure logins and password reset
- **Consent Tokenization** to ensure patient data privacy
- **Session/IP Tracking** and auto logout for dual/inactive sessions
- **Automated Data Retention and Deletion** policies for compliance

### 👩‍⚕️ Role-based Modules
- **Admin**: Manage users (Doctors, Nurses, Receptionists, Pharmacy), access control, view stats
- **Doctor**: Diagnose, treat, prescribe, review history, monitor patient progress, and discharge
- **Nurse**: Record vitals, symptoms, history, test results, and manage patient data with consent
- **Receptionist**: Register/manage patients, book appointments, manage patient consents
- **Pharmacy**: Dispense medicines, track medications, serve canvas-based prescriptions

---

## 🔧 Tech Stack

| Layer             | Technologies Used                                         |
|------------------|-----------------------------------------------------------|
| **Frontend**      | React Native, Figma UI, Expo Go                          |
| **Backend**       | Spring Boot (Java), RESTful APIs                         |
| **Database**      | MySQL                                                    |
| **Security**      | Spring Security, JWT, AES Encryption, OTP Verification  |
| **DevOps**        | GitHub, Postman, Swagger (for API testing)               |
| **Cloud Ready**   | Modular design for easy deployment to AWS, GCP, or Azure|

---

## 📁 Code Repositories

- 🔗 **Frontend GitHub**: [github.com/Team30HAD/Frontend](https://github.com/Team30HAD/HISFrontend.git)
- 🔗 **Backend GitHub**: [github.com/Team30HAD/Backend](https://github.com/Team30HAD/HISBackend.git)
- 📹 **Demo Recording**: [Click here to view demo](https://drive.google.com/drive/folders/1aN6RcrAnKwic-P8HabNnfoDtTA1CUnYU?usp=drive_link)

---

## 🎨 UI/UX Prototypes (Figma Links)

| Module        | Design Link                                                                 | Prototype Link                                                                 |
|---------------|------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| Admin         | [Admin Design](https://www.figma.com/file/Ffgl3ydMpUbkqf9IWlhuFl/Admin-Module) | [Admin Prototype](https://www.figma.com/proto/Ffgl3ydMpUbkqf9IWlhuFl/Admin-Module?node-id=17-46) |
| Doctor (IP)   | [IP Design](https://www.figma.com/file/xACBHHZgVHV3E1S5hEt3V7/IP-Doctor)       | [IP Prototype](https://www.figma.com/proto/xACBHHZgVHV3E1S5hEt3V7/IP-Doctor?node-id=1-274)       |
| Doctor (OP)   | [OP Design](https://www.figma.com/file/w2zMVUSJRwWVEwoEAOuNhe/OP-Doctor)       | [OP Prototype](https://www.figma.com/proto/w2zMVUSJRwWVEwoEAOuNhe/OP-Doctor?node-id=128-194)     |
| Nurse         | [Nurse Design](https://www.figma.com/file/NekyNlZaaTeTWvX08pMFEr/Nurse-Module) | [Nurse Prototype](https://www.figma.com/proto/NekyNlZaaTeTWvX08pMFEr/Nurse-Module?node-id=30-2)  |
| Receptionist  | [Receptionist Design](https://www.figma.com/file/WZ8QUxu9wqstokztKOIhqI/Receptionist) | [Receptionist Prototype](https://www.figma.com/proto/WZ8QUxu9wqstokztKOIhqI/Receptionist?node-id=11-2) |
| Pharmacy      | [Pharmacy Design](https://www.figma.com/file/S7W13ICs8fTNjAPl278NQK/Pharmacy) | [Pharmacy Prototype](https://www.figma.com/proto/S7W13ICs8fTNjAPl278NQK/Pharmacy?node-id=33-8)   |

---

## 🧠 Highlights

- 🔍 500+ RESTful APIs across modules
- 📄 API Documentation using Swagger
- ✅ Unit Testing and Role-Based Authentication
- 🎯 OTP-based consent workflow and security tokenization
- 🧠 Integrated real-world healthcare flows (Canvas-based prescription, QR-based beds)

---

## 📌 Future Scope

- Integration with **FHIR standards** and external hospital management systems
- Deployment using **Docker** & **Kubernetes** on AWS or GCP
- Incorporating real-time wearable health data
- Expand to web and desktop platforms

---

## 👤 Authors

- Bhumika Jindal  
- Abhipsa Panda  
- Kakunuri Himarishitha Reddy  
- Charvy Koshta  
- Deepanjali Ghosh  

---

Let me know if you want this exported as a `README.md` file or auto-deployed to a GitHub repo!
