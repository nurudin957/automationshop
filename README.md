<<<<<<< HEAD


## Clone Repository

1.- Open Your terminal and go to the folder where you want to clone the project, after that you are in your root directory, write down this command on the terminal "git clone https://github.com/nurudin957/automationshop", this will download the project into your local machine.

## Download WebDrivers / 

2.- Download the webdrivers, and put them in to the folder where it's the package.json file.

URL: https://www.npmjs.com/package/selenium-webdriver

## Install dependencies

3.- In your terminal, in the root directory of the project that you recently clone, where is you package.json. Run the following command 'npm install' to install the dependencies.

## Run server

4.- After install all your dependencies, you are ready to start the server. Run the following command 'npm run dev'. This script you can find it on the package.json file in the script property. this will create a server runnig on port: 3000.

## Open Postman

5.- Open your postman and use a get request in the following endpoints.

- http://localhost:3000/ // OPEN THE PAGE with Nodejs, selenium and Postman
- http://localhost:3000/login // Login Test with Nodejs, selenium and Postman
- http://localhost:3000/register // Register Test with Nodejs, selenium and Postman
- http://localhost:3000/logout // Logout Test with Nodejs, selenium and Postman

- http://localhost:3000/index/products // WebScrapping from index Page with cheerio & axios
- http://localhost:3000/index/slider // WebScrapping from index Page with cheerio & axios
- http://localhost:3000/index/banner // WebScrapping from index Page with cheerio & axios
- http://localhost:3000/index/footer // WebScrapping from index Page with cheerio & axios

## Raw data

URL: http://automationpractice.com/index.php
LOGIN: http://automationpractice.com/index.php?controller=authentication&back=my-account

1.-) Login, Raw data object:
Example: {"username":"nurudinproject.com","password":"123456789"}

2.-) Register, Raw data object:
Example: {
"username":"ahmedgmailemail@gmail.com",
"password":"1234567890",
"gender": "male",
"firstname": " Javier",
"lastname": "Movie",
"days":"30",
"months":"May",
"years":"1991",
"company":"project",
"address1":"1234 atyp road , Minneapolis",
"address2":"Los Angles, Los angles",
"city":"Los Angles",
"state":"Alabama",
"postcode":"00283",
"aditional":"best site!!",
"phone":"9524654121",
"mobilephone":"9654654121",
"alias":"nurudin"
}

