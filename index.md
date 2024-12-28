<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Projects</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .project {
            background: #fff;
            border-radius: 8px;
            margin: 20px 0;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .project h2 {
            margin: 0 0 10px;
            color: #444;
        }
        .project p {
            margin: 10px 0;
            line-height: 1.6;
        }
        .project a {
            color: #007bff;
            text-decoration: none;
        }
        .project a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
        @media (max-width: 600px) {
            main {
                padding: 0 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>My Projects</h1>
    </header>
    <main>
        <div class="project">
            <h2>Predictive Model: Recipe Predictor</h2>
            <p>Developed a binary classification model to predict user-recipe interactions, utilizing a dataset of 700k interactions from Food.com and achieving 79% accuracy on test sets.</p>
            <a href="https://github.com/vbommisetty/Recipes/tree/hieu" target="_blank">View Project</a>
        </div>

        <div class="project">
            <h2>MicroProcessor Design</h2>
            <p>Designed a single-cycle 16-bit processor using Verilog, optimized for converting binary digits to IEEE 754 floating-point numbers, validated through simulations.</p>
            <a href="https://drive.google.com/drive/folders/18Khfl8ZVJOYSTMF3cZRsw2CBal0rsJ?usp=sharing" target="_blank">View Documentation</a>
        </div>

        <div class="project">
            <h2>Alarm Clock Digital Design</h2>
            <p>Created a fully functional alarm clock using LogicWorks, integrating RTL circuits and FSMs for user-interactive clock and alarm settings.</p>
            <a href="https://github.com/rli128/AlarmClock" target="_blank">View Project</a>
        </div>

        <div class="project">
            <h2>SHA-256 RTL Model</h2>
            <p>Implemented a secure hashing algorithm using SystemVerilog with FSM design, tested for compliance with cryptographic standards and efficiency under varying conditions.</p>
            <a href="https://github.com/rli128/SHA-256" target="_blank">View Project</a>
        </div>

        <div class="project">
            <h2>DevSurf</h2>
            <p>Developed a developer journal web app with CI/CD pipelines, Node.js backend, SQLite database, and E2E testing with Puppeteer.</p>
            <a href="https://github.com/cse110-sp24-group29/cse110-sp24-group29" target="_blank">View Project</a>
        </div>

        <div class="project">
            <h2>Gym Script</h2>
            <p>Automated gym guest form filling using Puppeteer, interacting with DOM elements for efficient data entry.</p>
            <a href="https://github.com/rli128/Golds-Script" target="_blank">View Project</a>
        </div>

        <div class="project">
            <h2>Huffman File Encoding</h2>
            <p>Developed a C++ tool for lossless file compression, implementing Huffman algorithms to compress files up to 500MB.</p>
            <a href="https://github.com/rli128/Huffman" target="_blank">View Project</a>
        </div>

        <div class="project">
            <h2>Malloc and Free</h2>
            <p>Created a C library for dynamic memory allocation with a simulated heap, using bit arithmetic and a best-fit policy.</p>
            <a href="https://github.com/rli128/malloc" target="_blank">View Project</a>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>