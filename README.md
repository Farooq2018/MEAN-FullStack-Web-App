# MEAN-FullStack-Web-App

Welcome to the MEAN-FullStack-Web-App! This project is a comprehensive web application built using the MEAN (MongoDB, Express, Angular, Node.js) stack. It offers a fully functional backend, a rich frontend, and seamless integration between the two.

## Table of Contents

- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This web application is designed to manage travel trips. Users can create, edit, and view trips, with features such as authentication, trip listings, and detailed trip information.

## Directory Structure

```
Farooq2018-MEAN-FullStack-Web-App/
├── README.md
├── app.js
├── package.json
├── .seedgooserc.js
├── app_admin/
│   ├── README.md
│   ├── angular.json
│   ├── package-lock.json
│   ├── package.json
│   ├── tsconfig.json
│   ├── tslint.json
│   ├── .editorconfig
│   ├── .gitignore
│   ├── e2e/
│   └── src/
├── app_api/
│   ├── config/
│   ├── controllers/
│   ├── database/
│   └── routes/
├── app_server/
│   ├── controllers/
│   ├── routes/
│   └── views/
├── bin/
├── data/
├── public/
└── assets/
```

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/username/Farooq2018-MEAN-FullStack-Web-App.git
   cd Farooq2018-MEAN-FullStack-Web-App
   ```

2. **Install dependencies for the server and admin app:**
   ```bash
   npm install
   cd app_admin
   npm install
   ```

## Running the Application

1. **Start the backend server:**
   ```bash
   npm start
   ```

2. **Start the frontend application:**
   ```bash
   cd app_admin
   ng serve
   ```

   Navigate to `http://localhost:4200/` in your browser to view the application.

## Features

- **Authentication:** Secure user login and registration.
- **Trip Management:** Add, edit, and view trips.
- **Responsive Design:** User-friendly interface for various devices.
- **RESTful API:** Backend API for handling data and business logic.

## Technologies Used

- **Frontend:** Angular, TypeScript
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Other Tools:** Passport.js for authentication, Mongoose for MongoDB object modeling, Karma for testing.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push your branch and create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Thank you for checking out this project. If you have any questions or need further assistance, please feel free to reach out!
