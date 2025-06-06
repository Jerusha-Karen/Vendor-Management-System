Vendor Management System
A streamlined tool to help organizations register, manage, and monitor vendors efficiently.

🚀 Features
Vendor Registration – Add new vendors with ease.

Vendor Management – Update contact info, track contracts & performance.

Simple UI – Clean and intuitive interface built with React.

📦 Prerequisites
Node.js

npm

MongoDB

⚙️ Setup Instructions
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/ankur766/Vendor-Management-System.git
cd Vendor-Management-System
2. Install Backend Dependencies
bash
Copy
Edit
cd BackendServer
npm install
3. Add Environment Variables
Create a .env file in BackendServer:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
PORT=5000
4. Start the Backend Server
bash
Copy
Edit
npm start
Server runs at http://localhost:5000.

🧾 Project Structure
pgsql
Copy
Edit
Vendor-Management-System/
├── BackendServer/         # Node.js + Express backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
├── VENDOR SYSTEM/         # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── services/
📌 How to Use
Register vendors via the form.

Manage vendor info in the dashboard.

Monitor performance metrics.

🔮 Future Features
Email alerts for contract renewals

Vendor performance reports

Integration with accounting tools

📄 Docs
API Documentation

Frontend Docs

📬 Contact
Have questions or suggestions? Reach out to the maintainers.
