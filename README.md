# Workout Buddy

Your Workout Buddy React app in which you can add the daily exercises you do in the gym.
. The frontend is built with React and the backend is built with Node.js and Express.

## Project Structure

The project is divided into two main directories:

frontend/: Contains the React application.
backend/: Contains the Node.js and Express server.

### Frontend

The frontend is a React application. It uses context for state management and has several pages and components.

Key files and directories:

- App.js: The main component that wraps the entire application.
- components/: Contains reusable components like Navbar.js, WorkoutDetails.js, and WorkoutForm.js.
- context/: Contains the application's context providers, AuthContext.js and WorkoutContext.js.
- hooks/: Contains custom React hooks.
- pages/: Contains the different pages of the application.

### Backend

The backend is a Node.js and Express server. It uses MongoDB for the database and has several routes and controllers.

Key files and directories:

- server.js: The entry point to the server.
- controllers/: Contains the logic for handling requests, in userController.js and workoutController.js.
- models/: Contains the Mongoose models for the database, userModel.js and workoutModel.js.
- routes/: Contains the application's routes, user.js and workouts.js.

## Getting Started

To get started with this project, clone the repository and install the dependencies in both the frontend and backend directories:

```
git clone https://github.com/164adityakmar/Workout-Buddy.git
cd workout-tracker
cd frontend
npm install
cd ../backend
npm install
```

Then, you can start the frontend and backend servers:

```
# Start the frontend
cd frontend
npm start

# Start the backend
cd backend
npm start
```

### Contributing
Contributions are welcome! Please read the contributing guide to get started.

### License
This project is licensed under the [MIT License](LICENSE).
