# **🔧 Hardware Resource Management Portal**

A full-stack web application built as part of a **Team Project** for the **Advanced Programming & App Development (APAD)** course.  
This portal helps track and manage hardware resource allocation across multiple projects with real-time updates and a clean UI.

---

## **📌 Table of Contents**
- Project Overview  
- Team Details  
- Features  
- Tech Stack  
- Installation & Setup  
- Usage Guide  
- Project Structure  
- Screenshots  
- License  
- Acknowledgments  

---

## **📖 Project Overview**
The Hardware Resource Management Portal allows users to:  
- Register and log into the system  
- Create new projects  
- View project-specific hardware allocations  
- Check in / check out shared hardware (e.g., HW1, HW2)  
- Monitor real-time hardware availability across the system  

🔁 All interactions are handled via a **Flask REST API** and **MongoDB**, ensuring inventory consistency and data integrity.  

---

## **👩‍💻 Team Details**
- **Team Name:** SheCodes-Hub  
- **Team Members:** Sana, Aditi, Apurva, Abhirami, Samiksha, Manasi, Krutika  
- **Program:** MSITM ’26  
- **Institution:** McCombs School of Business, UT Austin  

---

## **🚀 Features**
- 🔐 User Authentication (Sign up / Login)  
- 📁 Project Management (Create, View)  
- 📦 Real-time inventory tracking  
- 🔁 Check-in / Check-out hardware interactions  
- ✅ Form validation and toast-based feedback  
- ⚙️ Clean, reusable React components with stateful interactions  

---

## **🧰 Tech Stack**
**💻 Frontend**  
- React.js  
- React Router  
- React-Bootstrap  
- React-Toastify  

**🔙 Backend**  
- Flask (Python)  
- RESTful API architecture  

**🗄️ Database**  
- MongoDB  
- Collections include: Users, Projects, Inventory  

---

## **⚙️ Installation & Setup**

**📁 Clone the Repository**  
```bash
git clone https://github.com/SanaIrshadTech/shecodes.git
cd shecodes
```
**🖥️ Frontend Setup**  
- 📄 Please refer to `frontend/README.md` for detailed steps.

**🐍 Backend Setup**  
- 📄 Please refer to `backend/README.md` for complete setup instructions, including environment variables and dependencies.

➡️ Make sure you have a local MongoDB instance running, or update the db.py file with your cloud MongoDB URI.

## **🧑‍💼 Usage Guide**

- **📝 Register**
  - Navigate to the `/signup` page
  - Enter a username and password to register

- **🔐 Login**
  - Go to the `/login` page
  - Authenticate using your credentials

- **🏗️ Create Project**
  - Access the `/project` page
  - Enter project ID, name, and description

- **⚙️ Manage Resources**
  - Navigate to the `/resource` page
  - Input a project ID to view hardware status
  - Check out or return hardware
  - Real-time feedback is provided via toast notifications

---

## **🗂️ Project Structure**
````
shecodes/
├── frontend/                  # React frontend
│   ├── components/            # Major features & reusable UI components
│   ├── utils/                 # Toast & API helpers
│   └── index.js               # React app entry point
│
├── backend/                   # Flask backend
│   ├── controllers/           # API route handlers
│   ├── models/                # MongoDB interaction logic
│   ├── db.py                  # DB connection logic
│   └── app.py                 # Flask app entry point
````

## **🖼️ Screenshots**
(Will add screenshots of the Login page, Project creation, and Hardware check-in/check-out views here.
Optionally, add a short demo video of the app in action.)

## **📜 License**
This project was created for educational use as part of the APAD course at UT Austin. All rights reserved © SheCodes-Hub Team, 2025.

## **🙌 Acknowledgments**
- Professor Abhay Samant — Advanced Programming & App Development (APAD)
- McCombs School of Business (MSITM Program) – UT Austin

