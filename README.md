
# FlashcardsApp

The application aims to support learning English through the use of flashcards. The application allows users to register, log in and manage flashcard sets. The application's functionalities include creating, editing, viewing and deleting your own flashcard sets and using flashcards shared by other users. The application offers three learning modes: viewing flashcards, learning in written form and tests. Additionally, the functions include the ability to import sets from Excel files and coloring the background of flashcards to categorize sets.


## Acknowledgements

 - [FlashcardsApp - backend](https://github.com/GWeronika/FlashcardsApp-backend)
 - [FlashcardsApp - frontend](https://github.com/GWeronika/FlashcardsApp-frontend)


## Requirements

### GENERAL

- Docker
- Docker Compose

### BACKEND

- Java Development Kit (JDK)
- Apache Maven

### FRONTEND

- Node.js
- Node Package Manager (npm)
## Launch the project

### Running the app locally

Go to backend directory

`cd backend`

Run the backend using Maven

`mvn spring-boot:run`

Go to frontend directory:

`cd frontend`

Execute the following commands:

`npm install`

`npm start`

The application should be available at `http://localhost:3000`.


### Running the app using Docker

In the main project directory, run the following command:

`docker-compose up --build`

The application should be available at `http://localhost:3000`.
To stop containers, press  `Ctrl+C`, then do:

`docker-compose down`.