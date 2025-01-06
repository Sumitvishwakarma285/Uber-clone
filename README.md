# Uber Clone

Uber Clone is a real-time ride-hailing application built using the MERN stack. This project replicates the core features of the Uber app, including ride booking, real-time tracking, and payment integration. It aims to provide a seamless experience for users to book and track rides while ensuring a robust and scalable backend.

## Features

- **User Authentication**: 
  - Secure login/signup with email/password and JWT-based authentication.
  - User profile management.

- **Ride Booking**:
  - Users can book rides by entering pickup and destination locations.
  - Real-time ride tracking with live map updates.

- **Payment Integration**:
  - Integrated payment gateway for ride payments and transaction management.

- **Real-Time Notifications**:
  - Push notifications for ride status updates and user alerts.

- **Admin Dashboard**:
  - Admin panel to manage users, rides, and payments.

## Tech Stack

### Frontend
- **React.js**: For building dynamic and responsive user interfaces.
- **Redux**: For state management across the app.
- **Google Maps API**: For displaying maps and real-time location tracking.
- **Tailwind CSS**: Utility-first CSS framework for styling.

### Backend
- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Lightweight web framework for building APIs.
- **MongoDB**: NoSQL database for storing user, ride, and payment data.
- **JWT Authentication**: Secure user authentication.

### Other Tools
- **Socket.io**: For real-time communication (ride tracking, notifications).
- **Stripe API**: For handling payments and transactions.

## Project Structure
Uber-Clone/ ├── frontend/ │ ├── src/ │ │ ├── components/ │ │ ├── pages/ │ │ ├── redux/ │ │ ├── App.js │ │ └── index.js │ └── public/ ├── backend/ │ ├── controllers/ │ ├── models/ │ ├── routes/ │ ├── server.js │ └── config/ ├── .gitignore ├── package.json └── README.md

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Sumitvishwakarma285/Uber-clone.git
Navigate to the project directory:
cd Uber-clone
Install dependencies:

cd backend
npm install
cd ../frontend
npm install
Access the application:

Frontend: http://localhost:3000
Backend API: http://localhost:5000
Acknowledgements
Inspiration for building this Uber clone came from the desire to replicate the real-world functionality of a ride-hailing app.
Special thanks to the contributors and supporters of this project.
