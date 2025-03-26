# ImageGen-SaaS

A full stack Image generation SaaS App using React.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [API Endpoints](#api-endpoints)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Introduction

ImageGen-SaaS is a full stack application designed to generate images based on user inputs. This project leverages the power of React for the frontend and a robust backend to handle image generation and user management.

## Features

- User authentication and authorization
- Image generation based on user input
- Responsive design
- Real-time updates
- RESTful API for image generation

## Technologies Used

- **Frontend:**
  - React
  - JavaScript
  - HTML/CSS

- **Backend:**
  - Node.js
  - Express.js

- **Database:**
  - MongoDB

- **Other:**
  - JWT for authentication
  - Cloud services for image storage

## Installation

To get a local copy up and running follow these simple steps.

### Prerequisites

- Node.js (>=14.x)
- npm (>=6.x)
- MongoDB

### Clone the repo

```bash
git clone https://github.com/wittyicon29/ImageGen-SaaS.git
cd ImageGen-SaaS
```

### Install NPM packages

```bash
npm install
```

### Set up environment variables

Create a `.env` file in the root directory and add the following:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
```

### Run the app

```bash
npm start
```

## Usage

1. Open your browser and go to `http://localhost:3000`.
2. Create an account or log in.
3. Use the image generation form to create images.

## Project Structure

```plaintext
ImageGen-SaaS/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.js
│   └── package.json
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
├── .env
├── .gitignore
└── README.md
```

### Explanation

- `client/` - Contains the React frontend.
  - `public/` - Public assets.
  - `src/` - Source code.
    - `components/` - Reusable React components.
    - `pages/` - Different pages of the application.
    - `App.js` - Main app component.
    - `index.js` - Entry point of the React app.
- `server/` - Contains the backend code.
  - `config/` - Configuration files.
  - `controllers/` - Logic for handling requests.
  - `models/` - Database models.
  - `routes/` - API routes.
  - `server.js` - Main server file.
- `.env` - Environment variables.
- `.gitignore` - Git ignore file.
- `README.md` - This README file.

## API Endpoints

### Authentication

- `POST /api/auth/register` - Register a new user.
- `POST /api/auth/login` - Log in a user.

### Image Generation

- `POST /api/images/generate` - Generate a new image.
- `GET /api/images` - Get all generated images.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
