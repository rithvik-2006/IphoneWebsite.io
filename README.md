
# iPhone Website

This is a 3D interactive iPhone website built with **Vite**, **React**, and **Three.js**. The project showcases a virtual 3D model of an iPhone, allowing users to explore its design with smooth interactions and animations.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [License](#license)

## Features

- **3D iPhone Model**: Explore a realistic 3D iPhone model using Three.js.
- **Interactive Animations**: Smooth and engaging animations for rotating, zooming, and interacting with the 3D model.
- **Optimized Performance**: Built using Vite for lightning-fast development and optimized build times.
- **Responsive Design**: Adapts to different screen sizes for a seamless experience on desktop and mobile.

## Technologies Used

- **Vite**: A blazing fast frontend build tool for modern web development.
- **React**: A JavaScript library for building user interfaces.
- **Three.js**: A powerful library for rendering 3D graphics in the browser using WebGL.
- **React-Three-Fiber**: A React renderer for Three.js, making it easier to work with 3D in React.

## Installation

Follow these steps to run the project locally:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/iphone-website.git
   cd iphone-website
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Development Server**

   ```bash
   npm run dev
   ```

   Vite will start a development server. Visit `http://localhost:3000` to view the project.

4. **Build for Production**

   To create a production build:

   ```bash
   npm run build
   ```

   This will generate an optimized build in the `dist` folder.

## Usage

Once you have the project running, you can interact with the 3D iPhone model on the homepage. Use the mouse or touch to rotate, zoom, and explore the details of the iPhone.

### Commands

- `npm run dev`: Start the development server.
- `npm run build`: Create a production build.
- `npm run preview`: Preview the production build.

## Folder Structure

```
iphone-website/
├── public/             # Public assets (e.g., favicon, 3D models)
├── src/
│   ├── assets/         # Static images and media
│   ├── components/     # React components
│   ├── scenes/         # Three.js scenes and related logic
│   ├── App.jsx         # Main App component
│   └── main.jsx        # Entry point
├── package.json        # Project metadata and dependencies
├── vite.config.js      # Vite configuration
└── README.md           # This file
```

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.






