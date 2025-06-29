# Auto-Share-Pooling: A Modern MERN Stack Ride-Booking App 🚖

![Auto-Share-Pooling](https://img.shields.io/badge/Auto--Share--Pooling-v1.0.0-blue.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg) ![Node.js](https://img.shields.io/badge/Node.js-v14.17.0-brightgreen.svg) ![React](https://img.shields.io/badge/React-v17.0.2-lightblue.svg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Overview

AutoSharePolling is a modern ride-booking application built using the MERN stack. Inspired by the popular service Rapido, this app allows users to book rides easily. Users can view their ride history, while drivers can accept and complete rides efficiently. The app is designed with a user-friendly interface that enhances the experience for both riders and drivers.

## Features

- **Real-time Vehicle Selection**: Users can see available vehicles in real-time.
- **Location Autocomplete**: Start typing your location, and the app will suggest options.
- **Fare Calculation**: Get an estimate of your ride fare before booking.
- **Ride History**: View all your past rides and their details.
- **Driver Acceptance**: Drivers can easily accept ride requests.
- **Responsive Design**: Works seamlessly on both mobile and desktop devices.

## Technologies

AutoSharePolling uses the following technologies:

- **Frontend**: 
  - React (with Vite)
  - Tailwind CSS
- **Backend**: 
  - Node.js
  - Express.js
- **Database**: 
  - MongoDB

## Installation

To get started with AutoSharePolling, follow these steps:

### Prerequisites

- Node.js (version 14 or later)
- MongoDB (local or cloud instance)

### Clone the Repository

```bash
git clone https://github.com/Cat1155/Auto-Share-Pooling.git
cd Auto-Share-Pooling
```

### Install Dependencies

For the frontend:

```bash
cd client
npm install
```

For the backend:

```bash
cd server
npm install
```

### Environment Variables

Create a `.env` file in the `server` directory and add the following variables:

```
MONGODB_URI=your_mongodb_uri
PORT=5000
```

### Start the Application

To run the application, start the backend and frontend servers:

For the backend:

```bash
cd server
npm start
```

For the frontend:

```bash
cd client
npm run dev
```

Your application should now be running at `http://localhost:3000`.

## Usage

Once the application is running, navigate to `http://localhost:3000` in your browser. You can register as a new user or log in if you already have an account. After logging in, you can start booking rides, view your history, and explore the features available.

## API Documentation

The backend API provides various endpoints for interacting with the application. Below are some key endpoints:

### User Authentication

- **POST** `/api/auth/register`: Register a new user.
- **POST** `/api/auth/login`: Log in an existing user.

### Ride Management

- **POST** `/api/rides/book`: Book a new ride.
- **GET** `/api/rides/history`: Get the ride history for the logged-in user.
- **POST** `/api/rides/accept`: Accept a ride request (for drivers).

### Location Services

- **GET** `/api/locations/autocomplete`: Get location suggestions based on user input.

## Contributing

We welcome contributions to AutoSharePolling. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For the latest releases, visit the [Releases section](https://github.com/Cat1155/Auto-Share-Pooling/releases). Download the latest version and execute it to start using AutoSharePolling.

For any updates, features, or bug fixes, keep an eye on the [Releases section](https://github.com/Cat1155/Auto-Share-Pooling/releases).

## Screenshots

![Homepage](https://via.placeholder.com/800x400?text=Homepage)  
*The homepage where users can start booking rides.*

![Ride Booking](https://via.placeholder.com/800x400?text=Ride+Booking)  
*The ride booking interface with location autocomplete.*

![Ride History](https://via.placeholder.com/800x400?text=Ride+History)  
*View your ride history and details.*

## Contact

For questions or feedback, feel free to reach out via GitHub issues or contact the repository owner directly.

## Acknowledgments

Thanks to the contributors and open-source community for their support and resources. This project would not be possible without their efforts.