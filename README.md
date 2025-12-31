# 📦 StreamScene Backend

StreamScene Backend is a scalable REST API built using Node.js, Express, MongoDB, and MVC architecture.
It powers authentication, content discovery, premium subscriptions, watchlists, and secure video streaming for the StreamScene platform.

## ✨ Features
- JWT-based Authentication (Signup, Login, Logout)
- Password Reset using OTP (Email-based)
- Movie & TV Show discovery via TMDB APIs
- User Watchlist management
- Premium access management
- Secure video streaming using HTTP Range Requests

## 🧱 Tech Stack
- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB + Mongoose
- **Payments:** Razorpay
- **Email Service:** SendGrid (via Nodemailer)
- **Video Streaming:** Native Node streams

## 

## 📦 Installation & Setup

1. #### Environment Variables:
    Create .env file in root directory-

    ```bash
    DB_USERNAME= <your_mongodb_connection_username>
    DB_PASSWORD= <your_mongodb_connection_password>
    KEY_ID= <Razorpay key ID> 
    KEY_SECRET= <Razorpay key secret>
    JWT_SECRET_KEY = <your JWT secret>
    SENDGRID_API_KEY = <your_sendgrid_api_key>
    TMDB_KEY = <your_tmdb_api_key>
    ```

2. #### Clone the Repository:

    ```bash
    git clone https://github.com/rutujashaha786/stream-scene-backend.git
    cd yourprojectname
    ```
3. #### Install Dependencies:

    ```bash
    npm install (Note: Use node version >=18.20)
    ```
4. #### Start the Server:

    ```bash
    npm run dev
    ```
    Server runs at:

    ```bash
    http://localhost:3005
    ```


### Consuming the APIs:
- This backend exposes RESTful APIs that can be consumed by Frontend apps