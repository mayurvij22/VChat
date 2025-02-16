# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:


- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
#   V C h a t 
 
 markdown

# My React Video Call App

This project is a React-based web application that allows users to join video call rooms using [ZegoUIKitPrebuilt](https://www.zegocloud.com/). Users can enter a room ID on the home page and be redirected to a video call room.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name

    Install dependencies:

    bash

npm install

Set up environment variables:

Create a .env file in the root of your project and add the following environment variables:

plaintext

    VITE_APP_ID=your_app_id
    VITE_SERVER_SECRET=your_server_secret

    Replace your_app_id and your_server_secret with your actual Zego Cloud App ID and Server Secret.

Usage

    Start the development server:

    bash

npm run dev

Open your browser and navigate to:

arduino

    http://localhost:5173

    Enter a Room ID on the home page and join the room.

Environment Variables

    VITE_APP_ID: Your Zego Cloud App ID.
    VITE_SERVER_SECRET: Your Zego Cloud Server Secret.

Features

    Video Call: Join video call rooms using a unique Room ID.
    React Router: Navigate between different pages in the app.
    ZegoUIKitPrebuilt Integration: Easily implement video call functionality.

Contributing

Contributions are welcome! Please follow these steps to contribute:

    Fork the repository.
    Create a new branch: git checkout -b feature/your-feature-name.
    Make your changes and commit them: git commit -m 'Add some feature'.
    Push to the branch: git push origin feature/your-feature-name.
    Submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for more information.
