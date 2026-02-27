🏗 Project Architecture

Frontend (React)
⬇ API calls
Backend (Node + Express)
⬇ (Future Integration)
Arduino / Energy Sensors

🛠 Technologies Used
Frontend

React.js

Vite

CSS

Fetch API

Backend

Node.js

Express.js

CORS

Future Hardware Integration

Arduino (or ESP32)

Current sensor (ACS712)

Voltage sensor module

Relay module (for source switching)

📊 Features

✅ Real-time energy simulation

✅ Automatic threshold-based switching

✅ Manual override modes:

Force Grid

Force Solar

Auto Mode

✅ Live API-based data fetching

✅ Beginner-friendly architecture

✅ IoT-ready backend

⚙️ How It Works

Backend simulates energy usage increasing every second.

When energy ≥ 2.5 kWh:

Source switches to Solar.

Frontend fetches data from:

http://localhost:5000/api/energy

Dashboard updates automatically.

🧪 Running the Project Locally
🔹 1. Clone the Repository
git clone https://github.com/your-username/energy-dashboard.git
cd energy-dashboard
🔹 2. Install Frontend Dependencies
npm install
npm run dev

Frontend runs on:

http://localhost:5173
🔹 3. Setup Backend
cd backend
npm install
node server.js

Backend runs on:

http://localhost:5000

Test API:

http://localhost:5000/api/energy
