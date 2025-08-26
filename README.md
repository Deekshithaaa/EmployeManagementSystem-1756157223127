
# Employee Management System

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=200&section=header&text=Employee%20Management%20System&fontSize=45&fontColor=fff&animation=fadeIn&fontAlign=50&desc=Spring%20Boot%20+%20React%20+%20MySQL&descSize=18&descAlign=50&descAlignY=75" />

[![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](#)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](#)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](#)
[![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#)

</div>

---

## 📌 **Overview**
The **Employee Management System** is a **full-stack application** built using **Spring Boot, React, and MySQL** that allows businesses to manage their employees efficiently.  

This project demonstrates **CRUD operations**, **RESTful APIs**, **responsive React UI**, and **secure database integration**, making it a strong example of enterprise-grade development.

---

## ✨ **Features**

- **Employee Management:** Add, view, update, and delete employees  
- **REST API:** Built with Spring Boot and Spring Data JPA  
- **Frontend:** Responsive UI using React.js  
- **Database:** MySQL with Hibernate ORM  
- **Security & Validation:** Form validation and structured backend error handling  
- **Scalable Architecture:** Can be containerized using Docker  

---

## 🛠 **Tech Stack**

### **Backend**
- Java 17, Spring Boot, Spring Data JPA
- RESTful APIs
- Maven for build automation

### **Frontend**
- React.js with Hooks
- Axios for API calls
- CSS Modules for styling

### **Database & Deployment**
- MySQL
- Docker (Optional)
- Deployed on AWS (Optional)

---

## 🚀 **Getting Started**

### **1. Clone the Repository**
```bash
git clone https://github.com/Deekshithaaa/EmployeManagementSystem-1756157223127.git
cd EmployeManagementSystem-1756157223127
```

### **2. Setup Backend (Spring Boot)**
1. **Create MySQL Database**
   ```sql
   CREATE DATABASE ems CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
   ```
2. **Configure application.properties**
   ```
   spring.datasource.url=jdbc:mysql://localhost:3306/ems
   spring.datasource.username=YOUR_DB_USER
   spring.datasource.password=YOUR_DB_PASSWORD
   spring.jpa.hibernate.ddl-auto=update
   ```
3. **Run Backend**
   ```bash
   ./mvnw spring-boot:run
   ```
   Server runs on: **http://localhost:8080**

### **3. Setup Frontend (React)**
```bash
cd cms
npm install
npm start
```
Frontend runs on: **http://localhost:3000**

---

## 📚 **API Endpoints**

| Method | Endpoint            | Description           |
|---------|--------------------|-----------------------|
| GET     | /api/employees     | Get all employees     |
| GET     | /api/employees/{id}| Get employee by ID    |
| POST    | /api/employees     | Add new employee      |
| PUT     | /api/employees/{id}| Update employee       |
| DELETE  | /api/employees/{id}| Delete employee       |

---

## 📸 **Screenshots**

<div align="center">
<img src="https://user-images.githubusercontent.com/00000000/demo-dashboard.png" width="700" alt="Dashboard Preview"/>
<img src="https://user-images.githubusercontent.com/00000000/demo-form.png" width="700" alt="Form Preview"/>
</div>

---

## 👩‍💻 **About the Developer**

### **Deekshitha Obulreddygari** – *Java Full Stack Developer*
- **Email:** [obulreddygarideekshitha@gmail.com](mailto:obulreddygarideekshitha@gmail.com)  
- **LinkedIn:** [linkedin.com/in/deekshitha-obulreddygari](https://linkedin.com/in/deekshitha-obulreddygari)  
- **Phone:** +1 (623) 688-1409  
- **Location:** Phoenix, AZ  

> *"Passionate about building scalable, high-performance applications that make a real impact."*

---

## ⭐ **Contributions & Feedback**
Contributions, issues, and feature requests are welcome!  
Feel free to **fork this repo** and submit a **PR**.

If you find this project helpful, **please give it a star ⭐**!

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=100&section=footer"/>
</div>
