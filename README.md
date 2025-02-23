# ChatGram

ChatGram is a real-time messaging web application built using React, Node.js, Express, and MongoDB. It allows users to send messages, create chat rooms, and experience seamless real-time communication.

## 🚀 Features
- 🔐 **User Authentication** – Secure login/signup using JWT authentication.
- 💬 **Real-time Messaging** – Send and receive messages instantly using WebSockets.
- 📂 **Media Sharing** – Share images, videos, and documents.
- 👥 **Group Chats** – Create chat rooms for group conversations.
- 🌓 **Dark Mode Support** – Switch between light and dark themes.
- 📱 **Responsive UI** – Fully optimized for desktop and mobile.

## 🛠️ Tech Stack
- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose ORM
- **Real-time Communication:** Socket.IO
- **Authentication:** JWT (JSON Web Tokens), bcrypt for password hashing

## 📂 Project Structure
```
ChatGram/
│── backend/           # Node.js + Express Backend
│── frontend/          # React.js Frontend
│── public/            # Static assets
│── .gitignore         # Ignored files
│── package.json       # Project dependencies
│── README.md          # Project documentation
```

## ⚡ Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/iamprish121/Chat-Application-ChatGram.git
cd Chat-Application-ChatGram
```

### 2️⃣ Install Dependencies
#### Backend Setup
```sh
cd backend
npm install
```
#### Frontend Setup
```sh
cd ../frontend
npm install
```

### 3️⃣ Configure Environment Variables
Create a **.env** file in the **backend/** folder and add:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Application
#### Start Backend Server
```sh
cd backend
npm start
```
#### Start Frontend Server
```sh
cd ../frontend
npm start
```

### 5️⃣ Open in Browser
Visit **http://localhost:3000** to access ChatGram.

## 🔧 Workflow
1. **User registers/logs in** → Data stored securely in MongoDB.
2. **WebSockets (Socket.IO) handle real-time messaging**.
3. **Messages get stored in the database and displayed instantly**.
4. **Users can create/join chat rooms for group conversations**.
5. **Responsive UI ensures smooth user experience on all devices**.

## 📜 Contribution Guidelines
Want to improve ChatGram? Follow these steps:
1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b feature-branch`).
3. **Make your changes and commit** (`git commit -m "Added new feature"`).
4. **Push to GitHub** (`git push origin feature-branch`).
5. **Open a pull request**.

## 🌟 Show Some Love
If you like this project, don't forget to ⭐ star the repository!

## 📞 Contact
- **GitHub:** [iamprish121](https://github.com/iamprish121)
- **Email:** Priyanshua038@gmail.com
