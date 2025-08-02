# health-tracker-app
🏥 Health Tracker App
<img width="1024" height="1536" alt="hta1" src="https://github.com/user-attachments/assets/05be5160-d824-463b-bc52-47cb1f6375a5" />
<img width="1024" height="1536" alt="hta2" src="https://github.com/user-attachments/assets/a4f30f16-31cb-4620-a2d0-b9d3936e43a8" />
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
Your Name - Neha
MIT
🖥️ App UI Overview (Frontend Output)
🔹 Dashboard View (HealthTrackerApp.jsx)
sql
Copy
Edit
+----------------------------------------------+
|        Health Tracker App                    |
+----------------------------------------------+

+---------------- Add Entry -------------------+
| Calories:       [ 2200        ]             |
| Sleep (hrs):    [ 8           ]             |
| Workout Type:   [ Running     ]             |
| Duration (min): [ 45          ]             |
| Calories Burned:[ 300         ]             |
| [Add Entry Button]                          |
+----------------------------------------------+

📊 Calories Consumed vs Burned (Bar Chart)
------------------------------------------
| Date      | Calories | Burned           |
|-----------|----------|------------------|
| Aug 1     | 2200     | 300              |
| Aug 2     | 2100     | 400              |
| Aug 3     | 2000     | 350              |
| ...       | ...      | ...              |
------------------------------------------
(Interactive bar chart rendered using Chart.js)
🗂️ Backend Output (Node Console)
When the server is running:
arduino
Copy
Edit
Server running on http://localhost:5000
On POST request from frontend:
bash
Copy
Edit
POST /api/logs
Log saved
On GET request to fetch logs:
yaml
Copy
Edit
GET /api/logs
[ { _id: ..., calories: 2200, sleep: 8, workouts: [Object], date: ... }, ... ]
🛠️ How to See It Yourself:
Start MongoDB server locally.
Run:
node server.js from /server
npm start from /client
Visit http://localhost:3000

