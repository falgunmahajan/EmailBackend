# Email Scheduler API

## Description
This API allows users to schedule emails to be sent after an hour using Agenda and Nodemailer.

---

## Features
- Schedule emails after an hour.
- JWT-based authentication for secure endpoints.
- Input validation to ensure valid data.

---

## Setup Instructions

### Prerequisites
- Node.js (v14+)
- MongoDB

---

### Installation
- Clone the repository:
```bash
   git clone https://github.com/falgunmahajan/EmailBackend.git
```

- Install dependencies:
```bash
   npm install
```

- Set up the .env file:
```bash
   PORT=3000
   DBURL=mongodb://localhost:27017/email-scheduler
   JWT_SECRET=your_jwt_secret
   USER=your_email@gmail.com
   PASS=your_email_password
```

- Start the server:
```bash
  npm start
```

### Testing
- Run tests using Jest:
```bash
  npm test
```
