# 🏡 HOMYZ – Full-Stack Real Estate Platform

HOMYZ is a full-stack real estate application that enables users to discover properties, schedule property visits, and manage real estate listings through a modern and responsive user interface. The platform focuses on providing a seamless property browsing experience with secure authentication and efficient data management.

## Features

### Authentication & Authorization

* Secure user authentication using Auth0/AuthJS.
* Protected routes for authenticated users.
* JWT-based session management.

### Property Listings

* Browse available properties.
* View detailed property information including pricing, location, amenities, and images.
* Add and manage property listings.

### Favorites Management

* Save properties to favorites for quick access.
* Manage favorite listings from the user profile.

### Visit Booking System

* Schedule visits for properties directly from the platform.
* Prevent duplicate bookings for the same property.
* View booked properties within the user account.

### User Dashboard

* Manage user profile information.
* Access saved properties and visit bookings.
* Personalized user experience.

### Optimized Performance

* Efficient server-state management using React Query.
* Reduced unnecessary API requests through caching.
* Responsive design across desktop and mobile devices.

---

## Tech Stack

### Frontend

* React.js
* Mantine UI
* React Query
* React Router

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB
* Prisma ORM

### Authentication

* Auth0 / AuthJS
* JWT

### Tools & Technologies

* Git
* GitHub
* Postman

---

## Project Architecture

```text
homyz/
├── client/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── utils/
│   └── context/
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── prisma/
│
└── README.md
```

---

## Installation & Setup

### Clone the Repository

```bash
git clone <your-repository-url>
cd homyz
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file and add the required configuration:

```env
DATABASE_URL=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

AUTH_CLIENT_ID=your_auth_client_id

AUTH_CLIENT_SECRET=your_auth_client_secret
```

### Run the Application

Backend:

```bash
npm run dev
```

Frontend:

```bash
npm start
```

---

## Key Contributions

* Developed a full-stack real estate platform using React, Node.js, Express.js, MongoDB, and Prisma ORM.
* Implemented secure authentication and authorization using Auth0/AuthJS and JWT.
* Built a property visit booking system with duplicate booking prevention.
* Integrated React Query for optimized API communication and client-side caching.
* Designed a responsive and user-friendly interface using Mantine UI components.

---

## Future Enhancements

* Advanced property filtering and sorting.
* Interactive map-based property search.
* Real-time notifications for bookings.
* Property recommendation system.
* Admin dashboard for property management.

---


