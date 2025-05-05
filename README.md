Concisea (Bitly Clone) 🔗
A URL Shortening Web Application built using Java (Spring Boot), React, and PostgreSQL.

📌 About the Project
Concisea is a Bitly-inspired web-based URL shortening platform that enables users to generate short, manageable links from long URLs. It provides essential features such as:

Short URL generation

User authentication using JWT

Click analytics and tracking

Responsive frontend built with React and Tailwind CSS

PostgreSQL database for robust URL and user data management

This project was developed as part of a B.Tech. final year thesis at C.V. Raman Global University, Odisha.

🛠️ Tech Stack
Layer	Technology
Frontend	React, Tailwind CSS
Backend	Java, Spring Boot
Auth	JWT Authentication
Database	PostgreSQL
Tools	IntelliJ IDEA (Backend), VS Code (Frontend)

🚀 Features
🔐 Secure User Authentication (JWT)

🔗 Short URL Creation

📊 Click Tracking & Analytics

📋 User Dashboard

📱 Responsive UI

⚙️ Project Setup
Backend (Spring Boot)
Navigate to server/ directory.

Add PostgreSQL credentials in application.properties.

Run the application via IntelliJ or command line:

bash
Copy
Edit
mvn spring-boot:run
Frontend (React)
Navigate to client/ directory.

Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm start
🗃️ Database Schema
Users Table: Stores user credentials and roles.

URL Mapping Table: Stores original & short URLs, click count, user association.

Click Event Table: Tracks individual clicks with timestamp.

📈 Future Enhancements
🌍 Online Deployment (Render, Vercel, etc.)

🎯 Custom Short URLs

🌐 Location, browser, and device analytics

📷 Screenshots
See the /screenshots folder (add screenshots here) or visit the Outputs and Results section in the project report.

![image](https://github.com/user-attachments/assets/3c7be402-7ace-4a8f-92b3-10b0f33cc3fb)

![image](https://github.com/user-attachments/assets/9e22799a-c6a5-4055-acf8-56cfd515dcb8)


![image](https://github.com/user-attachments/assets/8885b87b-ef59-4a5f-ae76-a47d48269c5e)

![image](https://github.com/user-attachments/assets/0ecf7acd-6e62-4dd3-b2c4-1c2090315826)
![image](https://github.com/user-attachments/assets/cce6d496-aace-44a0-9cc5-d801136b1490)
![image](https://github.com/user-attachments/assets/8d9fdab7-80d1-447c-a3ad-4169fbf0d484)


📚 References
Spring Boot Documentation

PostgreSQL Docs

React & Tailwind CSS Docs

Bitly API Concepts

