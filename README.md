# SB Works - Freelancing Platform (MERN Stack)

SB Works is a modern freelancing platform designed to connect clients with skilled freelancers. It offers an intuitive UI for project posting, bidding, real-time chat, and smooth collaboration with role-based access for clients, freelancers, and admins.

## 🌐 Live Demo

🎥 [Watch Demo Video](https://drive.google.com/file/d/1erdcudF8D00QyHEf0aMKioTAqWa2AjDb/view?usp=sharing)

## 📁 Project Repository

📦 [Source Code (Drive Link)](https://drive.google.com/drive/folders/10mSn2lMTaVMDWWFNjeJjiOLfmcD3-87C?usp=sharing)

---

## ✨ Features

- Project posting and bidding system
- Freelancer profiles and portfolios
- Real-time communication via chat
- Admin dashboard for user/project moderation
- Secure authentication and role management
- Notifications and project updates

---

## 💻 Tech Stack

**Frontend**
- React.js
- Axios
- Bootstrap / Material UI

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- Bcrypt, CORS

---

## 📐 Architecture

SB Works follows a client-server model:
- **Frontend (React.js):** Handles user interface, project browsing, bidding, and chat.
- **Backend (Express.js):** Handles API routing, user authentication, project management, chat, and admin logic.
- **Database (MongoDB):** Stores users, projects, applications, and messages.

---

## 📊 ER Diagram & Flow

- Clients → Post projects → Browse freelancers
- Freelancers → Submit proposals → Chat & collaborate
- Admin → Moderates users/projects → Resolves disputes

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Node.js and npm – [Download](https://nodejs.org/)
- MongoDB – [Download](https://www.mongodb.com/try/download/community)
- Git – [Download](https://git-scm.com/downloads)
- VS Code – [Download](https://code.visualstudio.com/download)

---

### ⚙️ Installation Steps

```bash
# Clone the repository or download from Drive
cd freelancer-app-MERN

# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

# Start the development server
npm start
