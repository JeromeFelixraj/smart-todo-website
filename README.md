 Smart To-Do Website

A modern full-stack To-Do web app with user authentication, persistent storage, and an admin dashboard — built for productivity and simplicity.

🚀 Features

✅ User Authentication

Secure Login & Signup using hashed passwords

Persistent session management

✅ To-Do Management

Add, edit, and delete tasks easily

Mark tasks as completed or pending

Auto-update UI with no page reload

✅ Admin Dashboard

Separate admin login portal

Manage all users and their to-dos

✅ Database Integration

To-dos are stored in a database, so they stay saved even after logout or refresh

✅ Responsive Design

Fully mobile-friendly

Built with Tailwind CSS for speed and consistency

🧩 Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript, Tailwind CSS
Backend	Node.js, Express.js
Database	MongoDB (Mongoose ORM)
Hosting	Render
Version Control	Git + GitHub
🌐 Live Demo

🔗 User App: https://smart-todo-website-2.onrender.com

🔗 Admin Panel: https://smart-todo-website-1.onrender.com

📂 Folder Structure
<img width="702" height="590" alt="image" src="https://github.com/user-attachments/assets/2dbfb08b-4853-420e-9676-3d9b63aef3cb" />


⚙️ Installation & Setup

Clone the repository

git clone https://github.com/<your-username>/web-smart-todo.git
cd web-smart-todo


Install dependencies

npm install


Create a .env file in the root directory and add your variables:

MONGO_URI=your_mongodb_connection_string
PORT=5000
SESSION_SECRET=your_secret_key


Run the development server

npm start


Then open http://localhost:5000
 in your browser 🎉

🧠 How It Works

User signs up or logs in

Tasks are stored in MongoDB, linked to their account

Admin can view/manage all users from the admin panel

Tasks persist even after logout or refresh

Hosted seamlessly on Render for live use

🖌️ UI Highlights

Clean minimal interface

Responsive Tailwind CSS layout

Dynamic JavaScript-driven task handling

📸 Screenshots (Optional)

(You can add screenshots from your website here)
Example:

![Homepage Screenshot](assets/screenshot-home.png)
![Admin Dashboard](assets/screenshot-admin.png)

🧑‍💻 Contributors
Name	Role
Jerome Felix	Full Stack Developer
warbug	Co-Developer / Tester
💡 Future Improvements

Dark Mode toggle

Task categories / priorities

Email notifications for deadlines

Progressive Web App (PWA) support

🛡️ License

This project is licensed under the MIT License — you’re free to use, modify, and distribute with attribution.

⭐ Show Your Support

If you like this project, give it a star ⭐ on GitHub — it helps a lot!
Feel free to fork and build upon it 💥
