# E-Commerce-Angular-DotNet
Full-stack e-commerce application built with Angular for the frontend and ASP.NET Core (.NET C#) for the backend

This repository contains a full-stack e-commerce application built with Angular for the frontend and ASP.NET Core (.NET C#) for the backend. It offers features like:

1. Authorization and Authentication: Secure user access with defined roles (Admin and User)
2. State Management: Efficient management of application state for a smooth user experience
3. Easy-to-Use User Interface: Intuitive design for user interaction
4. Product Management: Admins can manage product listings, categories, and details.
5. Shopping Cart and Checkout: Users can add items to their cart, proceed to checkout, and process orders (integration with a payment gateway would be required for actual payment processing).

Technologies Used:

1. Frontend: Angular
2. Backend: ASP.NET Core (.NET C#)

Setup Instructions:

Prerequisites:

1. Node.js and npm (or yarn) installed
2. .NET SDK installed (https://dotnet.microsoft.com/en-us/download)

Backend Setup:

1. Clone this repository.
2. Navigate to the backend directory (e.g., EComm_2).
3. Restore dependencies: dotnet restore
4. Build the backend project: dotnet build
5. Run the backend application (refer to project-specific instructions for the exact command).

Frontend Setup:

1. Navigate to the frontend directory (e.g., E-CommApp).
2. Install dependencies: npm install (or yarn install)
3. Build the Angular application: ng build (or follow project-specific build commands)
4. Run the development server: ng serve
