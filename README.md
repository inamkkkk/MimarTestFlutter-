# MimarTestFlutter-

A simple cross-platform mobile app built with **Flutter** and a **Node.js** backend that features:

- User Authentication (Login & Signup)
- Weather Info via external API
- Random Motivational Quote via external API
- Text Generation using Google Gemini API
- User listing on Home screen

---

## 🛠️ Tech Stack

### 📱 Frontend (Flutter)
- Flutter 3.x
- State Management: **Provider**
- HTTP package for API calls
- Form validation
- Responsive UI Design

### 🖥️ Backend (Node.js)
- Node.js with Express.js
- MongoDB (Mongoose)
- JWT for authentication
- Integration with:
  - OpenWeatherMap API
  - Quotable API
  - Google Gemini API (for text generation)

---

## 🚀 Features

### Flutter Frontend:
- **Login & Signup** screens with validation
- **Home Screen** includes:
  - Weather info by city
  - Random quote
  - User list displayed in table format
- Loading indicators and error handling

### Node.js Backend:
- **REST APIs** for `/signup`, `/login` with hashed passwords
- `/weather?city=CityName` → Weather data from OpenWeatherMap
- `/quote` → Quote from Quotable API
- `/gemini` → Text generation using Google Gemini API
- **Protected routes** using JWT tokens

---

## 📦 Packages Used

### Flutter:
- `provider`
- `http`
- `local storage`
- `flutter_spinkit` (for loading indicators)

### Node.js:
- `express`
- `mongoose`
- `jsonwebtoken`
- `bcryptjs`
- `axios`
- `dotenv`
- `cors`

---

## 🧪 API Testing

A **Postman Collection** is included for:
- User signup/login
- Fetching weather, quote, and Gemini response
- Includes Authorization header for protected routes

---

## 🔧 Setup Instructions

### Flutter App:
1. Clone the repo:
   ```bash
   git clone https://github.com/inamkkkk/MimarTestFlutter-.git
   cd MimarTestFlutter
