# 🗳️ Voting App using k8

A full‑stack web application allowing users to create polls, cast votes, and view results in real time. Built with a focus on user authentication, role‑based permissions, and admin‑controlled poll management.

---

## 🚀 Features

- User registration and login (including roles: voter, admin)
- Admin panel to create, edit, and manage polls
- Voters can browse polls, cast one vote per poll, and view live results
- Poll expiration and access control
- Responsive UI for web or mobile browsers
- Real-time vote count updates and visualizations

---

## 🧰 Tech Stack

*(Update according to your project)*

- Backend: Django / Flask / Node.js + Express  
- Frontend: React.js / Vue.js / HTML/CSS  
- Database: PostgreSQL / MySQL / MongoDB  
- Real‑time updates: WebSocket, Socket.io, or AJAX polling  
- Authentication: JWT, session-based, or OAuth  
- Optional: Docker, CI/CD pipeline

---

## 📂 Repository Structure

.
├── backend/ # API and business logic
├── frontend/ # UI application
├── database/ # Schema setup or migrations
├── scripts/ # Utility or deployment scripts
├── docker-compose.yml # Container orchestration setup
├── README.md # Project overview (this file)
└── requirements.txt or package.json



---

## 🛠️ Setup & Installation

### Prerequisites

- [Node.js & npm] or [Python 3.x]
- [Docker & Docker Compose] (optional, if using containers)
- Database engine (e.g. PostgreSQL/MySQL/MongoDB)

### Local Installation (without Docker)

1. Clone repository:
    ```bash
    git clone https://github.com/azharshaikh7898/voting-app.git
    cd voting-app
    ```

2. Backend setup:
    ```bash
    cd backend
    # If Python:
    python -m venv venv && source venv/bin/activate
    pip install -r requirements.txt

    # If Node.js:
    npm install
    ```

3. Database configuration:
    - Update `.env` or config file with database credentials
    - Run migrations or initialization scripts

4. Start backend service:
    ```bash
    # Python:
    python manage.py runserver

    # Node.js:
    npm start
    ```

5. Frontend setup:
    ```bash
    cd frontend
    npm install
    npm run dev
    ```

6. Access on browser at:
    - Frontend: `http://localhost:3000`
    - Backend API: `http://localhost:8000` (or as configured)

### Using Docker and Docker Compose

1. Ensure Docker is running.
2. From project root:
    ```bash
    docker-compose up --build
    ```
3. Services will be accessible at configured ports (e.g. frontend: 3000, backend: 8000).

---

## 🎯 Usage Workflow

### For Voters:
- Register or login as voter
- Browse available polls
- Cast your vote (one vote per poll)
- View live or final poll results

### For Admins:
- Login as admin role
- Create, schedule, and configure polls
- Set poll expiration and allowed candidates
- Monitor voting statistics

---

## ✅ Sample Usage

Backend CLI (Python example):

cd backend
python manage.py createsuperuser
python manage.py runserver

Frontend CLI:

cd frontend
npm install
npm run build


Contributions are welcome! To contribute:

Fork this repository

Create a branch (feature/xyz)

Commit your changes (git commit -m "Add feature"), then push (git push origin feature/xyz)

Open a Pull Request and describe your changes




