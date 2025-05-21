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
![localhost_8080 - Google Chrome 5_21_2025 9_03_35 PM](https://github.com/user-attachments/assets/59244b2f-a25b-46d4-9c3b-b41131a25d6c)

![death-the-kid png (360×306) - Google Chrome 5_17_2025 9_24_17 PM](https://github.com/user-attachments/assets/06fd9562-e466-4a88-87a7-35d6c0ad99bd)



---
