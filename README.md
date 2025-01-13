# Instructions

## Build

dotnet build

## Run

dotnet

## Tutorial

https://www.youtube.com/watch?v=RBVIclt4sOo

# My Blazor Website

This is a Blazor web application project that demonstrates the use of Blazor components and routing.

## Project Structure

- **Pages**: Contains the main pages of the application.
  - `Index.razor`: The main landing page of the application.
  - `_Host.cshtml`: The host page that sets up the HTML structure.
- **Shared**: Contains shared components.

  - `MainLayout.razor`: The main layout component for consistent page structure.

- **wwwroot**: Contains static files.

  - **css**: Contains stylesheets.
    - `site.css`: CSS styles for the application.
  - **js**: Contains JavaScript files.
    - `site.js`: JavaScript code for interactivity.

- **App.razor**: The root component that sets up routing and layout.

- **Program.cs**: The entry point for the application, configuring hosting and services.

- **Startup.cs**: Configures application services and middleware.

- **my-blazor-website.csproj**: Project file containing dependencies and build settings.

## Setup Instructions

1. Clone the repository.
2. Navigate to the project directory.
3. Run the application using the command:
   ```
   dotnet run
   ```
4. Open your browser and navigate to `http://localhost:5000` to view the application.

## Overview

This Blazor application serves as a template for building interactive web applications using C#. It leverages components for modularity and reusability, making it easy to maintain and extend.
