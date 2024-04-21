## SpringBoot RESTful API Project

This SpringBoot project demonstrates the implementation of a simple RESTful API for managing user data. It includes endpoints to retrieve user information based on their ID.

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Maven

### Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/your_username/spring-api.git
   ```

2. Navigate to the project directory:

   ```
   cd spring-api
   ```

3. Build the project using Maven:

   ```
   mvn clean install
   ```

4. Run the application:

   ```
   mvn spring-boot:run
   ```

### Project Structure

- **api/model/User.java**: Defines the User model class with properties such as ID, name, age, and email.
- **api/controller/UserController.java**: Contains the REST controller class responsible for handling HTTP requests related to user data.
- **api/service/UserService.java**: Implements the business logic for retrieving user data.
- **SpringApiApplication.java**: Main class to bootstrap the Spring Boot application.

### Usage

- **GET /user?id={userId}**: Retrieves user information based on the provided user ID.

### Example

To retrieve user information for a user with ID 1, make a GET request to:

```
http://localhost:8080/user?id=1
```

### Sample User Data

- User 1:
  - Name: Ida
  - Age: 32
  - Email: ida@mail.com
- User 2:
  - Name: Hans
  - Age: 26
  - Email: hans@mail.com
- User 3:
  - Name: Lars
  - Age: 45
  - Email: lars@mail.com
- User 4:
  - Name: Ben
  - Age: 32
  - Email: ben@mail.com
- User 5:
  - Name: Eva
  - Age: 59
  - Email: eva@mail.com

### Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request.

