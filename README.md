# health-tracker-app
🏥 Health Tracker App
Track your daily health stats like calories consumed, sleep hours, and workouts. This full-stack web app visualizes your health patterns with beautiful charts to help improve your well-being.
⚙️ Tech Stack
Layer
Technology
Frontend
React.js, Chart.js
Backend
Node.js, Express
Database
MongoDB
📦 Setup Instructions
📁 Clone the repo
git clone https://github.com/YOUR_USERNAME/health-tracker-app.git
cd health-tracker-app
📂 Backend Setup
cd server
npm install
node server.js
Ensure MongoDB is running on mongodb://localhost:27017/health_tracker
💻 Frontend Setup
cd ../client
npm install
npm start
The React app will run at http://localhost:3000
🔑 Features
➕ Add entries for:
Calorie intake
Sleep (in hours)
Workouts (type, duration, calories burned)
📊 View logs in interactive charts (using Chart.js)
🧠 Data stored securely in MongoDB
🔁 Fetch and visualize the last 7 logs
📊 Sample Chart.js Views
Bar Chart: Calories consumed vs burned
Line Chart: Sleep over days
Pie Chart: Workout types (coming soon)
🚀 Future Improvements
User login/auth (JWT)
Report downloads (PDF/CSV)
Mobile responsive UI
Notifications/reminders
🧑‍💻 Author
Your Name - @yourgithub
MIT

