# Weather Interface

#### _JavaScript, 06.04.2019_

#### By _Reese Lee and Marc Davies_

## Description

* _This program returns weather information for a city._

## Specs
| Behavior | Input | Output |
| ------------- |:-------------:| -----:|
| If user enters a city, the program returns humidity and temperature information for that city | Portland | "The humidity in Portland is 51%. The temperature in Kelvins is 289.95." * |
_* Actual weather information may vary_

## Installation and Setup

_Cloning and setting up the application_

* If you don't have it installed, download and install Node.js 12.3.1
* `$ git clone https://github.com/MarcLignarius/weather-interface.git` This will clone the repository to your local machine.
* `$ npm install` This will allow you to have access to the CLI (command line interface) for webpack.
* `$ npm run build`
This will automatically build the bundle once. The entry file is `./src/script/index.js`, with production ready code (minified).
* `$ npm run start`
This will watch the file changes in `./src` and automatically build the bundle with dev build (not minified). This is a continuous monitoring which can be stopped with the key combination `Ctrl + C` within the terminal.

_Creating and Storing Your API key_

* Go to https://home.openweathermap.org/users/sign_in and create an account, or sign in.
* Go to https://home.openweathermap.org/api_keys, generate a new API key and copy it.
* `$ touch .env` in the top level directory to create a .env file.
* `$ atom .env` and add "API_KEY = Paste the API key here"
* Add the .env file to the .gitignore file

## Known Bugs
There are no known bugs as of last update.

## Support and contact details
_Please contact me at marcdaviesriot@gmail.com if you run into any issues or have questions, ideas or feedback._

## Technologies Used
This application was built in Atom using JavaScript, Node.js 12.3.1, jQuery 3.4.1, Bootstrap v4.3.1, a custom css file and API calls. For unit testing, Jasmine framework and Karma task runner are both used.

### License

*This software is licensed under MIT license.*

Copyright (c) 2019 **_Reese Lee, Marc Davies_**
