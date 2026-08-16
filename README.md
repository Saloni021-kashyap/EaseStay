# EaseStay 🏡

EaseStay is a full-stack, Airbnb-inspired stay listing web application built through hands-on coding to understand and implement real-world web development and backend concepts.

The project focuses on building a complete CRUD-based listing platform with **Node.js, Express.js, MongoDB, Mongoose, EJS, Passport authentication, session management, MVC architecture, middleware, validation, reviews, and Cloudinary image uploads.**

> This project was built to gain practical experience in connecting frontend, backend, database, authentication, authorization, and cloud-based image storage into a complete web application.

---

## 🚀 Features

- User Registration & Login
- Session-based Authentication
- Passport.js Authentication
- Protected Routes
- User Authorization
- Create Listings
- View Listings
- Update Listings
- Delete Listings
- Category-based Listing Filtering
- Listing Owner Authorization
- Reviews & Ratings
- Review Author Authorization
- Image Upload using Cloudinary
- Form Validation using Joi
- Flash Messages
- Custom Error Handling
- 404 Error Page
- MVC Architecture
- Dynamic Server-side Rendering using EJS

---

## 🛠️ Tech Stack

### Frontend

- HTML
- CSS
- JavaScript
- EJS
- EJS-Mate

### Backend

- Node.js
- Express.js

### Database

- MongoDB
- Mongoose

### Authentication

- Passport.js
- Passport Local
- Passport Local Mongoose
- Express Session

### Image Upload & Storage

- Multer
- Cloudinary
- Multer Storage Cloudinary

### Validation & Middleware

- Joi
- Custom Express Middleware
- Method Override
- Connect Flash

### Tools

- Git
- GitHub
- npm
- VS Code

---

## 🏗️ MVC Architecture

EaseStay follows the **MVC (Model-View-Controller)** architecture to keep the application organized and maintainable.

```text
                    User
                     │
                     ▼
                   Routes
                     │
                     ▼
        Authentication / Middleware
                     │
                     ▼
                Controllers
                     │
                     ▼
              Mongoose Models
                     │
                     ▼
                  MongoDB
                     │
                     ▼
                Controllers
                     │
                     ▼
                EJS Views
                     │
                     ▼
                    User
