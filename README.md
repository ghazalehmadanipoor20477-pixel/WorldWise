# 🌍 WorldWise

**WorldWise** is a responsive front-end web application built with **React** that allows users to explore cities and countries around the world, manage visited cities, and view their locations on an interactive map.

## ✨ Features

### 🏙️ City & Country Lists

* Browse a list of cities around the world.
* View each city's name, location, and representative emoji.
* Explore countries and their associated cities.
* Easily navigate between cities and countries.

### 📍 City Details

Each city has a dedicated details page containing:

* City name
* Country
* Geographic coordinates
* Emoji representation
* Additional information about the city
* Exact location displayed on an interactive map

### 🗺️ Interactive Map

WorldWise uses **Leaflet** to provide an interactive map.

Users can:

* View cities directly on the map.
* See the exact geographical location of each city.
* Explore nearby areas.
* Select cities directly from the map.

### ➕ Add New City

Authenticated users can add new cities through a dedicated form.

The form includes:

* City name
* Latitude
* Longitude
* Emoji

Form validation is implemented to prevent incomplete or invalid city data from being submitted.

### 🔐 Authentication & Protected Routes

The application includes a login system with:

* Username and password authentication
* Protected routes
* Restricted access to authenticated-only pages

For example, adding a new city is only available to authenticated users.

### 💳 Product & Pricing

WorldWise also includes:

* **Product Page** — showcases the application's products/services and their benefits.
* **Pricing Page** — presents different subscription plans and pricing options.

### 📱 Responsive Design

The application is designed to work across different screen sizes and devices, providing a consistent user experience on:

* 💻 Desktop
* 📱 Mobile
* 📟 Tablet

---

## 🛠️ Technologies Used

| Technology       | Purpose                            |
| ---------------- | ---------------------------------- |
| **React**        | Building the user interface        |
| **React Router** | Client-side routing and navigation |
| **Context API**  | Global state management            |
| **Leaflet**      | Interactive maps                   |
| **JavaScript**   | Application logic                  |
| **CSS**          | Styling and responsive design      |
| **JSON Server**  | Fake REST API for development      |

---

## 📂 Project Structure

```text
WorldWise/
├── public/
├── src/
│   ├── components/
│   ├── contexts/
│   ├── pages/
│   ├── App.js
│   └── index.js
├── data/
├── package.json
└── README.md
```

> The exact folder structure may vary depending on the project implementation.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/worldwise.git
```

### 2. Navigate to the project

```bash
cd worldwise
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the fake API server

```bash
npm run server
```

### 5. Start the React development server

In another terminal:

```bash
npm start
```

### 6. Open the application

Visit:

```text
http://localhost:3000
```

---

## 🔑 Authentication

WorldWise includes protected routes that require authentication.

Users can log in through the login page to access protected functionality such as adding new cities.

---

## 🗺️ Map Integration

The map functionality is powered by **Leaflet**, allowing the application to display city locations based on latitude and longitude coordinates.

This makes it easy for users to visually explore the cities they've added or visited.

---

## 📸 Visual Overview:
<img width="3840" height="2160" alt="home" src="https://github.com/user-attachments/assets/1b66b904-19f0-41da-8ba4-92e7e60aabed" />
<img width="1920" height="1080" alt="map" src="https://github.com/user-attachments/assets/30347d0c-29f0-4f98-b9a7-cc6c82e3b5f3" />

