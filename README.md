# First-Project-Java-Spring

A Spring Boot application showcasing Thymeleaf templates and static resource handling.

## Overview
- **Name**: First-Project-Java-Spring
- **Controllers**:
  - `HelloController`: Returns plain text at `/`.
  - `GreetingController`: Renders `greeting.html` at `/greeting` with a `name` parameter.

## Setup
- **Files**:
  - `Ichigo.png` in `src/main/resources/static/images/`.
  - `greeting.html` in `src/main/resources/templates/`.
- **Dependencies**: Include `spring-boot-starter-web` and `spring-boot-starter-thymeleaf` in `pom.xml`.

## Usage
1. Place `Ichigo.png` in `src/main/resources/static/images/`.
2. Run the application.
3. Visit:
   - `http://localhost:8080/` for the root message.
   - `http://localhost:8080/greeting?name=Vistula` for the template with the image.

## Notes
- Ensure one `public` class per file (e.g., `HelloController.java`, `GreetingController.java`).
- Verify template and image paths to avoid 404 errors.

## Screenshots
![localhost_8080 - Google Chrome 5_21_2025 9_55_23 PM](https://github.com/user-attachments/assets/bbe44dca-7151-4e9a-b328-432471867800)




---
