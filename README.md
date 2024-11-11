# Getting Started with React

This guide will walk you through setting up a basic React project. 

**Note:** To follow along, you should be familiar with **JavaScript** and **HTML**.

## What is React?

1. **Visual Studio Code (VS Code)** - This is a code editor where you can write and organize your code.
2. **Node.js** - A JavaScript runtime that includes `npm` (Node Package Manager), which helps to install React and its dependencies.

## Step 1: Install Node.js

1. Go to the [Node.js website](https://nodejs.org/) and download the latest **LTS version** for your computer.
2. Install Node.js, and to check if it’s installed correctly, open your terminal and run:
   ```bash
   node -v
   npm -v
You should see version numbers for both node and npm.

## Step 2: Set Up a React Project

1. Open VS Code and Open the terminal in VS Code (click on View > Terminal).
2. Go to the folder where you want to create your project, or create a new one.
3. In the terminal, type the following command to create a new React app:
   ```bash
npx create-react-app my-app
Replace `my-app` with whatever you want to name your project.

Once it's done, go to the project folder:
   ```bash
cd my-app

Start the React development server:
   ```bash
npm start
Open your browser and go to http://localhost:3000 to see your new React app running!

Project Folder Overview
Inside your project, you’ll see folders like these:

public/ - Stores static files like `index.html`.
src/ - Contains JavaScript files and React components (like `App.js`).
node_modules/ - Contains installed packages.
Helpful Resources
React Documentation - Great for learning more about React.
JavaScript Documentation - Helpful for brushing up on JavaScript.
