# ProductsApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.0.

Description: An Angular with Web API Product Management Application is a full-stack project designed to manage product data using an Angular frontend with an ASP.NET Core Web API backend. This application enables users to perform CRUD operations on products, making it ideal for learning and implementing end-to-end product management in a web environment.

Key Features:
Product Catalog: Displays a list of products with relevant details such as ProductID, ProductName, Description, Price, Category, and Stock.
CRUD Operations:
Create: Add new products with all necessary fields.
Read: Retrieve product data from the Web API and display it in the Angular UI.
Update: Edit existing product details and save changes to the database.
Delete: Remove products, with optional confirmation dialogs for safety.
Search and Filter: Filter products by categories, price range, or search by name for easy browsing.
Pagination: Manage large product catalogs with paginated views.
Tech Stack:
Frontend:
Angular: For building a responsive, single-page application (SPA) with a dynamic user interface.
Angular Material or Bootstrap: For UI components and styling.
Angular Services: For handling HTTP requests to the backend using HttpClient.
Backend:
ASP.NET Core Web API: For building RESTful API endpoints to manage product data.
Entity Framework Core: For handling database interactions, including CRUD operations.
SQL Database: For storing product data.
Typical Workflow:
Frontend (Angular):

Product Service: Manages HTTP requests to the Web API (GET, POST, PUT, DELETE).
Product Components: Separate components for listing, adding, editing, and viewing products.
Routing: Configures navigation between different product pages.
Backend (Web API):

Controllers: Define endpoints such as /api/products for managing product resources.
Repository Pattern: Handles data access logic, separating it from the controller logic.
DTOs: Use Data Transfer Objects to ensure only necessary data is exchanged.
This project offers a comprehensive understanding of Angular and ASP.NET Core Web API integration, focusing on practical CRUD functionality, API communication, and frontend-backend data handling

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
