# SpringBootCrud
This repository contains a backend application built using **Java, Docker, PostgreSQL, and Spring Boot**. The application allows for performing CRUD (Create, Read, Update, Delete) operations on data.

**Overview**
The SpringBootCrud application was developed as part of a crash course with amigoscode, where the following concepts and technologies were covered:

- JPA (Java Persistence API): The application uses JPA for object-relational mapping, allowing seamless interaction with the database.
- JDBC (Java Database Connectivity): JDBC is utilized for database connectivity and executing SQL queries.
- Configuration & Annotations: The application leverages various annotations and configurations to define beans, handle dependencies, and manage application settings.
- Request Params: It demonstrates the usage of request parameters in HTTP requests to pass data to the backend.
- Request Mappings: Spring Boot's request mapping annotations are used to map incoming requests to appropriate controller methods.
- Path Variable: Path variables are employed to extract dynamic values from the request URL.
- Maven, Gradle: The project can be built using either Maven or Gradle build tools, and their respective configuration files are included.
- Tomcat SQL Postman: The application is integrated with Tomcat, SQL, and Postman for server hosting, database management, and testing HTTP requests, respectively.
- MVC Architecture: The application follows the Model-View-Controller (MVC) architectural pattern for better separation of concerns and modularity.


**Getting Started**

To run the SpringBootCrud application locally, follow these steps:

**Prerequisites**:

Ensure you have Java Development Kit (JDK) installed on your machine.
Install Docker to run the PostgreSQL database container.
Optionally, have a REST client like Postman to interact with the API.

**1 Clone the Repository:**

git clone https://github.com/your-username/SpringBootCrud.git


**2 Build the Application:**

Navigate to the project directory.
Run the appropriate build command based on your preference:
If using Maven:

mvn clean install

If using Gradle:

gradle clean build

**3 Run the PostgreSQL Container:**

In the project directory, open a terminal or command prompt.
Run the following command to start the PostgreSQL database container:

docker-compose up -d


**4 Start the Application:**

Run the application using the following command:

java -jar target/SpringBootCrud.jar


**5 Interact with the API:**

Open a web browser or use Postman to send HTTP requests to http://localhost:8080/api for CRUD operations on the data.

**Contributing**
Contributions to the SpringBootCrud project are welcome! If you find any issues or have suggestions for improvement, feel free to open a new issue or submit a pull request.

**License**
This project is licensed under the MIT License. Feel free to use and modify the code as per the terms of the license.

**Acknowledgements**
The SpringBootCrud application was developed based on a crash course by amigoscode. Thanks to amigoscode for providing the valuable learning resources and guidance.

**Contact**
For any questions or inquiries, please contact **riyazramzan2001@gmail.com**

Feel free to customize the README file by adding more details or sections based on your specific project requirements.





