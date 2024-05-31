#Scheduling And Appointment booking system for hospitals

## About The Project
Overview: The Hospital Appointment Booking System aims to streamline the process of scheduling appointments for patients at hospitals. It aims to offer a convenient solution for patients to book appointments with doctors, specialists, and other healthcare professionals.

Goal: The goal is to enhance the patient experience by reducing wait times, minimizing administrative tasks, and ensuring efficient allocation of medical resources. 

Target audience: Patients, healthcare providers like doctors, specialists, nurses, and hospital administrators.

Within this system, allows patients to register, log in, and schedule appointments with healthcare providers according to their availability. Patients can also access their appointment history, receive reminders, and cancel or reschedule appointments if necessary. Healthcare providers have access to a dashboard where they can manage their schedules, view patient appointments, and update availability. 


## What Features Will You Find Here:
 - Dynamic Homepage: Conveniently gathers essential information on a single page.
 - Easy Appointment Setup: Seamlessly schedule appointments with doctors, featuring selectable available dates and time ranges.
 - Dynamic Appointment Management: Flexible time and date range selection for appointments.
 - Doctor Selection: Patients can choose their preferred doctor for appointments.
 - Industry-standard Code Quality: Utilization of top-notch code conventions, code splitting, and TypeScript in backend development.
 - Email Notifications: Automated email notifications for appointment setup and invoicing.
 - Doctor Dashboard: Dynamic dashboard for doctors to access patient information and provide online treatment with customizable prescriptions.
 - Patient Dashboard: Patients can track their treatment progress, view medications, prescriptions, and appointment details from a dynamic dashboard.
 - Appointment Tracking: Track appointment status using a unique tracking ID directly from the homepage.
 - User Authentication: Dynamic authentication system allowing user sign-in, sign-up, password recovery, and email verification (for doctors).
 
<!-- GETTING STARTED -->
## Getting Started
To begin using the DocConnect System, follow given beow steps:

### Prerequisites
Before getting started with the DocConnect System, ensure that you have the following prerequisites installed and set up:
* Install Node.js (globally)

  npm install npm@latest -g
* Prisma CLI: If you're planning to work on the backend part, you'll need to have Prisma CLI installed globally. You can install it using npm:

   npm install -g prisma

* TypeScript (optional): TypeScript is used in the backend, ensure that you have TypeScript installed globally. You can install it using npm:

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

#### What Technology Are Using In This Project

**Frontend Technology Stack:** 
- **React**: A JavaScript library for building user interfaces, offering a component-based architecture for creating interactive UIs.
- **Redux Toolkit:** A state management library for React applications, providing predictable state management with a single source of truth.
- **Ant Design:** A UI library for React applications, offering a set of customizable and pre-designed components.
- **React Hook Form:** A library for managing form state and validation in React applications, providing a simple and intuitive API.
- **Axios**: A promise-based HTTP client for making HTTP requests, used for interacting with backend APIs.

**Back-End:** 
- **Express.js:** A web application framework for Node.js, used for building robust APIs and web applications
- **TypeScript:** A superset of JavaScript that adds static typing, enhancing code quality and maintainability.
- **Prisma**: A modern database toolkit for Node.js and TypeScript, used for database access and management.




