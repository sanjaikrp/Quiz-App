# Quiz App Project

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
The Quiz App Project is an interactive web application designed to create, manage, and take quizzes. It provides an engaging platform for users to test their knowledge on various topics and for administrators to create custom quizzes.

## Features
- User registration and authentication
- Create, edit, and delete quizzes
- Multiple choice questions with instant feedback
- Quiz timer and score tracking
- Responsive design for both desktop and mobile

## Technologies Used
- Frontend: HTML, CSS, JavaScript, React
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/sanjaikrp/Quiz-App.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Quiz-App
    ```
3. Install the frontend dependencies:
    ```sh
    cd client
    npm install
    cd ..
    ```
4. Install the backend dependencies:
    ```sh
    npm install
    ```
5. Set up the environment variables:
    ```sh
    cp .env.example .env
    ```
6. Start the development servers:
    ```sh
    npm run dev
    ```

## Usage
1. Open your web browser and navigate to `http://localhost:3000` for the frontend.
2. Use the provided interface to register a new account or log in with an existing account.
3. Create new quizzes, answer questions, and view your scores.
