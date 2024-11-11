# Cypress Demo Test

This repository contains Cypress automation test for [Saucedemo](https://www.saucedemo.com/v1/) website. The test cases are designed to cover and execute automation for positive, negative and exceptional usecases.

## Prerequisites

Before running the tests, ensure you have the following installed:

- **Node.js** (v12 or later)
- **npm** (comes with Node.js)
- **Cypress** (install via npm or yarn)
- **Git** (to clone the repository)

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Pooja-Gangavathi/cypress_demo_test.git
    ```
   Then change the directory,
   ```bash
   cd cypress_demo_test
   ```

3. **Install cypress:**

Install Cypress as a development dependency.
```bash
npm install cypress --save-dev
 ```

3. **Open Cypress Test Runner:**

   Use the following command to open Cypress's graphical interface to view and run tests interactively:

   ```bash
   npx cypress open
   ```
Follow the below steps to run the testcase by Cypress Runner,

1.*Select the Scaffold file in the project directory.*
2.*Select any of the browser when prompted by Cypress runner.*
3.*Select "Okay, I got" it to continue.*
4.*Choose the Login_Functionalty.cy.js file to run from the displayed list,Cypress will start running the test case automatically.*

4. **Alternatively, to run Tests in Headless Mode:**

To run tests in the terminal without opening the Cypress GUI.
Cypress generates reports for test results. To view them:

   ```bash
   npx cypress run
   ```
which will create test report of pass and fail test.

   
This README should guide you through setting up, running, and reporting on your tests in the `cypress_demo_test` repository.


Here is the link of detailed manual test case spreadsheet
https://docs.google.com/spreadsheets/d/18wGJq7SGkmcsyGDZTXrGYMIXauDDXMUftxEeY7p1Szc/edit?gid=0#gid=0
