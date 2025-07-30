

# AuricPOS – GoldPOS

AuricPOS is a Point of Sale (POS) system designed for gold/jewelry businesses, enabling smooth inventory tracking, billing, and customer management.

---

## **Project Objective**

The main goal of **AuricPOS – GoldPOS** is to provide gold and jewelry businesses with a streamlined POS system that:

- Manages gold inventory and transactions effectively.
- Simplifies billing and customer records.
- Provides a responsive and user-friendly interface for retail operations.
- Uses modern technologies for scalability and performance.

---

## **Technologies Used**

- ![React.js](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61dafb)  
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)  
- ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)  
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)  
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  

---

## **How to Run the Project**

### **1. Clone the Repository**

```bash
git clone https://github.com/emanfaisal333/AuricPOS-GoldPOS.git
```
2. Navigate to the Project Directory
```bash
cd AuricPOS-GoldPOS
```
3. Set up the Backend
```bash

cd backend
npm install
npm start
```
This starts the backend server.

4. Set up the Frontend
Open a new terminal and run:

```bash
cd frontend
npm install
npm start
```
This runs the frontend on your local development server (usually http://localhost:3000).

5. Configure the Database
Make sure MongoDB is installed and running locally, or use a cloud MongoDB service (like MongoDB Atlas).

Set your database connection string in a .env file inside the backend folder:

env
```bash
MONGO_URI=your-mongodb-connection-string
PORT=5000
```
