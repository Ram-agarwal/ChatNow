ChatNow - Real-Time Chat Application

Overview
 
   ChatNow is a full-stack real-time chat application built using modern web technologies. It enables users to communicate instantly with a secure and scalable system.

Features:

  - Real-time messaging using Socket.io
  - Secure authentication with JWT
  - User profile management
  - Online/offline user status
  - Responsive UI with modern design
  - Scalable backend architecture

 Tech Stack:

 Frontend:
   - React.js
   - CSS
   - Zustand

 Backend:
   - Node.js
   - Express.js
   - Socket.io

 Database:
   - MongoDB

 DevOps & Tools
   - Docker
   - Nginx
   - Kubernetes
   - CI/CD Using Github-Action
 

 Project Architecture
   - Frontend communicates with backend using REST APIs and WebSockets
   - Backend handles authentication, messaging, and business logic
   - MongoDB stores users and chat data
   - Socket.io enables real-time communication

  




Setup Instructions:
  - git clone <your-repo-link>
  - cd ChatNow

Setup Environment Variables
 
 - - - Create .env file in backend:

  - MONGODB_URI=mongodb://mongoadmin:secret@mongodb:27017/dbname?authSource=admin
  - JWT_SECRET=your_jwt_secret_key
  - PORT=5001

Note: 
  - Replace `your_jwt_secret_key` with a strong secret key of your choice.

Run with Docker:
  - docker-compose up -d --build

Access app:
  - http://localhost

API Endpoint:
  - http://localhost:5001


Future Improvements:
 - CI/CD pipeline integration
 - Kubernetes deployment
 - Group chat feature
 - Media sharing
