# E-Learning Platform

An e-learning platform built using **Java Spring Boot** for the backend and **Angular** for the frontend. This platform enables users to access educational content, take quizzes, track progress, and more.

## Features

- User authentication and authorization
- Course creation and management
- Video and resource hosting
- Progress tracking and analytics
- Quiz and assessment modules
- Responsive design for desktop and mobile

---

## Tech Stack

### Backend
- **Java Spring Boot**: REST API development
- **Spring Security**: User authentication and role-based access control
- **Hibernate/JPA**: Database interaction
- **MySQL**: Relational database

### Frontend
- **Angular**: Modern web application development
- **TypeScript**: Language for Angular development
- **Bootstrap**: Responsive design

---

## Requirements

- **Java 17** or later
- **Node.js 18.x** or later
- **Angular CLI**: Installed globally (`npm install -g @angular/cli`)
- **MySQL**: For database management

---

## Setup Instructions

### Backend (Spring Boot)

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/e-learning-platform.git
   cd e-learning-platform
   ```

2. Navigate to the `backend` folder:
   ```bash
   cd backend
   ```

3. Configure the database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/elearning
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

4. Build and run the backend:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend (Angular)

1. Navigate to the `frontend` folder:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the Angular development server:
   ```bash
   ng serve
   ```

4. Access the application at `http://localhost:4200`.

---

## Directory Structure

```
e-learning-platform/
├── backend/           # Spring Boot backend
│   ├── src/
│   ├── pom.xml
│   └── ...
├── frontend/          # Angular frontend
│   ├── src/
│   ├── angular.json
│   └── ...
└── README.md          # Project documentation
```

---

## Contributing

We welcome contributions! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push your branch and create a pull request:
   ```bash
   git push origin feature-name
   ```

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or feedback, feel free to contact the project maintainers:

- **Abdelrehman Elhaj**: [hdr333@gmail.com](mailto:your.email@example.com)
- **GitHub**: [AbdelrehmanElhaj](https://github.com/yourusername)

