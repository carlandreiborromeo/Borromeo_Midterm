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
   ```
You should see version numbers for both `node` and `npm`.

## Step 2: Set Up a React Project

1. Open VS Code and Open the terminal in VS Code (click on View > Terminal).
2. Go to the folder where you want to create your project, or create a new one.
3. In the terminal, type the following command to create a new React app:
   ```bash
   npm create vite@latest
   ```

After that fill up the following that shows up:
   ```bash
   Project name:
   Select A Framework:
   Select A Variant:
   ```

Once it's done, run the following that appears on the terminal:
   ```bash
    cd my-react-app
    npm install
    npm run dev
   ```
the `my-react-app` is the name name or should be the name of your folder.

Open your browser and copy and paste the link on `local host` to see your new React app running!

## Project Folder Overview
Inside your project, you’ll see folders like these:

`public/`-Stores static files like `index.html`.<br>
`src/`-Contains JavaScript files and React components (like `App.js`).<br>
`node_modules/`-Contains installed packages.<br>

## Helpful Resources

[React Documentation](https://react.dev/blog/2023/03/16/introducing-react-dev){:target="_blank"}

[JavaScript Documentation](https://www.w3schools.com/js/){:target="_blank"}

[React Video Tutorial](https://www.youtube.com/watch?v=hn80mWvP-9g&list=PLZPZq0r_RZOMQArzyI32mVndGBZ3D99XQ){:target="_blank"}
