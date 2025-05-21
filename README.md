# Chatty - Fullstack Real-Time Chat Application


A modern real-time chat application built with React, Node.js, Express, MongoDB, and Socket.io. This project provides a complete messaging solution with features like real-time messaging, online status indicators, user authentication, profile customization, and theme selection.

## Features

- **Real-time messaging** using Socket.io
- **User authentication** with JWT (JSON Web Tokens)
- **Online/offline status indicators**
- **Image sharing** with Cloudinary integration
- **Profile customization** with avatar uploads
- **Theme selection** with 30+ themes from DaisyUI
- **Responsive design** that works on desktop and mobile
- **Secure communication** with protected routes

## Tech Stack

### Frontend
- **React** - UI library
- **Vite** - Build tool
- **React Router** - Routing
- **Zustand** - State management
- **Tailwind CSS** - Styling
- **DaisyUI** - Component library
- **Axios** - HTTP client
- **Socket.io-client** - WebSocket client
- **React Hot Toast** - Notifications

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM
- **Socket.io** - WebSocket server
- **JWT** - Authentication
- **Bcrypt** - Password hashing
- **Cloudinary** - Image storage

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB database
- Cloudinary account

### Environment Setup

1. Create a `.env` file in the `backend` directory:

```
PORT=5001
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### Installation

1. Clone the repository
```bash
git clone https://github.com/daivya4/fullstack-chat-app.git
cd fullstack-chat-app
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Install frontend dependencies
```bash
cd ../frontend
npm install
```

### Running the Application

#### Development Mode
1. Start the backend server
```bash
# In the backend directory
npm run dev
```

2. Start the frontend development server
```bash
# In the frontend directory
npm run dev
```
- Backend will run on http://localhost:5001
- Frontend will run on http://localhost:5173

#### Production Mode
```bash
# In the root directory
npm run build
npm start
```

### Database Seeding

To seed the database with sample users:
```bash
# In the backend directory
node src/seeds/user.seed.js
```

## Usage

1. Register a new account or log in with existing credentials
2. Select a user from the sidebar to start chatting
3. Send text messages or images
4. Customize your profile picture
5. Choose from different themes in the settings page

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.