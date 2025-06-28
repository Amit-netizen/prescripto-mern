# ⚕️ Prescripto – Secure Health SaaS Platform

[![MERN Stack](https://img.shields.io/badge/MERN-MongoDB%20%7C%20Express%20%7C%20React%20%7C%20Node.js-brightgreen)](https://www.mongodb.com/mern-stack)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3.x-%2338B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![React Router](https://img.shields.io/badge/React_Router-v6.x-%23F44250?style=flat&logo=react-router&logoColor=white)](https://reactrouter.com/)

**Prescripto** is a full-stack web application built using the **MERN (MongoDB, Express, React, Node.js) stack**. It aims to streamline the management of prescriptions, medical records, and facilitate seamless doctor-patient interaction through secure authentication and intuitive interfaces.

## ✨ Key Features

* **Secure Authentication:** Robust JWT (JSON Web Tokens) based authentication for both users (patients) and doctors, ensuring data privacy and security.
* **Role-Based Dashboards:** Dedicated and intuitive dashboards tailored for users and doctors, providing relevant features and information at a glance.
* **Effortless Appointment Scheduling:** A user-friendly system for patients to book appointments with doctors based on availability.
* **Comprehensive Patient Profile Management:** Secure storage and easy access to patient medical history, including past appointments and prescriptions.
* **Prescription Management:** Organize and view digital prescriptions conveniently.
* **Responsive Design:** A seamless experience across various devices, from desktops to mobile phones, thanks to Tailwind CSS.
* **Modern UI:** A clean and user-friendly interface built with React and styled with Tailwind CSS.
* **Efficient Routing:** Smooth navigation within the application using React Router.

## 🛠️ Technologies Used

This project leverages the power of the following technologies:

* **Frontend:**
    * [React.js](https://react.dev/): A JavaScript library for building user interfaces.
    * [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development.
    * [React Router](https://reactrouter.com/): A standard library for routing in React applications.
    * [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML): Provides the semantic structure and organization of the web application's content.
    * [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS): Handles the visual styling, layout, and responsiveness of the user interface, ensuring a consistent experience across different devices.

* **Backend:**
    * [Node.js](https://nodejs.org/): A JavaScript runtime built on Chrome's V8 JavaScript engine.
    * [Express.js](https://expressjs.com/): A minimal and flexible Node.js web application framework.
    * [JSON Web Tokens (JWT)](https://jwt.io/): For secure authentication and authorization.

* **Database:**
    * [MongoDB](https://www.mongodb.com/): A NoSQL document database.
    * [Mongoose](https://mongoosejs.com/): An elegant MongoDB object modeling for Node.js.

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
    * Add the following environment variables, replacing the placeholders with your actual values:
        ```env
        MONGODB_URI=your_mongodb_connection_string
        JWT_SECRET=your_secret_key_for_jwt
        PORT=your_backend_server_port (e.g., 5000)
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
    * Add the following environment variable, replacing the placeholder with your backend server URL:
        ```env
        REACT_APP_API_BASE_URL=http://localhost:your_backend_server_port
        # Add any other frontend specific environment variables
        ```

7.  **Start the frontend development server:**
    ```bash
    npm start  # or yarn start
    ```
    The frontend application should now be accessible in your browser, usually at `http://localhost:3000`.
