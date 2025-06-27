# Uber Full Stack Clone

## Overview
This is a full-stack Uber clone built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to sign up, book rides, and track them in real time, while captains (drivers) can accept or reject ride requests.

## Live Demo
- Check out the live demo: [Uber Clone](https://uber-frontend-taupe.vercel.app/)
- Use "Mobile View" for better experience - recommended
## Features Implemented
### Authentication & Authorization
- User and Captain signup/login with JWT authentication
- Token storage in browser cookies
- Middleware for protected routes

![AuthenticationUser](/public/Authentication%20user.png) 

![AuthenticationCaptain](/public/Authentication%20captain.png) 

### User Features
- Book a ride by entering pickup and destination locations
- See estimated fare and ride OTP
- Get real-time ride status updates
- Live tracking of the ride
- OTP verification for ride completion

![userfeature](/public/userfeature.png) 


### Captain Features
- Accept or reject ride requests
- View ride details including pickup and destination
- Live tracking of the ride
- Finish the ride after OTP verification

![captainfeature](/public/captainfeature.png) 

### WebSocket Implementation
- Real-time notifications for captains when a new ride is available

![usercaptainpov](/public/usercaptainpov.png) 


### Backend Features
- Ride fare calculation
- Secure password hashing using bcrypt
- WebSockets for real-time communication
- Blacklisting tokens on logout

## Technologies Used
### Frontend
- React.js
- Tailwind CSS for styling
- Axios for API requests
- Context API for state management

### Backend
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT for authentication
- bcrypt for password hashing
- Socket.io for real-time updates

## Deployment
- Frontend: Vercel
- Backend: Railway.app
- Database: MongoDB Atlas

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps to Run Locally
#### Clone the Repository
```sh
git clone https://github.com/dummy/uber-clone.git
cd uber-clone
```

#### Backend Setup
```sh
cd backend
npm install
npx nodemon
```

#### Frontend Setup
```sh
cd frontend
npm install
npm run dev
```
#### Other Setup
```sh
Make sure to setup the environment variables at both frontend and backend
```

## Future Improvements
Here are some features that could be added:
- Profile picture upload for users and captains
- A separate profile analytics page for users and captains
- Payment gateway integration for ride payments
- Displaying nearby captains based on user’s pickup location
- Ride history and past transactions
- Admin dashboard for managing users and captains

## Contributing
If you'd like to contribute, feel free to fork the repo and create a pull request.

## Credits
Thank you [Sheryians Coding School](https://www.youtube.com/@sheryians) for guiding me through this entire project.



This README file provides all the necessary details for the project, including setup instructions and future scope.
