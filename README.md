# Dynamic Welcome Page with Express and EJS

This project demonstrates a simple Express.js application that renders a dynamic welcome page using EJS as the view engine. It personalizes the message based on the user's name and the time of day.

## Features

- **Dynamic Greeting**: The page greets the user based on the current time of day:
  - "Good morning" for hours before noon
  - "Good afternoon" for hours before 6 PM
  - "Good evening" for hours after 6 PM
- **User Personalization**: The user's name is passed dynamically from the server and displayed in the welcome message.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/dynamic-welcome.git
    cd dynamic-welcome
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

## Running the Application

1. Start the server:
    ```bash
    node app.js
    ```

2. Open your browser and navigate to:
    ```
    http://localhost:3000/welcome
    ```

You should see a dynamic greeting message like:
