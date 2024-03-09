# Dynamic-routes-models-file System to store data 

# Project Name

Brief description of your project.

## Dependencies

The following packages are used in this project:

- **Express**: The web framework for Node.js.
- **EJS**: A templating engine for Node.js.
- **Body Parser**: Middleware to parse incoming request bodies.
- **Nodemon**: Development server for automatically restarting the Node.js server when changes are made.

## Project Structure

- **app.js**: The main entry point of the application.
- **package.json**: The configuration file containing metadata and dependencies.
- **views**: The folder containing the HTML templates.
  - **index.ejs**: The template to display the product details.
- **public**: The folder containing the static files.
  - **css**: The folder containing the CSS files.
    - **styles.css**: The stylesheet for the application.
- **data**: The folder containing the file system-based data store.
  - **products.json**: The JSON file to store product data.
- **models**: The folder containing the product model.
  - **product.js**: The product model handling data access and manipulation.
- **util**: The folder containing utility functions.
  - **util.js**: The utility functions for the application.

## Installation

To install the dependencies, use npm:

```bash
npm install
