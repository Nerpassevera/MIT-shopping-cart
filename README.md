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

This application consists of two main parts: the frontend (React application) and the backend (Strapi server). Follow the steps below to set up both components on your local machine.

### Backend (Strapi)

1. Clone the repository and navigate to the `backend` directory:


```
git clone <repository-url>
cd backend
```


2. Install the required node modules:

```
npm install
```


### Frontend (React)

1. From the root of the repository, navigate to the `frontend` directory:
```
cd ../frontend
```


2. If you haven't done so already, install `http-server` globally on your machine to serve the frontend application:
```
npm install -g http-server
```

## Running the Application

Once you've installed all the necessary dependencies for both the frontend and backend, you're ready to run the application.

### Starting the Backend

1. Ensure you are in the `backend` directory, then start the Strapi server:
```
npm run develop
```


Strapi will start in development mode on `http://localhost:1337`.

2. Open a browser and navigate to `http://localhost:1337/admin` to access the Strapi admin panel. You may need to set up an admin user if it's your first time running Strapi.

### Starting the Frontend

1. Open a new terminal window and navigate to the `frontend` directory.

2. Start the frontend application using `http-server`:
```
http-server
```

This command will serve your frontend on `http://localhost:8080`.

3. Open your browser and go to `http://localhost:8080` to interact with the React Shopping Cart.

Make sure both servers are running; the frontend will make API requests to the backend Strapi server to retrieve and manage the product data.

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