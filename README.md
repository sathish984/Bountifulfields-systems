Bountifulfields-system
To set up your development environment with Java JDK 1.7, Spring Boot, Node.js, Angular, and MySQL, and to create a project with a Spring Boot backend and an Angular frontend, follow these step-by-step instructions:

Install Java JDK 1.7:

Download and install Java JDK 1.7 from the Oracle website or an appropriate source for your operating system.
Set the JAVA_HOME environment variable to the JDK installation path.
Install Spring Boot:

Download Spring Boot from the official website or use a build tool like Maven or Gradle to include it in your project.
Create a Spring Boot project or import an existing one into your development environment.
Install Node.js:

Download and install Node.js from the official website.
Verify the installation by running node -v and npm -v in your command prompt or terminal.
Install Angular:

Open a command prompt or terminal and run the following command to install Angular CLI globally:
npm install -g @angular/cli
Verify the installation by running ng --version.
Install MySQL:

Download and install MySQL from the official website or use a package manager appropriate for your OS.
During installation, set the MySQL server to run on port 3306.
Create Folders:

Create two separate folders for your Spring Boot backend and Angular frontend projects.
Project Setup:

Copy your Spring Boot project files into the Spring Boot folder.
Copy your Angular project files into the Angular folder.
Create MySQL Database:

Open a MySQL client (e.g., MySQL Workbench or command line).
Log in with appropriate credentials.
Create a new database named bountifulfieldsdatabase using the following SQL command:
CREATE DATABASE bountifulfieldsdatabase;
Connect Frontend and Backend:

In your Angular project, configure the API endpoints to connect to the Spring Boot backend running on a specific port (usually 8080).
Ensure that your Angular app sends HTTP requests to the correct endpoints on your Spring Boot server.
Admin Page Login:

In your Spring Boot application, create an API or controller for handling user authentication.
Store user login details (email and password) in a MySQL table.
Implement a secure login mechanism using technologies like Spring Security.
In your Angular frontend, create an admin login page that sends a POST request to the Spring Boot backend for authentication.
Upon successful login, provide access to the admin page.
Running the Project:
Start your Spring Boot application on port 8080.
Run your Angular application using the Angular CLI (ng serve) on a different port (e.g., 4200).
Access the frontend at http://localhost:4200 and the backend at http://localhost:8080.
Ensure that all dependencies are correctly installed, and your project files are structured appropriately to make this setup work seamlessly.
