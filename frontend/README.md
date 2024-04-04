# React Shopping Cart

## Overview
This frontend part of the React Shopping Cart application showcases a dynamic user interface for adding products to a shopping cart. It provides real-time interaction and a responsive design, ensuring a seamless e-commerce experience.

## Features
- Real-time shopping cart updates.
- Responsive layout with Bootstrap.
- Navigation with React Router.

## Prerequisites
- [Node.js](https://nodejs.org/en/) installed on your system.

## Libraries Used
- React v17.0.2
- React DOM v17.0.2
- React Router v5.2.0
- React Bootstrap v1.6.0

## Installation

1. Clone the repository:
```git clone <https://github.com/Nerpassevera/MIT-shopping-cart>```

2. Navigate to the `frontend` directory where the `standalone.html` file is located.

3. Install `http-server` globally on your machine:
```npm install -g http-server```

    This will allow you to serve the application on a local web server.

## Running the Application

After the installation is complete, you can start the application using `http-server`:

1. In the terminal, ensure you are in the directory containing your `standalone.html` file.

2. Start the server with the following command:
```http-server```

    This will start a local web server and host your application.

3. Open a web browser and visit `http://localhost:8080`. This will open the `standalone.html` page, where you can interact with the React Shopping Cart.

    If you have another service running on port 8080, `http-server` will use the next available port.

## Usage

- Use the application to browse products and add them to your cart.
- The cart icon displays the current number of items in the cart.
- Modify the quantity or remove items as needed.

## Contributing

I encourage contributions! If you would like to contribute, please fork the repository and submit a pull request with your proposed changes.

## Acknowledgments

- This project utilizes a Strapi backend for product management.
- All product data is served dynamically via API requests.

## License

This project is available under the [MIT License](LICENSE).