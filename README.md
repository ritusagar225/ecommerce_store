# 🛒 **CommerceCraft** ✨  
A modern, full-stack e-commerce web application designed to deliver a secure, fast, and seamless online shopping experience. **CommerceCraft** combines robust authentication, Stripe-powered payments, efficient caching, and a beautiful responsive UI to showcase a production-ready online store.

---

## 🌐 **Live Demo**

👉 [Check out the live website here](https://your-app.onrender.com)  


---

## 🌟 **Key Features**

🔐 **JWT Authentication System** — Secure user signup, login, and session management with JSON Web Tokens.  
🛡️ **Protected Routes** — Backend routes secured for authorized users and admins only.  
👤 **User Profiles & Orders** — Customers can manage their accounts, view order history, and update personal info.  
📦 **Product & Category Management** — Add, edit, or remove products and categories with ease.  
🛍️ **Shopping Cart & Checkout** — Add products to cart, apply coupon codes, and complete checkout securely with Stripe.  
💳 **Stripe Payment Integration** — Handles secure payment processing with real-time feedback.  
🏷️ **Coupon System** — Admins can create discount codes; customers can apply them at checkout.  
📊 **Admin Dashboard** — Sales analytics and order management for store admins.  
⚡ **Caching with Redis** — Optimizes performance for frequently requested data.  
🖼️ **Image Upload with Cloudinary** — Store and serve high-quality product images.  
🎨 **Responsive Tailwind CSS UI** — Clean, mobile-friendly design for a smooth user experience.  
🔒 **Security Best Practices** — Robust error handling, data validation, and environment config.  
⌛ **And much more...** — Fully extendable for real-world e-commerce scenarios.

---

## 🛠️ **Tech Stack**

**Frontend:**  
- React (Vite)
- Tailwind CSS

**Backend:**  
- Node.js
- Express.js
- MongoDB
- JWT for authentication
- Redis for caching
- Stripe API for payments
- Cloudinary for image hosting
- Socket.IO (optional for real-time features)

---

## ⚙️ **Environment Variables**

Create a `.env` file in your project root and add the following:

```env
PORT=5000

MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key

CLIENT_URL=http://localhost:5173
NODE_ENV=development
