Quizify 📝

A full-featured Quiz Web Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and styled with Tailwind CSS. Quizify enables users to create quizzes (MCQs & polls), share them via unique links, set timers per question, and allows admins to analyze participant results.

🚀 Features

🔑 JWT Authentication & Authorization – secure signup, login, and data handling.

📝 Quiz Creation – users can design MCQs and poll-based questions.

⏱ Timers – set custom timers for each question.

📤 Shareable Links – distribute quizzes easily.

📊 Result Analysis – admins can view & analyze participant answers.

📱 Responsive UI – seamless experience across devices with Tailwind CSS.

💾 MongoDB – efficient storage and retrieval of users, quizzes, and responses.

🛠️ Tech Stack

Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT

⚡ Getting Started
1. Clone the Repository
git clone https://github.com/<your-username>/quizify.git
cd quizify

2. Install Dependencies

For backend:

cd server
npm install


For frontend:

cd client
npm install

3. Setup Environment Variables

Create a .env file inside the server folder:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

4. Run the Application

Start backend:

cd server
npm run dev


Start frontend:

cd client
npm run dev


Now, open 👉 http://localhost:5173 in your browser.

📂 Project Structure
quizify/
 ├── client/        # React frontend
 ├── server/        # Express backend
 ├── models/        # MongoDB schemas
 ├── routes/        # API routes
 ├── controllers/   # Business logic
 └── README.md

✨ Future Enhancements

📌 Leaderboard for participants

📌 Support for images in quizzes

📌 Email invites for sharing
