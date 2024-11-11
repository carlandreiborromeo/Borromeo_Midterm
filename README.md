<h1>Getting Started with React</h1>
    <p>This guide will walk you through setting up a basic React project.</p>
    <p><strong>Note:</strong> To follow along, you should be familiar with <strong>JavaScript</strong> and <strong>HTML</strong>.</p>

    <h2>What is React?</h2>
    <ul>
        <li><strong>Visual Studio Code (VS Code)</strong> - This is a code editor where you can write and organize your code.</li>
        <li><strong>Node.js</strong> - A JavaScript runtime that includes <code>npm</code> (Node Package Manager), which helps to install React and its dependencies.</li>
    </ul>

    <h2>Step 1: Install Node.js</h2>
    <ol>
        <li>Go to the <a href="https://nodejs.org/" target="_blank">Node.js website</a> and download the latest <strong>LTS version</strong> for your computer.</li>
        <li>Install Node.js, and to check if it’s installed correctly, open your terminal and run:</li>
    </ol>
    <pre><code>node -v
npm -v</code></pre>
    <p>You should see version numbers for both <code>node</code> and <code>npm</code>.</p>

    <h2>Step 2: Set Up a React Project</h2>
    <ol>
        <li>Open VS Code and Open the terminal in VS Code (click on View &gt; Terminal).</li>
        <li>Go to the folder where you want to create your project, or create a new one.</li>
        <li>In the terminal, type the following command to create a new React app:</li>
    </ol>
    <pre><code>npm create vite@latest</code></pre>
    <p>After that, fill up the following that shows up:</p>
    <pre><code>cd my-app</code></pre>
    <p>Once it's done, go to the project folder:</p>
    <pre><code>npm start</code></pre>
    <p>Open your browser and go to <code>http://localhost:3000</code> to see your new React app running!</p>

    <h2>Project Folder Overview</h2>
    <p>Inside your project, you’ll see folders like these:</p>
    <ul>
        <li><code>public/</code> - Stores static files like <code>index.html</code>.</li>
        <li><code>src/</code> - Contains JavaScript files and React components (like <code>App.js</code>).</li>
        <li><code>node_modules/</code> - Contains installed packages.</li>
    </ul>

    <h2>Helpful Resources</h2>
    <ul>
        <li><a href="https://react.dev/blog/2023/03/16/introducing-react-dev" target="_blank">React Documentation</a> – Great for learning more about React.</li>
        <li><a href="https://www.w3schools.com/js/" target="_blank">JavaScript Documentation</a> – Helpful for brushing up on JavaScript.</li>
        <li><a href="https://www.youtube.com/watch?v=hn80mWvP-9g&list=PLZPZq0r_RZOMQArzyI32mVndGBZ3D99XQ" target="_blank">React</a> – A live demonstration for learning and setting up React.</li>
    </ul>
