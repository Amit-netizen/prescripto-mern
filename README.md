# ⚕️ Prescripto - Your Digital Health Hub

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![MERN Stack](https://img.shields.io/badge/MERN-MongoDB%20%7C%20Express%20%7C%20React%20%7C%20Node.js-brightgreen)](https://www.mongodb.com/mern-stack)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3.x-%2338B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![React Router](https://img.shields.io/badge/React_Router-v6.x-%23F44250?style=flat&logo=react-router&logoColor=white)](https://reactrouter.com/)

**Prescripto is a comprehensive platform designed to streamline prescription management, medical record access, and doctor-patient communication through a secure and intuitive interface.** Built with the **MERN (MongoDB, Express, React, Node.js) stack**, Prescripto aims to enhance the healthcare experience for both patients and practitioners.

## ✨ Key Features

* **Secure User & Doctor Authentication:** Ensures data privacy and security with robust JWT-based authentication for both patients and doctors.
* **Role-Specific Dashboards:** Provides tailored and intuitive dashboards for users and doctors, offering quick access to relevant features and information.
* **Effortless Appointment Scheduling:** Enables patients to easily book appointments with available doctors through a user-friendly interface.
* **Comprehensive Patient Profile Management:** Securely stores and provides easy access to patient medical history, including appointments and prescriptions.
* **Organized Prescription Management:** Allows users to conveniently view and manage their digital prescriptions.
* **Responsive Design:** Delivers a seamless and consistent experience across all devices (desktops, tablets, and mobile phones) powered by Tailwind CSS.
* **Modern User Interface:** Offers a clean, intuitive, and engaging user experience built with React and styled with Tailwind CSS.
* **Efficient Application Navigation:** Ensures smooth and rapid navigation throughout the application using React Router.

## 🛠️ Technologies Used

This project leverages the power of the following technologies:

* **Frontend:**
    * [React.js](https://react.dev/): A JavaScript library for building dynamic and interactive user interfaces.
    * [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for rapid and customizable UI development.
    * [React Router](https://reactrouter.com/): A standard library for declarative routing in React applications.
    * [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) & [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)

* **Backend:**
    * [Node.js](https://nodejs.org/): A JavaScript runtime environment for building scalable server-side applications.
    * [Express.js](https://expressjs.com/): A minimalist and flexible Node.js web application framework providing a robust set of features for web and mobile applications.
    * [JSON Web Tokens (JWT)](https://jwt.io/): An open, industry standard method for securely transmitting information between parties as a JSON object, used here for authentication.

* **Database:**
    * [MongoDB](https://www.mongodb.com/): A cross-platform, document-oriented NoSQL database, offering high performance, high availability, and easy scalability.
    * [Mongoose](https://mongoosejs.com/): An elegant MongoDB object modeling tool for Node.js, providing a schema-based solution to model your application data.

## 🚀 Getting Started

Follow these steps to get Prescripto up and running on your local machine.

### Prerequisites

Make sure you have the following installed on your system:

* [Node.js](https://nodejs.org/) (LTS version recommended)
* [npm](https://www.npmjs.com/) (usually installed with Node.js) or [Yarn](https://yarnpkg.com/)
* [MongoDB](https://www.mongodb.com/try/download/community) (Community Server)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Amit-netizen/prescripto-mern.git](https://github.com/Amit-netizen/prescripto-mern.git)
    cd prescripto-mern
    ```

2.  **Install backend dependencies:**
    ```bash
    cd backend
    npm install  # or yarn install
    ```

3.  **Configure backend environment variables:**
    * Create a `.env` file in the `backend` directory.
    * Add the following environment variables, replacing the placeholders with your actual values. These variables are crucial for connecting to your database and ensuring secure authentication:
        ```env
        MONGODB_URI=your_mongodb_connection_string # Connection string for your MongoDB database
        JWT_SECRET=your_secret_key_for_jwt       # Secret key used to sign and verify JWTs
        PORT=your_backend_server_port (e.g., 5000) # Port on which the backend server will run
        # Add any other necessary environment variables
        ```

4.  **Start the backend server:**
    ```bash
    npm run dev  # or yarn dev (if you have a dev script in package.json)
    ```
    The backend server should now be running on the specified port.

5.  **Install frontend dependencies:**
    ```bash
    cd ../frontend
    npm install  # or yarn install
    ```

6.  **Configure frontend environment variables:**
    * Create a `.env.local` file in the `frontend` directory.
    * Add the following environment variable, replacing the placeholder with the URL of your backend server. This allows the frontend to communicate with the backend API:
        ```env
        REACT_APP_API_BASE_URL=http://localhost:your_backend_server_port
        # Add any other frontend specific environment variables
        ```

7.  **Start the frontend development server:**
    ```bash
    npm start  # or yarn start
    ```
    The frontend application should now be accessible in your browser, usually at `http://localhost:3000`.
