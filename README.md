# ⚡ QuickPay — Full-Stack Web App
A minimal full-stack starter to help you jump-start your next project.  
Built with a responsive frontend, secure backend, MongoDB integration, and auth features.

🛠️ Tech Stack
🎨 Frontend
- React  
- Tailwind CSS 
🧠 Backend
- Express 
- MongoDB 
📝 Language
- TypeScript 

🚀 Getting Started
1️⃣ Clone the repo
git clone https://github.com/NishulDhakar/QuickPay.git
cd QuickPay

2️⃣ Install dependencies
Backend:
cd backend
npm install

Frontend:
cd frontend
npm install

3️⃣ Configure environment variables
Create a .env file in your backend directory:
MONGO_URL=your_mongodb_connection_string
PORT=3001
JWT_SECRET=your_secret_key
SENDGRID_API_KEY=your_sendgrid_key

4️⃣ Run the app
Backend:
cd backend
npm run dev

Frontend:
cd frontend
npm start

✨ Backend Features
- User auth (signup, signin) with hashed passwords
- OTP using SendGrid
- Middleware for protected routes
- User profile updates & search (/bulk)
- Account routes (/balance, /transfer)
- Mongo schema for accounts & transactions

🎨 Frontend Features
- React Router for /signin, /signup, /dashboard
- Axios for API calls
- Reusable Input & Button components
- Display user list, send money
- Responsive dashboard with Tailwind CSS

🚀 Deploy
Vercel — for frontend (npm run build)
Render — for backend (npm install && npm run build && npm start)

🤝 Contributing
Issues, pull requests & feature ideas are welcome!

