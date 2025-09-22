# URL Shortener App

A full-stack **URL Shortener Application** built with **Spring Boot + H2 + Spring Security** on the backend and **React.js** on the frontend.  
This app allows users to register/login, shorten long URLs, and retrieve the original links securely.

---

## 🚀 Features
- User authentication & authorization with **Spring Security**  
- Shorten long URLs into unique short links  
- Retrieve and redirect to original URLs  
- In-memory database using **H2** (easily replaceable with MySQL/PostgreSQL)  
- REST API powered by **Spring Boot**  
- Interactive **React.js frontend**  
- Secure endpoints (only logged-in users can shorten/manage URLs)  

---

## 📂 Project Structure
URL-Shortener/
│-- README.md
│-- url_shortner_backend_final/ # Spring Boot Backend
│ ├── src/main/java/... # Backend Java source code
│ ├── src/main/resources/ # application.properties + schema
│ └── pom.xml
│
│-- url_shortner_app/ # React.js Frontend
│ ├── src/ # React components
│ ├── public/
│ └── package.json


---

## 🛠️ Technologies Used
- **Backend:** Java, Spring Boot, Spring Security, H2 Database  
- **Frontend:** React.js, Axios, Bootstrap/Tailwind (if used)  
- **Build Tools:** Maven (backend), npm/yarn (frontend)  

---

## ⚡ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/url-shortener-app.git
cd url-shortener-app
