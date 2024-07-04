# Full Stack ReactJS with Spring Boot (Contact)

A full-stack contact management application built with ReactJS for the frontend and Spring Boot for the backend. This project demonstrates the integration of a ReactJS frontend with a Spring Boot backend to handle contact management functionalities, including creating, reading, updating, and deleting contacts.

## Features

- **Backend (Spring Boot):**
  - Domain modeling and repository setup
  - Contact service layer for business logic
  - Data source configuration
  - API endpoints for CRUD operations
  - Comprehensive API testing

- **Frontend (ReactJS):**
  - Responsive UI components for contact management
  - Modal dialogs for adding and updating contacts
  - Toast notifications for user feedback
  - CORS configuration for backend communication
  - CRUD operations for contact management, including photo updates

## Technologies Used

- **Backend:** Spring Boot, MySQL
- **Frontend:** ReactJS, CSS
- **Others:** CORS, Toast Notifications

## Installation

### Backend

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd backend
   ```

2. Configure application properties:
   - Edit `src/main/resources/application.properties` to set up your database connection.

3. Build and run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React application:
   ```bash
   npm start
   ```

## Usage

- Access the application at `http://localhost:3000` for the frontend.
- The backend API is available at `http://localhost:8080/api/contacts`.

## API Endpoints

- `GET /api/contacts` - Retrieve all contacts
- `POST /api/contacts` - Create a new contact
- `GET /api/contacts/{id}` - Retrieve a specific contact
- `PUT /api/contacts/{id}` - Update an existing contact
- `DELETE /api/contacts/{id}` - Delete a contact

## Contributing

Feel free to fork the repository and submit pull requests. Contributions and feedback are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Spring Boot](https://spring.io/projects/spring-boot)
- [ReactJS](https://reactjs.org/)

