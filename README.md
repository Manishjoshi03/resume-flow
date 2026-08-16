# ResumeFlow — Full-Stack ATS Resume Builder

ResumeFlow is a full-stack web application for creating, managing, customizing, and exporting ATS-friendly resumes.

## Features

* Create and edit resumes with a live editor
* Drag-and-drop resume sections and bullet points
* JWT-based authentication and protected routes
* OTP-based password reset
* Resume version history
* Public resume sharing links
* Export resumes as PDF and DOCX
* Sequelize ORM with relational database

## Screenshots

### Homepage

![ResumeFlow Homepage](./screenshots/image1.png)

### Resume Builder CTA Section

![Resume Builder CTA Section](./screenshots/image2.png)

## Tech Stack

### Frontend

* Angular 13
* TypeScript
* Angular Material
* SCSS
* RxJS
* Angular Reactive Forms

### Backend

* Node.js
* Express.js
* Sequelize ORM
* MySQL / PostgreSQL
* JWT
* bcrypt
* Nodemailer
* wkhtmltopdf
* html-to-docx

## Project Structure

```text
resume-flow/
├── frontend/
├── backend/
├── screenshots/
│   ├── image1.png
│   └── image2.png
├── .gitignore
└── README.md
```

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/bhanu-joshi01/resume-flow.git
cd resume-flow
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file with your database and authentication configuration.

Run migrations:

```bash
npx sequelize-cli db:migrate
```

Start the backend:

```bash
npm run dev
```

Backend:

```text
http://localhost:3000
```

### Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm start
```

Frontend:

```text
http://localhost:4200
```

## API

The backend provides REST APIs for:

* Authentication
* Dashboard
* Resumes
* Resume sections
* Bullet points
* Public resume sharing
* PDF export
* DOCX export

## Authentication

JWT is used for authentication and protected routes.

OTP-based verification is used for password reset.

## Database

Sequelize ORM is used to interact with the relational database.

Supported databases:

* MySQL
* PostgreSQL

## Resume Export

ResumeFlow supports:

* **PDF** — using `wkhtmltopdf`
* **DOCX** — using `html-to-docx`

## Author

**Harshit Joshi**

BCA (AI & ML) | Full-Stack Web Developer

GitHub: [@harshit2k05](https://github.com/harshit2k05)

