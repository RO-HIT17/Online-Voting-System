# Voting Application

This is a **Spring Boot** project with a **Thymeleaf** frontend, built using **Spring Tool Suite (STS)**. The application allows users to vote for candidates and provides an admin interface to view vote details.

## Features

* **User Role**

  * Users can view candidates and cast their vote.
* **Admin Role**

  * Admin can view all vote details and manage the voting system.

## Technology Stack

* **Frontend**: Thymeleaf, CSS — for designing page layouts and user interface.
* **Backend**: Java — all business logic and application flow are implemented in Java.
* **Database**: MySQL — used to store users, candidates, and voting data.
* **Security**: Spring Security — for authentication and authorization.
* **ORM**: Hibernate — used for database operations and object-relational mapping.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
2. Import the project in **Spring Tool Suite (STS)**.
3. Configure **MySQL** database in `application.properties`.
4. Run the project as a **Spring Boot Application**.
5. Access the application at `http://localhost:8080`.

