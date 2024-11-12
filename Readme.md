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
   git clone https://github.com/Pooja-Gangavathi/cypress-assignment-oct.git
    ```
   Then change the directory,
   ```bash
   cd cypress-assignment-oct
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
 **Follow the below steps to run the testcase by Cypress Runner,**
 
- Step 1. **Select the Scaffold file in the project directory.**
- Step 2. **Select any of the browser when prompted by Cypress runner.**
- Step 3. **Select "Okay, I got" it to continue.**
- Step 4. **Choose the Login_Functionalty.cy.js file to run from the displayed list,Cypress will start running the test case automatically.**

4. **Alternatively, to run Tests in Headless Mode:**

Run the below code in the code editor, which will create test report of pass and fail test.

   ```bash
   npx cypress run
   ```


## Manual testcase spreadsheet
Here is the below link,
https://docs.google.com/spreadsheets/d/18wGJq7SGkmcsyGDZTXrGYMIXauDDXMUftxEeY7p1Szc/edit?gid=0#gid=0
