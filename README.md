# Netflix Clone

A feature-rich Netflix Clone built using **React** and **Firebase**, offering a dynamic, responsive user interface with secure authentication and real-time database management.

---

## Features

- **Dynamic UI**: Developed reusable and responsive components using **React** and styled with **Tailwind CSS**, delivering a visually appealing interface.
- **Firebase Integration**: Used **Firebase** for user authentication and real-time database functionality to streamline user management and data retrieval.
- **Seamless Navigation**: Integrated **React Router** for smooth page transitions and an enhanced user experience.
- **Protected Routes**: Implemented route protection to ensure secure access to application features.
- **Improved Engagement**: Achieved optimized loading of components and a smooth user flow, improving overall application usability.

---

## Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Firebase (Authentication and Database)
- **Routing**: React Router
- **Build Tool**: Vite

---

---

## Live Demo

Try the live application [here](https://netflix-clone-wi5g.onrender.com/).

---

## How to Run the Code

### Prerequisites
Ensure you have the following tools installed:
1. **Node.js** (LTS version recommended)
2. **npm** (comes with Node.js)
3. A Firebase project setup for authentication and database configuration.

### Steps to Clone and Run Locally

1. **Clone the Repository**:

2. **Install Dependencies**:
   Run the following command to install all necessary packages:
   ```bash
   npm install
   ```

3. **Set Up Firebase**:
   - Go to the Firebase Console: [Firebase Console](https://console.firebase.google.com/).
   - Create a new project or use an existing one.
   - Set up **Authentication** and **Realtime Database** in the Firebase dashboard.
   - Copy your Firebase configuration and add it to the project in a `.env` file:
     ```plaintext
     VITE_FIREBASE_API_KEY=your_api_key
     VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
     VITE_FIREBASE_PROJECT_ID=your_project_id
     VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
     VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
     VITE_FIREBASE_APP_ID=your_app_id
     ```

4. **Start the Development Server**:
   Run the following command to start the app in development mode:
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) in your browser to view the application.


---

## Key Scripts

- **`npm run dev`**: Starts the development server.
- **`npm run build`**: Builds the app for production.
- **`npm run preview`**: Previews the production build.
---


Enjoy building and exploring the Netflix Clone! 😊
