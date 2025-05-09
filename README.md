# BeautyCode

## Introduction
BeautyCode is a powerful code optimization plugin designed for Visual Studio Code, aimed at enhancing the coding experience for developers. Built with a Python FastAPI backend and a JavaScript frontend, BeautyCode provides intelligent suggestions, performance scoring, and constructive feedback to help developers write cleaner, more efficient code. The plugin also features an AI-powered chatbot that offers real-time assistance directly within the VSCode environment, eliminating the need to switch between tools.

## Getting Started

### Installation Process
To install BeautyCode, follow these steps:

1. Install the backend dependencies:
    ```bash
    cd BeautyCode-backend
    pip install -r requirements.txt

2. Install the extension dependencies:
    ```bash
    cd BeautyCode-extension
    npm install

3. Start the backend server:
    ```bash
    uvicorn app.run:app --reload

4. Load the extension in VSCode:
    -Open the Extensions view (Ctrl+Shift+X).
    -Click on the three dots in the top right corner and select "Install from VSIX..." to load your extension.

### Software Dependencies
* Python 3.x
* FastAPI
* Uvicorn
* Node.js
* npm
