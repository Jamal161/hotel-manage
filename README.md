# Project

This is a full-stack project built using Node.js, React, and MongoDB. The system allows users to register, log in, and create posts. The live demo only provides a frontend view and does not connect to a database, so data persistence is not available.

## Live Demo
[ Demo](https://hotel-manage-liart.vercel.app/)

## Technologies Used
- Node.js (Backend API)
- React.js (Frontend)
- MongoDB (Database)

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/hotel-management.git
cd hotel-management
```

### 2. Install Dependencies
For both the API and client:
```sh
cd api
npm install

cd ../client
npm install
```

### 3. Create a `.env` File
Create a `.env` file in the root of the `api` directory and add the following:
```env
MONGO_URI=your_mongo_database_url
GOOGLE_APP_ID=your_google_app_id
GOOGLE_SECRET=your_google_secret_key
JWT_SECRET=your_jwt_secret
```

### 4. Run the Application
Run the following command in both `api` and `client` directories:
```sh
npm run dev
```

## Features
- User Registration
- User Login
- Create Posts

## API Endpoints
| Method | Endpoint        | Description          |
|--------|----------------|----------------------|
| POST   | /api/users     | Register a new user |
| POST   | /api/login     | User login          |
| POST   | /api/posts     | Create a post       |




