# **Tactical-Tiles**  ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)



## Overview

Welcome to the MERN Chess Application! This project showcases our collaborative skills and coding abilities in building a scalable, user-focused single-page application using the MERN stack. This project is a fun way for us to express our love for coding and give back to the chess community and hobbyists alike. The application integrates real-world data and provides an engaging platform for chess enthusiasts to play and improve their skills.

<img width="1914" alt="Screenshot 2024-07-17 at 04 12 31" src="https://github.com/user-attachments/assets/330ad879-c1ec-4764-b6d9-80f8f158767b">

<img width="1918" alt="Screenshot 2024-07-17 at 04 12 17" src="https://github.com/user-attachments/assets/75a3dcb7-4c7b-4a44-8e8a-e7d35eb9d333">

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [App](#app)
- [Questions](#questions)

## Features

- **User Authentication**: Secure sign-up and login functionality using JWT.
- **Real-Time Gameplay**: Users can play chess games in real-time with live updates.
- **Game History**: Users can view their past games and track their progress.
- **Responsive Design**: The app is fully responsive and works on all device sizes.
- **Interactive UI**: The interface is polished and interactive, providing a smooth user experience.
- **Data Protection**: Sensitive information, such as API keys, is securely handled on the server side.

### Technologies Used

- **Front End:**
- `React.js`

- **Back End:**
- `Node.js` `Express.js`

- **Database:**
- `MongoDb` `Mongoose ODM`

- **APIs:**
- `GraphQL for quieries and mutations`

## **Deployment:**
  
- This application is deployed on [Render](https://tactical-tiles.onrender.com/)

## Installation

To install this application locally:

1. Clone the repository

```
git clone https://github.com/AliyusUnderwood/Tactical-Tiles.git
```

2. Navigate into the project directory file
   
```
cd Tactical-Tiles
```

3. Install dependencies, both in the server side and the client side of the application, and then navigate back to the root level for deployment.

```
npm install

cd client

npm install

cd ...

```

4. You will need to create an .env file, at the root or server directory, and add your MONGODB_URI:

```
In the `.env` file: MONGODB_URI=your_mongodb_uri
```

**Set up environment variables:**

- Create a `.env` file in the root directory and add the necessary environment variables, and a `JWT_SECRET`, if applicable:

```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

**Start the development server:**
```
npm run dev
```

## Usage

- After completing the installation steps, you can start using the application by visiting `http://localhost:3000` in your web browser.
- You will need to sign in with an email, password, and pick a username that you like! This will enable you to come back to a game that you havent finished. 
- From there, you are free to enjoy playing chess! 

## Contributing

We welcome contributions to the MERN Chess Application! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. Follow these steps to contribute:

- **Fork the repository.**
- **Create a new branch:** `git checkout -b feature/your-feature-name`
- **Commit your changes:** `git commit -m 'Add some feature'`
- **Push to the branch:** `git push origin feature/your-feature-name`
- **Open a pull request.**

We would love to introduce the ability to play peer-to-peer, and make it even more personable with a video-relay service, that way you can talk that talk, as you walk your walk. 

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/AliyusUnderwood/Tactical-Tiles/blob/main/LICENSE) file for details. 

## App
https://tactical-tiles-19d538a6e28a.herokuapp.com/

## Questions and Contributors

This project relies on the Node.js ecosystem, and we greatfully thank the developers of these libraries for their contributions to the open-source community! 

To reach out to any of the trusty collaborators on this project:

- [Aliyus Underwood on GitHub](https://github.com/AliyusUnderwood)
- [Jake Pearson on GitHub](https://github.com/jakepears)
- [Joseph Collins on GitHub](https://github.com/collinsjosephj)
- [Efrain Ruiz on GitHub](https://github.com/efrainrf)



