# Vue Counter

This documentation explains the Vue Counter project, a simple web application built using Vue 3 and Vite. This application serves as a basic demonstration of reactivity and state management within the Vue ecosystem.

## Project Description

Vue Counter is a Single Page Application that features a basic counter. Users can interact with the application to increment or decrement the numerical value displayed on the screen. This application was developed to demonstrate the core functionality of Vue 3, specifically the use of the Composition API with `ref`.

## Features

- **Increment:** A button to increase the counter value.
- **Decrement:** A button to decrease the counter value.
- **Reactive Display:** The counter value updates instantly on the user interface as the user interacts with it.
- **Interactive Animations:** Includes custom styling and interactive pulse animations when buttons are pressed.

## Technologies Used

- **Vue 3:** A JavaScript framework for building user interfaces.
- **Vite:** A frontend build tool used for fast local compilation and serving.
- **Vanilla CSS:** Used for layout, colors, and custom component animations.

## Prerequisites

Before running this project, ensure your system has the following software installed:

- [Node.js](https://nodejs.org/) (LTS version recommended. According to `package.json`, Node.js ^22.18.0 or >=24.12.0 is required)
- `npm` (Node Package Manager), which is typically included with the Node.js installation.

## Installation

Follow these steps to set up the project in your local environment:

1. Open your terminal and ensure you are in the `vue-counter` project directory.
2. Run the following command to download and install all necessary dependencies:

```sh
npm install
```

## Running the Application (Development Mode)

To run the application in development mode with hot-reload support, use the following command:

```sh
npm run dev
```

Vite will start a local development server. The terminal will display the local URL (usually `http://localhost:5173/`). Open this URL in your web browser to view and interact with the application.

## Building for Production

If you want to prepare the application for deployment to a production server, run the following command:

```sh
npm run build
```

This command will compile and minify all code (HTML, CSS, JavaScript) and assets into a `dist` directory. This `dist` directory is what you will use for the deployment process.
