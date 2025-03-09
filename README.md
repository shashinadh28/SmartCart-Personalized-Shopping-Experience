🛍️ SmartCart – Personalized E-Commerce Webpage
🚀 Overview
SmartCart is a full-featured MERN stack e-commerce platform that dynamically changes content based on user behavior, providing a personalized shopping experience.

🌟 Features
✅ Personalized Product Recommendations
✅ User Signup & Authentication (JWT)
✅ MongoDB & Redis Integration
✅ Shopping Cart & Order Management
✅ Coupon Code System
✅ Secure Payments with Razorpay
✅ Admin Dashboard for Product & User Management
✅ Sales Analytics & Insights
✅ Tailwind CSS for Responsive UI
✅ Caching for Optimized Performance

🔧 Project Setup
2️⃣ Install Dependencies
npm install
cd frontend && npm install
3️⃣ Setup .env File
Create a .env file in the root directory and add the following:

PORT=5000
MONGO_URI=your_mongo_uri
UPSTASH_REDIS_URL=your_redis_url
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
CLIENT_URL=http://localhost:5173
NODE_ENV=development
4️⃣ Run the App Locally
Backend
npm run dev
Frontend
cd frontend
npm run dev
