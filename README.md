[flexbnbapi_readme.md](https://github.com/user-attachments/files/23027379/flexbnbapi_readme.md)
# Flexbnb Backend — Node.js & Express API

Flexbnb Backend provides the robust server-side foundation for the full-stack Airbnb-inspired platform. It handles authentication, data management, real-time communication, and integrates seamlessly with the frontend to deliver a scalable and maintainable API.

## Live Demo
🌐 [Flexbnb Live Demo](https://flexbnb-karin.onrender.com)

## Key Backend Features
- **User Authentication:** Secure login and signup with email/password and OAuth options
- **API Endpoints:** Manage homes, users, bookings, reviews, and wishlist functionality
- **Real-Time Communication:** WebSocket connections for instant notifications and messaging
- **Data Persistence:** MongoDB + Mongoose for robust database modeling
- **Media Management:** Cloudinary integration for image uploads
- **Middleware:** Authentication, request validation, and error handling

## Tech Stack
- **Backend:** Node.js, Express, REST API
- **Database:** MongoDB, Mongoose
- **Real-Time:** Socket.io
- **Media Storage:** Cloudinary
- **Version Control:** Git & GitHub

## Installation & Setup
1. Clone the backend repository:
```bash
git clone https://github.com/yourusername/flexbnb-backend.git
cd flexbnb-backend
```
2. Install dependencies:
```bash
npm install
```
3. Create a `.env` file with the following variables:
```
MONGODB_URI=<your_mongodb_connection_string>
CLOUDINARY_CLOUD_NAME=<your_cloud_name>
CLOUDINARY_API_KEY=<your_api_key>
CLOUDINARY_API_SECRET=<your_api_secret>
JWT_SECRET=<your_jwt_secret>
```
4. Run the backend server:
```bash
npm run dev
```
5. The backend API will be available at `http://localhost:8000`

## Frontend Repository
🖥️ [Flexbnb Frontend on GitHub]([https://github.com/yourusername/flexbnb-frontend](https://github.com/IdanBahar/flexbnb))

## Project Structure
```
backend/
  |-- routes/       # API route definitions
  |-- controllers/  # Request handling logic
  |-- models/       # MongoDB schema models
  |-- services/     # Utility functions, Cloudinary integration, Socket handling
  |-- middleware/   # Authentication & validation middleware
```

## Contact
Built by Idan Bahar — focused on creating clean, maintainable, and scalable backend solutions for full-stack applications.

