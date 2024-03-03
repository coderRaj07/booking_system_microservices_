# Microservices Application 🚀

Welcome to our microservices application! This application is built using Node.js and Sequelize for MySQL database interaction. We've divided our application into several microservices to make it more scalable and maintainable.

## Folder Structure 📁

- **config**: Contains configuration files for secrets and environment variables.
- **controllers**: Houses controllers responsible for calling service methods.
- **middleware**: Includes middleware functions used across services.
- **models**: Defines database schemas using Sequelize ORM.
- **repository**: Contains repository classes for interacting with the database.
- **routes**: Defines API routes for each microservice.
- **seeders**: Includes seed data for pre-populating the database during development.
- **utils**: Contains utility functions, including error validation codes.

## Microservices 🛠️

1. **Authentication Service**: Handles user authentication using JWT tokens.
2. **Flight Booking Service**: Manages flight bookings and reservations.
3. **Flight Search and Filter Service**: Provides functionality for searching and filtering flights based on criteria.
4. **Reminder Service**: Sends reminders to users about their upcoming flights and bookings.

## Technologies Used 💻

- **Node.js**: JavaScript runtime for building server-side applications.
- **Sequelize**: ORM for Node.js that supports MySQL and other databases.
- **Express.js**: Web application framework for Node.js used for defining API routes.
- **JWT**: JSON Web Tokens for user authentication and authorization.

## Getting Started 🚦

1. Clone this repository to your local machine.
2. Navigate to the root directory of each microservice (`auth-service`, `flight-booking-service`, `flight-search-service`, `reminder-service`) and follow the instructions in the respective `README.md` files for setup and configuration.
3. Once you've set up each microservice, you can proceed with initializing the database schema, starting the services, and using the application as described in their respective `README.md` files.

## Final Words 📝

Feel free to customize and extend this template according to your specific requirements and use cases.
Happy coding! 🚀
