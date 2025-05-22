# First-Project-Java-Spring

A Spring Boot application showcasing Thymeleaf templates and static resource handling.

## Overview
- **Name**: First-Project-Java-Spring
- **Controllers**:
  - `HelloController`: Returns plain text at `/`.
  - `GreetingController`: Renders `greeting.html` at `/greeting` with a `name` parameter.

## Setup
- **Files**:
  - `greeting.html` in `src/main/resources/templates/`.
- **Dependencies**: Include `spring-boot-starter-web` and `spring-boot-starter-thymeleaf` in `pom.xml`.

## Usage
1. Run the application.
2. Visit:
   - `http://localhost:8080/` for the root message.
 
## Notes
- Ensure one `public` class per file (e.g., `HelloController.java`, `GreetingController.java`).
- Verify template and image paths to avoid 404 errors.

## Screenshots
![localhost_8080 - Google Chrome 5_21_2025 9_55_23 PM](https://github.com/user-attachments/assets/bbe44dca-7151-4e9a-b328-432471867800)

## Technologies used
Spring Boot
Thymeleaf

Maven
---
