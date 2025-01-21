# E-PersonalCommerce
# E-PersonalCommerce

## Description
E-PersonalCommerce is a project that consists of a client-side application and a server-side application. The client is built using modern JavaScript frameworks, while the server handles API requests and data management.

## Client Directory
- **eslint.config.js**: Configuration file for ESLint, a tool for identifying and reporting on patterns in JavaScript.
- **index.html**: The main HTML file that serves as the entry point for the client application.
- **jsconfig.json**: Configuration file for JavaScript projects, providing IntelliSense and other features in editors.
- **package-lock.json**: Automatically generated file that locks the versions of dependencies installed in the project.
- **package.json**: Contains metadata about the project and lists dependencies, scripts, and other configurations.
- **README.md**: Documentation file for the client-side application.
- **vite.config.js**: Configuration file for Vite, a build tool and development server.
- **public/**: Directory containing static assets.
  - **vite.svg**: Logo or image used in the application.
- **src/**: Source directory containing the main application code.
  - **App.jsx**: Main application component.
  - **main.jsx**: Entry point for the React application.
  - **assets/**: Directory for static assets like images.
    - **react.svg**: React logo.
  - **components/**: Directory for reusable components.
    - **Navbar.jsx**: Navigation bar component.
    - **ProductCard.jsx**: Component for displaying product information.
    - **ui/**: Directory for UI components.
      - Various UI components like buttons, checkboxes, dialogs, etc.
  - **pages/**: Directory for page components.
    - **CreatePage.jsx**: Component for creating new items.
    - **HomePage.jsx**: Component for the home page.
  - **store/**: Directory for state management.
    - **product.js**: State management for products.

## Server Directory
- **server.js**: Main entry point for the server application.
- **config/**: Directory for configuration files.
  - **db.js**: Database configuration and connection setup.
- **controllers/**: Directory for request handling logic.
  - **product.controller.js**: Controller for handling product-related requests.
- **models/**: Directory for data models.
  - **product.js**: Model representing product data structure.
- **routes/**: Directory for defining API routes.
  - **product.routes.js**: Routes for handling product-related API requests.
