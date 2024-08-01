# Digital Banking Application

This project is a full-stack digital banking application with a Spring Boot backend and an Angular frontend.

## Project Structure

- Backend: Spring Boot application
- Frontend: Angular application

## Backend

### Technology Stack

- Java 17
- Spring Boot 3.2.5
- Maven

### Key Dependencies

- Spring Boot Starter Data JPA
- Spring Boot Starter Web
- H2 Database
- SpringDoc OpenAPI UI
- Lombok

### Build and Run (Backend)

1. Ensure Java 17 and Maven are installed.
2. Navigate to the backend directory.
3. Run: `mvn spring-boot:run`

### API Documentation

Available at `http://localhost:8080/swagger-ui.html` after starting the backend.

## Frontend

### Technology Stack

- Angular 17.3.0
- TypeScript
- RxJS
- ng-zorro-antd (Ant Design for Angular)

### Key Dependencies

- Angular core packages (v17.3.0)
- ng-zorro-antd (v17.4.1)
- RxJS

### Build and Run (Frontend)

1. Ensure Node.js and npm are installed.
2. Navigate to the frontend directory.
3. Run: `npm install`
4. Start the dev server: `ng serve`

## Running the Full Application

1. Start the backend server.
2. Start the frontend development server.
3. Access the application at `http://localhost:4200/`.

## Development

- Backend: Uses Spring Boot DevTools for automatic restarts and live reload.
- Frontend: Auto-reloads on file changes.

## Testing

- Backend: Run `mvn test` in the backend directory.
- Frontend: Run `ng test` in the frontend directory.

## Scripts

### Backend (Maven)

- `mvn spring-boot:run`: Run the application
- `mvn test`: Run tests
- `mvn package`: Build the project

### Frontend (npm)

- `ng serve`: Start the development server
- `ng build`: Build the project
- `ng test`: Run unit tests


## License

See the LICENSE.md file for details.