<div align="center">

  # 📊 Socio-Dash
  ### Analytics & Scheduling Platform

  <p>
    A full-stack <strong>PERN</strong> (PostgreSQL, Express, React, Node.js) application designed for real-time social media management.
  </p>

  <p>
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node" />
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="Postgres" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind" />
    <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
  </p>

  <img src="https://github.com/user-attachments/assets/2d491afe-86c4-43e1-a2e7-482775df7ee6" alt="Dashboard Preview" width="100%" />

</div>

---

## 🚀 Features

* **🔐 Secure Authentication:** JWT-based user registration and login system with bcrypt password hashing.
* **📈 Interactive Dashboard:**
    * Real-time statistics for Followers, Likes, Shares, and Engagement Rate.
    * **Data Visualization:** Interactive weekly engagement line graph using `Recharts`.
* **📅 Content Scheduler:**
    * Draft and schedule posts for platforms like Twitter and LinkedIn.
    * View upcoming scheduled content in a chronological timeline.
    * Automatic status updates (Draft/Scheduled/Published).
* **📱 Responsive Design:** Fully responsive UI built with **Tailwind CSS**.

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | React (Vite), Tailwind CSS, Recharts, Lucide React, Axios |
| **Backend** | Node.js, Express.js |
| **Database** | PostgreSQL, Prisma ORM |
| **Auth** | JSON Web Tokens (JWT), Bcrypt |

---

## 📸 Project Screenshots

<table width="100%">
  <tr>
    <td width="50%">
      <h3 align="center">Analytics Dashboard</h3>
      <img src="https://github.com/user-attachments/assets/2d491afe-86c4-43e1-a2e7-482775df7ee6"  alt="Dashboard" />
    </td>
    <td width="50%">
      <h3 align="center">Content Scheduler</h3>
      <img src="https://github.com/user-attachments/assets/da6bff0e-90a6-4b98-9418-722d898110d5" alt="Scheduler" />
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <h3 align="center">Secure Login</h3>
      <div align="center">
        <img src="https://github.com/user-attachments/assets/1b27620e-e88d-4653-b412-665629ae82b3" alt="Login Page" width="50%" />
      </div>
    </td>
  </tr>
</table>

---


### 🚀 Live Link: [Socio_Dash](https://social-dashboard-vert.vercel.app/)


## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### **1. Prerequisites**
* Node.js (v16 or higher)
* PostgreSQL installed and running locally
* Git

### **2. Clone the Repository**
```bash
git clone [https://github.com/your-username/social-dashboard.git](https://github.com/your-username/social-dashboard.git)
cd social-dashboard
3. Backend Setup
Navigate to the backend folder and install dependencies:

Bash

cd social-dashboard-backend
npm install
Create a .env file in the social-dashboard-backend directory:

Code snippet

DATABASE_URL="postgresql://postgres:password@localhost:5432/social_dashboard?schema=public"
JWT_SECRET="your_super_secret_key"
PORT=3000
Run database migrations to create the tables:

Bash

npx prisma migrate dev --name init
Start the backend server:

Bash

npm run dev
4. Frontend Setup
Open a new terminal, navigate to the frontend folder, and install dependencies:

Bash

cd social-dashboard-frontend
npm install
Start the frontend development server:

Bash

npm run dev
Visit http://localhost:5173 in your browser.

🤝 Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request


