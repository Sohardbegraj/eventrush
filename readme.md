# EventRush

## 🚀 Overview

**EventRush** is a modern platform to **host**, **discover**, and **participate** in events, competitions, and challenges across technology, business, and culture.  
It is designed as an alternative to platforms like **Unstop**, catering to both event organizers and participants.

---

## 🌟 Features

- **Explore Events** – Discover trending and upcoming events.
- **Host Events** – Full event management: registration, deadlines, submissions.
- **Participant Dashboard** – Track your activity and submissions.
- **Leaderboards & Results** – View rankings and final results.
- **Notifications** – Receive in-app and email updates.
- **Certificates & Prizes** – Award and receive digital certificates.

---

## 🛠️ Tech Stack

### Frontend

- React + TypeScript
- Tailwind CSS
- Axios for API communication

### Backend

- Golang with Gin framework
- MongoDB
- JWT-based Authentication
- RESTful APIs

### Deployment

- Vercel for frontend
- Render for backend
- MongoDB Atlas for database

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/Sohardbegraj/eventrush.git
cd eventrush
```

### Frontend Setup

```bash
cd client
npm install
npm start
```

### Backend Setup

```bash
cd server
go mod tidy
go run main.go
```

---

## 🚴 Running Locally

Make sure MongoDB is running or properly connected via MongoDB Atlas.

- Frontend URL: [http://localhost:3000](http://localhost:3000)
- Backend URL: [http://localhost:8080](http://localhost:8080)

> **Note**: Configure environment variables in `.env` files for both frontend and backend.

---

## 🧪 Sample API Endpoints

| Method | Endpoint            | Description         |
|--------|---------------------|--------------------|
| POST   | `/api/auth/register`| Register user      |
| POST   | `/api/auth/login`   | Login user         |
| GET    | `/api/events`       | Get all events     |
| POST   | `/api/events`       | Host a new event   |
| POST   | `/api/submit/:id`   | Submit to event    |

---

## 🤝 Contributing

We welcome contributions! Fork the repository and submit a pull request.  
For major changes, please open an issue first to discuss what you would like to change.

---
## 👨‍💻 Authors
<a href="https://github.com/Sohardbegraj/eventrush/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Sohardbegraj/eventrush" />
</a>

Built with ❤️ by **LAKSH/ARYAN/SOHARD**.

---

> _Thank you for using EventRush!_
