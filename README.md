# Admin Dashboard Application 🛠️

A robust web application designed for managing users, roles, and permissions efficiently. Administrators can assign roles, define permissions, and control user statuses in a secure and user-friendly interface.

## Table of Contents
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Available Scripts](#available-scripts)
- 
## Project Structure

    Admin-dashboard/
       ├── client/
       │   ├── src/
       │   │   ├── components/
       │   │   │   ├── ErrorMessage.jsx
       │   │   │   ├── LoadingSpinner.jsx
       │   │   │   ├── PremissionManagement.jsx
       │   │   │   ├── RoleManagement.jsx
       │   │   │   ├── UserManagement.jsx
       │   │   │   └── Sidebar.jsx
       │   │   ├── hooks/
       │   │   │   └── useAuth.js
       │   │   ├── services/
       │   │   │   └── api.js
       │   │   └── App.jsx
       │   │   └── index.css
       │   │   └── main.jsx
       │   ├── .gitignore
       │   ├── eslint.config.js
       │   ├── index.html
       │   ├── package-lock.json
       │   ├── package.json
       │   ├── postcss.config.js
       │   ├── tailwind.config.js
       │   ├── tsconfig.app.js
       │   ├── tsconfig.json
       │   ├── tsconfig.node.json
       │   ├── vite.config.ts
       │   └── vite.svg



## Technologies Used

- **Frontend**: React.js, Tailwind CSS
- **Routing**: React Router
- **Custom Hooks**: For managing authentication and API calls
- **Role-Based Access Control (RBAC)**: Securely manage permissions and roles

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/en/) (v14+)
- [MongoDB](https://www.mongodb.com/) for the database
- [npm](https://www.npmjs.com/)

### Steps

1. **Clone the repository:**
   
       git clone https://github.com/your-username/admin-dashboard.git
       cd admin-dashboard

2. **Install dependencies for the frontend:**
   
       cd client
       npm install

3. **Set up environment variables:**

       MONGODB_URI=<your-mongodb-uri>
       JWT_SECRET=<your-jwt-secret>

4. **Run the app:**

       npm start


### Usage

 Once the app is running, you can navigate to the following pages:

- Dashboard: Overview of users, roles, and permissions.
- User Management: Add, edit, delete users, and manage their roles and statuses.
- Role Management: Define roles, assign permissions, and edit role details.
- Login Page: Log in to access the dashboard.

  
### Available Scripts

In the client/ directory, you can run the following scripts:

    npm start
    
Runs the app in development mode. Open http://localhost:3000 to view it in the browser.

    npm run build
    
Builds the app for production to the build folder. Optimizes the build for the best performance.

    npm test
    
Launches the test runner in interactive watch mode.   

---------------------------------
