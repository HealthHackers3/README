CellVerse - Our Cell Image Database Project for Software Engineering for Biomedical Engineer

Project Overview
This project is a cell image database designed to facilitate the analysis and management of biological images. The system provides an intuitive user interface, central database, and tools for image processing and user tracking. It aims to simplify workflows for researchers and professionals working with large-scale cell image datasets, especially catered to people who have a nonbiological background.

Steps to Run the Project:

Please make sure you have the following installed on your system:
- Node.js and WebStorm(for the Electron frontend)
- ?? (for backend servlets)
- ??(for the database)
Then clone all required repositories.

Here is an overview of the active repositories:

DatabaseServlet-
The Java Database Servlet is a backend service for managing database operations in the Cell Image Database project. It connects to a PostgreSQL database, executes SQL queries dynamically via HTTP requests, and processes results into JSON format for frontend integration.

Key Features:
- Database connectivity using environment variables for security.
- Dynamic SQL execution, supporting query execution (e.g., SELECT) and updates (e.g., INSERT, UPDATE).
- JSON transformation of query results using Gson.
- Error handling with clear feedback for SQL issues.

Electron-Frontend-
The Electron-Frontend is the graphical user interface for the Cell Image Database project, built with Electron and React. It provides a cross-platform desktop application for interacting with the database and performing image analysis.

Key Features:
- Electron ensures cross-platform compatibility.
- React provides a dynamic and responsive interface.
- Retry mechanism connects to the React development server.
- Development tools are preloaded for debugging.

APIs-
The API layer provides endpoints for managing users, images, posts, and searches within the Cell Image Database. It ensures secure and efficient communication between the frontend and backend.

Key Features :
- Register and log in users with cookie-based credentials.
- Upload, retrieve, and manage image properties.
- Create, update, and retrieve post data.
- Manage usernames, emails, and account creation dates.
- Perform queries for images and metadata.

HHDb_Manager-
HHDb_Manager is for managing the database in the Cell Image Database project. It provides a user-friendly way to interact with and manage database tables, making administrative tasks efficient and accessible.

Key Features
- 

