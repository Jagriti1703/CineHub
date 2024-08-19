# CineHub

CineHub is a full-featured movie streaming and ticket booking platform built using the MERN stack (MongoDB, Express.js, React, Node.js). This platform allows users to watch movies online and book tickets for upcoming showtimes, providing a seamless experience for movie lovers.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Stream Movies**: Watch a variety of movies from different genres.
- **Book Tickets**: Reserve your seats for the latest movie releases.
- **User Authentication**: Secure user registration and login.
- **Admin Dashboard**: Manage movies, showtimes, and user data.
- **Responsive Design**: Optimized for all devices, from desktop to mobile.

## Technologies Used

- **Frontend**: React.js, HTML5, CSS3, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Integration**: [Optional] Stripe API
- **Deployment**: [Optional] Heroku, Netlify

## Installation

To get a local copy up and running, follow these steps:

### Prerequisites

- Node.js
- MongoDB

### Clone the Repository

```bash
git clone https://github.com/your-username/cinehub.git
cd cinehub
```

### Install Dependencies

For the backend:

```bash
cd backend
npm install
```

For the frontend:

```bash
cd ../frontend
npm install
```

### Set Up Environment Variables

Create a `.env` file in the `backend` directory and add the following:

```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Run the Application

Start the backend server:

```bash
cd backend
npm start
```

Start the frontend development server:

```bash
cd ../frontend
npm start
```

Open your browser and navigate to `http://localhost:3000` to see CineHub in action.

## Usage

1. **Sign Up / Log In**: Create an account or log in to access the platform.
2. **Browse Movies**: Explore the available movies.
3. **Watch or Book**: Choose to either stream a movie online or book a ticket for a cinema experience.
4. **Admin Access**: If you have admin privileges, manage movies, showtimes, and users via the admin dashboard.

## Project Structure

```
cinehub/
├── backend/           # Express.js backend
├── frontend/          # React.js frontend
├── README.md          # Project documentation
└── .gitignore         # Ignored files and directories
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
