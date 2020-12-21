# Team_Profile_Generator

# Description

This application serves as a tool that takes in various user information to generate a profile card for each member of your team, which is also color-coded by the employee's role and then displayed on a simple HTML webpage. The app takes the user information from a command line interface, and asks questions specific to the role that is chosen on the first prompt. When the user chooses the command 'No more employees', this function will cease and the application will produce a team.html file with all of the included profiles. This gives the user easy access to information about each member on their roster.

# Installation

To install the application you must first install node.js. You can click here to navigate to the Node.js download page. After installing node, you must also install the required npm packages. To do so, navigate to the applications file path in the terminal and type "npm i" or "npm i inquirer" to install the required inquirer modules. The application also is packaged with various unit tests to ensure functionality. If you would like to run the unit tests, navigate to the applications file path in the terminal and type "npm i" or "npm i jest" to install the required inquirer modules. To run the tests in the command line type "npm run test".

# Screenshots

The application kicks off with a prompt from the command line interface, asking the user to specify which role the first employee they want to add has. Then the user will fill in information specific to that role, as well as some general information about the employee.After the user has completed filling out their roster, they will select the 'No more employees' option, which terminates the function.

<img width="613" alt="user_input" src="https://user-images.githubusercontent.com/72167504/102740076-84b82680-4314-11eb-8eb5-c88ceedb2e35.png">

The application then produces an HTML file that has a profile card for each member of their team!

<img width="1776" alt="HTML" src="https://user-images.githubusercontent.com/72167504/102740158-c517a480-4314-11eb-8566-af4064e9ef6f.png">

# Testing
This program was build using class syntax and constructor functions. The function for each employee type was tested before building out the rest of the program.

<img width="453" alt="Test" src="https://user-images.githubusercontent.com/72167504/102740347-2b042c00-4315-11eb-81eb-9102a666a0e4.png">

# Technology

HTML
Bootstrap CSS
NodeJS
ES6
inquirer
path

# License

MIT License

Copyright (c) [2020] [Pritesh Patel]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) [2020] [Pritesh Patel]