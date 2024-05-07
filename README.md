This is a simple authentication app built with Express.js. It demonstrates how to create a basic web server with Express, handle form data using body-parser, and implement simple authentication logic.

Features
Allows users to enter a password in a form
Validates the password
Grants access to a secret page if the correct password is entered

Technologies Used
Express.js: A minimal and flexible Node.js web application framework
body-parser: Middleware for parsing incoming request bodies
Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine

Getting Started
Prerequisites
Node.js installed on your local machine

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/express-authentication-app.git
Navigate to the project directory:
bash
Copy code
cd express-authentication-app
Install dependencies:
bash
Copy code
npm install
Usage
Start the server:
bash
Copy code
npm start
Open your web browser and go to http://localhost:3000
Enter the password in the form and submit
If the password is correct, you will be redirected to the secret page. Otherwise, you'll remain on the home page.
