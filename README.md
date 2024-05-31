#Scheduling And Appointment booking system for hospitals

The goal of this project is to enhance the patient experience by reducing waiting times in queue to book appointments, minimizing administrative tasks, and ensuring efficient allocation of medical resources. In this system,  patients register, then log in, and schedule appointments . Patients can also view their appointment history in the dashboard.

Features: Dynamic Homepage, Easy Appointment Setup, Dynamic Appointment Management, Doctor Selection, Industry-standard Code Quality, Email Notifications, Doctor Dashboard, Patient Dashboard, Appointment Tracking, User Authentication
 
<!-- GETTING STARTED -->
## Getting Started
To begin using the DocConnect System, follow given below steps:

### Prerequisites
Before getting started with the DocConnect System, install and set up:
* Install Node.js (globally)

  npm install npm@latest -g
* Prisma CLI:

   npm install -g prisma

* TypeScript

   npm install -g typescript


## Installation
To begin using the DoctorOnCall System, follow these simple steps:
### The front-end and Backend code are in the same directory, with the Backend API located at the ./api directory


### Install Frontend
cd Doctor-Appointment
- npm install
- npm start

### Install Backend
cd api
- npm install

### Setup Database
1. Rename .env.example to .env (remove .example).
2. Create a PostgreSQL Database (Railway if you don't have one installed locally):
   - Create an account at https://railway.app/.
   - Navigate to the New Section > Database > Add PostgreSQL.
   - Select your created database and go to the Variables tab.
   - Copy DATABASE_PUBLIC_URL.
   - Paste the database URL into the .env file.

### Install Prisma
- npm install -g prisma
- npx prisma generate
- npx prisma migrate dev

### Setup Google App Password (For Email Notification)
1. Go to Google Account settings at https://myaccount.google.com/security?hl=en.
2. Navigate to Security > 2-Step Verification.
3. Scroll to the bottom of the page and find App passwords.
4. Select your project name and copy the generated password.
5. Paste the app password into .env as EMAIL_PASS.

### Setup Cloudinary to Upload Image
1. Create a Cloudinary Account at https://cloudinary.com/.
2. Login to your Cloudinary Account and copy all the credentials (e.g., Cloud name, API key, API secret).
3. Paste those credentials into the .env file.

### Start Backend
npm run dev

Technologies Used In This Project

Frontend Technology Stack: 
- React: A JavaScript library for building user interfaces, offering a component-based architecture for creating interactive UIs.
- Redux Toolkit: A state management library for React applications, providing predictable state management with a single source of truth.
- Ant Design: A UI library for React applications, offering a set of customizable and pre-designed components.
- React Hook Form: A library for managing form state and validation in React applications, providing a simple and intuitive API.
- Axios: A promise-based HTTP client for making HTTP requests, used for interacting with backend APIs.

Back-End:
- Express.js: A web application framework for Node.js, used for building robust APIs and web applications
- TypeScript: A superset of JavaScript that adds static typing, enhancing code quality and maintainability.
- Prisma: A modern database toolkit for Node.js and TypeScript, used for database access and management.




