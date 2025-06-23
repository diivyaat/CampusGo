# CampusGo

CampusGo is a dynamic platform designed to streamline university club operations and boost student involvement. It empowers campus communities by simplifying the management of clubs, events, and student enrollments, while also offering seamless payment integration through Razorpay.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

--Secure user sign-up and login for personalized access
-Comprehensive club oversight with streamlined management tools
-Seamless event creation and organization for smooth planning
-Easy student enrollment into clubs and events in just a few clicks
-Integrated Razorpay support for hassle-free payments
-Role-specific access controls ensuring the right permissions for admins and members

## Tech Stack

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
- **Frontend:**
  - React
  - Tailwind CSS
  - Axios
- **Payment Processing:**
  - Razorpay

## Installation

To get started with CampusGo, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/PorePranav/CampusGo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd CampusGo
   ```

3. Install the backend dependencies:

   ```bash
   cd server
   npm install
   ```

4. Install the frontend dependencies:

   ```bash
   cd ../client
   npm install
   ```

5. Set up environment variables:

   Create proper `.env` file in the `client` and `config.env` in the `server` directories and add your configuration

6. Run the backend server:

   ```bash
   cd ../server
   npm run dev
   ```

7. In a new terminal, run the frontend development server:

   ```bash
   cd ../client
   npm run dev
   ```

## Usage

After starting the application, you can access the frontend at `http://localhost:3000`.

- Register as a student or admin
- Manage clubs and events through the dashboard
- Participate in various club activities and events

## Contributing

I welcome contributions to CampusGo! Please read [CONTRIBUTING.md](CONTRIBUTING.md) file for details on the process for submitting pull requests.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
