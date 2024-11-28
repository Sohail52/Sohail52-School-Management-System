# SCHOOL MANAGEMENT SYSTEM

## About

The School Management System is a web-based application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It aims to streamline school management, class organization, and facilitate communication between students, teachers, and administrators.

## Features

- **User Roles:** The system supports three user roles: Admin, Teacher, and Student. Each role has specific functionalities and access levels.

- **Admin Dashboard:** Administrators can add new students and teachers, create classes and subjects, manage user accounts, and oversee system settings.

- **Attendance Tracking:** Teachers can easily take attendance for their classes, mark students as present or absent, and generate attendance reports.

- **Performance Assessment:** Teachers can assess students' performance by providing marks and feedback. Students can view their marks and track their progress over time.

- **Data Visualization:** Students can visualize their performance data through interactive charts and tables, helping them understand their academic performance at a glance.

- **Communication:** Users can communicate effortlessly through the system. Teachers can send messages to students and vice versa, promoting effective communication and collaboration.

## Technologies Used

- **Frontend:** React.js, Material UI, Redux
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Installation

```sh
1. **Clone the Repository:**

git clone https://github.com/Sohail52/MERN-School-Management-System.git


2. **Backend Setup:**

- Navigate to the `backend` folder:

cd backend


- Install the required dependencies:

npm install


- Start the backend server:

npm start


- Create a `.env` file in the backend folder and add the following line to connect to your MongoDB database:

MONGO_URL=mongodb://127.0.0.1/school


If you are using **MongoDB Compass**, you can use this database link, or if you are using **MongoDB Atlas**, replace this with your own database connection string.


3. **Frontend Setup:**

- Navigate to the `frontend` folder:

cd frontend


- Install the required dependencies:

npm install


- Start the frontend server:

npm start


The frontend will run on `localhost:3000`, and the backend API will run on `localhost:5000`.
