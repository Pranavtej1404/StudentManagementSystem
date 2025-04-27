

# Student Management System

This is a simple **Student Management System** built using:
- **C++** (Backend with Crow HTTP server)
- **HTML + JavaScript** (Frontend)

It allows you to:
- Add students
- View all students
- Search students by ID

## 🛠 Tech Stack
- C++17
- Crow Web Framework
- HTML5 / JavaScript
- VS Code (Recommended)

---

## 📦 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
```

---

### 2. Install Dependencies

✅ Install Crow:
- Download `crow_all.h` from [Crow GitHub](https://github.com/CrowCpp/Crow) and place it inside the project folder.

✅ Install Boost (optional):
- Using **vcpkg**:

```bash
git clone https://github.com/microsoft/vcpkg.git
cd vcpkg
.\bootstrap-vcpkg.bat
.\vcpkg.exe install boost
```

- Or skip Boost if you are using basic Crow features only.

---

### 3. Build the Backend

Compile the backend:

```bash
g++ backend.cpp -o backend -lpthread
```

Run the server:

```bash
./backend
```

By default, it runs at **http://localhost:18080**.

---

### 4. Run the Frontend

- Open `index.html` in your browser.
- Make sure the backend server is running.
- You can now **add students** and **view the student list**!

---

## 🌟 Features

- Add new students (name, ID, grade)
- View all added students
- Simple API with Crow
- Lightweight frontend (pure HTML + JS)
- Easy to extend (file saving, authentication, etc.)

---

## 📋 API Endpoints

| Endpoint           | Method | Description           |
|--------------------|--------|-----------------------|
| `/add_student`      | POST   | Add a student          |
| `/get_students`     | GET    | Fetch all students     |

---



## ✍️ Author
- **N Pranav Tej**  
- [LinkedIn](#) | [GitHub](#)

---

# 🚀 Future Improvements
- Save students to a file or database
- Add editing and deleting students
- User authentication (login/signup)
- Host backend + frontend online

---

# License
This project is open-source and free to use.

---

---

Would you like me to also **create the folder structure** suggestion like:

```bash
student-management-system/
├── backend.cpp
├── crow_all.h
├── index.html
├── README.md
```

