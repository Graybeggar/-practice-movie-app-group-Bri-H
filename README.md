# Movie Management — Spring Boot group project

A Spring Boot practice app that manages a movie list and uses the Google Gemini API to generate movie descriptions.

## Tech stack

- Java 21
- Spring Boot 3.2.4 (spring-boot-starter-web)
- Google GenAI SDK 1.0.0
- dotenv-java
- Maven

## What it does

- Serves an HTML form at `/` to add a movie with title, rating, and review
- Calls the Gemini API to generate a short description for each submitted title
- Displays the full in-memory movie list after each submission

## How to run

1. Create a `.env` file with your Gemini API key: `GOOGLE_API_KEY=your-key`
2. Start the app: `mvn spring-boot:run`
3. Open http://localhost:8080 in a browser
