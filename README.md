
# BMI Calculator

A simple web application to calculate Body Mass Index (BMI). The application is built with Node.js and Express and allows users to enter their height and weight to receive their BMI and a categorization of their BMI value.

## Installation

To run this application, you will need Node.js and npm (Node Package Manager) installed on your system.

If you do not have Node.js and npm installed, download and install them from [nodejs.org](https://nodejs.org/).

Once Node.js and npm are installed, clone this repository to your local machine or download the source code.

Using your command line interface, navigate to the project directory and run the following command to install the required dependencies:

```bash
npm install
```

This command will install the following npm packages:

- `express`: A fast, unopinionated, minimalist web framework for Node.js.
- `body-parser`: A body parsing middleware used to parse the JSON, buffer, string, and URL-encoded data submitted using HTTP POST request.

## Running the Application

To start the server, run the following command in the root directory of the project:

```bash
npm start
```

This will start the Express server on port 3000. You can access the application by opening a web browser and navigating to `http://localhost:3000`.

## Dependencies

- Node.js
- npm
- Express (^4.17.1)
- Body-Parser (^1.19.0)

Make sure you have the required versions of Node.js and npm installed on your system to ensure compatibility with the npm packages used in this project.

## Server Details

The server is configured to run on port 3000. This can be modified in the `app.js` file if necessary, but you will need to update the port number in the following section of code:

```javascript
const port = 3000;
app.listen(port, () => {
  console.log(`Server running on port ${port}`);
});
```

If you change the port, remember to access the application using the new port number in your browser.
