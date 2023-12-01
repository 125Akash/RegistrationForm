

# Bharat Intern Task - Registration Form

## Overview

This project is a registration form application built using React for the frontend and MongoDB for the database. The codebase is organized into two main folders: "backend" and "frontend," each containing the relevant code for their respective components.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- MongoDB: A NoSQL database for storing user registration data.

## Folder Structure

```
registration-form/
|-- backend/
|   |-- server.js
|   |-- routes/
|       |-- userRoutes.js
|   |-- models/
|       |-- User.js
|   |-- config/
|       |-- config.js
|-- frontend/
|   |-- src/
|       |-- components/
|           |-- RegistrationForm.js
|       |-- App.js
|   |-- public/
|   |-- package.json
|-- .gitignore
|-- README.md
```

## Backend

### Setup

1. Navigate to the `backend` folder: `cd backend`.
2. Install dependencies: `npm install`.
3. Create a MongoDB database and update the connection details in `config/config.js`.
4. Start the server: `npm start`.

### API Endpoints

- `POST /api/users/register`: Register a new user.
- `GET /api/users`: Get all registered users.

## Frontend

### Setup

1. Navigate to the `frontend` folder: `cd frontend`.
2. Install dependencies: `npm install`.
3. Update the API endpoint in `src/components/RegistrationForm.js` to match your backend server.
4. Start the React app: `npm start`.

### Usage

Visit `http://localhost:3000` in your browser to access the registration form.

## Contributing

Feel free to contribute to this project by opening issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to modify the content based on your project's specifics and add any additional information that might be relevant.
