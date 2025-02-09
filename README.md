# Login System Frontend

## 📌 Overview
This is the **frontend** for a user authentication system built using **React.js**. It provides a simple and responsive UI for user registration, login, and profile management. The frontend interacts with the backend to authenticate users using **JWT (JSON Web Tokens)**.

## 🚀 Features
- User Registration & Login
- JWT-based Authentication
- Responsive UI
- API Integration with Backend

## 🛠️ Tech Stack
- **Frontend:** React.js, CSS
- **State Management:** useState, useContext
- **Routing:** React Router

## 📂 Folder Structure
```
Login-system-frontend/
│-- src/
│   ├── components/  # Reusable UI components
│   ├── pages/       # Page components (Login, Register, Profile)
│   ├── context/     # Authentication context
│   ├── services/    # API calls
│   ├── App.js       # Main App component
│-- public/
│-- .env            # Environment variables
│-- package.json    # Project dependencies
│-- README.md       # Project documentation
```

## 🔧 Installation & Setup

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/shivang4857/Login-system-frontend.git
cd Login-system-frontend
```

### **2️⃣ Install Dependencies**
```sh
npm install   # Install required packages
```

### **3️⃣ Configure Environment Variables**
Create a `.env` file in the root directory and add the following:
```
REACT_APP_API_URL=http://localhost:3000
```

### **4️⃣ Run the Frontend**
```sh
npm start
```
The frontend will run on `http://localhost:3000/`

## 🚀 Deployment
### **Deploy on Vercel/Netlify**
- Ensure `REACT_APP_API_URL` is correctly set to the backend URL.

## 🔥 Future Enhancements
- Add validation to forms
- Improve UI/UX with animations
- Implement OAuth (Google, GitHub login)

## 🤝 Contributing
Pull requests are welcome! Open an issue first for major changes.

## 📄 License
This project is **MIT Licensed**.

