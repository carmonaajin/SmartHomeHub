# SmartHomeHub

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview

SmartHomeHub is an intuitive and customizable dashboard designed to centralize the monitoring and control of your smart home devices. Whether you have lights, thermostats, or security cameras, SmartHomeHub integrates them all into a single, elegant interface.

## Features

- Unified control panel for multiple IoT devices
- Real-time device status updates
- Customizable dashboards
- Secure user authentication
- Mobile-friendly responsive design

## Tech Stack

- Frontend: React.js with Material-UI
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT
- Deployment: Docker

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/carmonaajin/SmartHomeHub.git
   cd SmartHomeHub
   ```

2. Install dependencies:

   ```bash
   npm install
   cd client && npm install
   ```

3. Create a `.env` file in the root directory and add your MongoDB URI and JWT secret:

   ```env
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

## Usage

Visit `http://localhost:3000` after running the development server. Register an account and start adding your smart home devices to the dashboard. Customize your views and manage device settings seamlessly.

## Screenshots

![Dashboard Placeholder](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

![Device Control Placeholder](https://via.placeholder.com/800x400?text=Device+Control+Screenshot)

## Contributing

Contributions are welcome!

1. Fork the repository on GitHub: [https://github.com/carmonaajin/SmartHomeHub](https://github.com/carmonaajin/SmartHomeHub)
2. Clone your fork:

   ```bash
   git clone https://github.com/carmonaajin/SmartHomeHub.git
   ```
3. Create a feature branch:

   ```bash
   git checkout -b feature/YourFeatureName
   ```
4. Commit your changes and push to your fork.
5. Open a Pull Request on the main repository.

Please ensure your code follows the existing style and passes all tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Author

Developed by [carmonaajin](https://github.com/carmonaajin)
