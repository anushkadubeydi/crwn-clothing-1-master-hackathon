# crwn-clothing-1-master-hacakthon
Description
"Crown Clothing" Crown Clothing Ltd. is an E-commerce Website where you can go and shop for clothing.

"Visuals"
desktop view
https://user-images.githubusercontent.com/47336885/88493158-aa1b5100-cf7d-11ea-8b99-3a073acd3dab.png

mobile view
https://user-images.githubusercontent.com/47336885/88493250-1c8c3100-cf7e-11ea-858b-9af4564d63c1.png

Technology Used
JavaScript, React, Redux, Redux-Saga, React Hooks, Express.js, Node.js, Material UI, HTML5, CSS3, Firebase, SCSS, Styled-Components, Git
JavaScript as the base developement language.
Server was built using Nodejs and Express.
Database was set using Firebase/ Firestore.
Redux used for state managemnet.
Stripe API used for payments.
SCSS used for styling the components.
Styled Components used in some components to style the application.
React Hooks used in the front-end to avoid using stateful components.
Jest used for Unit Testing.
Heroku was used to deploy the application.
Installation Guide
Steps to run in development mode
Fork the repo and clone it.
Make sure you have npm and Node.js installed in your system.
Check the libraries and packages needed from package.json file under the dependencies object.
In the terminal type npm install to install the packaged of the application.
Setup your Firebase account.
Setup your Stripe API account.
Open src/components/stripe-button/StripeCheckoutButton.js and replace the publishable key with your stripe publishable key.
Create .env file in src and put it in .gitignore. Now put your stripe screte key in .env file by creating a STRIPE_SECRET_KEY variable.
Run npm run dev to run server or and client side at the same time.
