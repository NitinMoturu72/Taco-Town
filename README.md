# Taco-Town 🌮

Welcome to the Taco Town repository! This project is a simple web application that allows users to explore different taco recipes by selecting their favorite taco ingredients. The app uses Express.js and EJS templating to dynamically render the recipe details based on user input. The project was completed as part of a web development course on Udemy.

Project Structure

index.js: The main server file that sets up the Express server, handles routing, and processes user input.
views/index.ejs: The EJS template that renders the main page of the application, displaying taco options and recipe details.
public/styles/main.css: The stylesheet for the application, providing basic styling for the webpage.

Getting Started

Prerequisites
Node.js
npm (Node Package Manager)

Installation
Clone the repository
Navigate to the project directory
Install the dependencies: npm i
Running the Application: node index.js
Open your browser and navigate to http://localhost:3000.

Usage
On the main page, you will see three buttons representing different taco options: Chicken, Beef, and Fish.
Click on any button to view the ingredients and preparation details for the selected taco recipe.

Project Details
index.js
This file sets up the Express server and defines the routes for the application.
GET /: Renders the main page with the taco options and recipe details.
POST /recipe: Processes the user input and selects the appropriate taco recipe based on the chosen option.

index.ejs
This template file dynamically renders the recipe details based on the data received from the server.
Displays the taco options as buttons.
Shows the selected recipe details including ingredients and preparation method.

Main.css
This stylesheet provides basic styling for the webpage, including background color and layout adjustments.

Enjoy your taco-making experience with Taco Town! 🌮
