# Spring Boot Basics - Task 1

## Project Description
This is the first part of the Spring Framework assignment for Vistula University. The goal of this task was to create a basic Spring Boot application, implement the first web controller, and handle static/dynamic content.

## Technologies Used
* Java 25
* Spring Boot 4.0.1
* Maven
* Thymeleaf (Template Engine)

## Key Features & Endpoints
1. **Plain Text Response (`/`)**:
    - Uses `@RestController` (or `@ResponseBody`) to return a simple string: "Hello Vistula, in my first Spring controller."
2. **Dynamic View (`/greeting`)**:
    - Uses `@Controller` to return a Thymeleaf template (`greeting.html`).
    - Accepts a request parameter `name` (default: "World").
    - Displays a custom message and a static image from the university.

## How to Run
1. Clone the repository.
2. Run `Task1Application.java`.
3. Open browser at `http://localhost:8080/greeting?`.

## Screenshots
> **Note to student:** Place your screenshot of the browser with the Vistula logo here.
![Task 1 Greeting Screen](screenshots/task1_result.png)