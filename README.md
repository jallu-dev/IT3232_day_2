# Spring Boot Application

## Overview

This is a simple Spring Boot application that provides RESTful endpoints to return messages. The application is structured with a controller that maps specific routes to return string responses.

## Requirements

- Java 17 or later
- Maven
- Spring Boot

## Installation

1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd <project-directory>
   ```
3. Build the application using Maven:
   ```sh
   mvn clean install
   ```

## Running the Application

Run the application using the following command:

```sh
mvn spring-boot:run
```

## API Endpoints

The application provides the following endpoints:

### GET `/app/msg`

Returns a simple message:

```json
"Hello SpringBoot"
```

### GET `/app/name`

Returns another message:

```json
"Hello my name is SpringBoot"
```

## Technologies Used

- Spring Boot
- Java
- Maven

## Output

![Screenshot (358)](https://github.com/user-attachments/assets/16d8127d-48b3-4a76-9ca8-74ab3744f263)
