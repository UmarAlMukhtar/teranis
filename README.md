# TechFest App (Teranis)

## 🚀 Overview
TechFest App (Teranis) is an all-in-one platform for managing college tech fest events, including registrations, competition hosting, live leaderboards, and automated rule enforcement.

## 📌 Features
- **User Authentication** – Google login, email/password (Firebase/Auth0)
- **Event Registration System** – Users sign up for competitions, view schedules
- **Dashboard & Profiles** – Track registrations, results, and announcements
- **Admin Panel** – Manage users, check-in participants, update scores
- **Live Updates & Notifications** – Firebase Cloud Messaging (FCM) for real-time updates
- **QR Code Entry** – Generate QR codes for check-in
- **Leaderboard & Results** – Display winners and rankings
- **Competition Module** – Custom rules, AI restriction detection, automated scoring

## 🏗️ Tech Stack
- **Frontend:** React.js / Next.js
- **Backend:** Express.js + Node.js
- **Database:** MongoDB (Mongoose ORM)
- **Authentication:** Firebase/Auth0
- **Real-time Updates:** Socket.io + Firebase Cloud Messaging (FCM)
- **Deployment:** Vercel (Frontend) + Render/Heroku (Backend)

## 🛠️ Setup & Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/UmarAlMukhtar/teranis.git
cd teranis
```

### 2️⃣ Install Dependencies
#### **Frontend**
```bash
cd client
npx create-next-app@latest .
npm install axios firebase
```

#### **Backend**
```bash
cd ../server
npm init -y
npm install express mongoose dotenv cors firebase-admin socket.io
```

### 3️⃣ Environment Variables
Create `.env.local` in `client` and `.env` in `server`.

#### **Frontend (`client/.env.local`)**
```
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_key
NEXT_PUBLIC_API_URL=http://localhost:5000
```

#### **Backend (`server/.env`)**
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
FIREBASE_ADMIN_KEY=./firebase-admin-key.json
```

### 4️⃣ Running the Project
#### **Start Backend**
```bash
cd server
node server.js
```

#### **Start Frontend**
```bash
cd client
npm run dev
```

## 🔥 Contributors
- **Umar Al Mukhtar Ibrahimkutty** (Lead Developer)
- [Other Contributors]

## 📜 License
This project is licensed under the MIT License.

---
🚀 **Need help?** Open an issue or contribute to the repo!

