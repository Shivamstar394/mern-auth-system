# MERN Stack Authentication App

This is a simple MERN (MongoDB, Express, React, Node.js) based authentication app that includes user registration and login functionality with a modern UI and automatic redirection after successful registration.

## Features

- User Registration
- User Login
- Form validation
- Modern responsive UI
- Axios for API requests
- MongoDB Atlas integration
- Redirect to login after successful registration

## Tech Stack

- **Frontend**: React, Axios, CSS
- **Backend**: Node.js, Express.js, Mongoose
- **Database**: MongoDB Atlas

## Project Structure

mern-auth-app/ ├── backend/ │ ├── server.js │ ├── models/ │ ├── routes/ │ └── .env ├── frontend/ │ ├── src/ │ │ ├── components/ │ │ │ ├── Login.js │ │ │ └── Register.js │ │ ├── App.js │ │ └── index.js │ └── package.json └── README.md

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/mern-auth-app.git
cd mern-auth-app
### Backend Setup
bash
Copy
Edit
cd backend
npm install
###Create a .env file in the backend folder:

env
Copy
Edit
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/?retryWrites=true&w=majority

Then run:

bash
Copy
Edit
npm start
3. Frontend Setup
bash
Copy
Edit
cd ../frontend
npm install
npm start
Usage
Open http://localhost:3000/register to create an account.

After registration, you are redirected to http://localhost:3000/login.

Login with credentials to see the welcome alert.

Author
Shivam Ramesh Mishra

License
This project is licensed under the MIT License.

markdown
Copy
Edit

---


 
