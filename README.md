# maven

## Overview
This is a simple Maven-based Java project named `hemap`. It is a `jar` project built using Apache Maven.

## Project Structure
```
hemap/
├── pom.xml                 # Maven Project Object Model file
├── src/
│   ├── main/
│   │   ├── java/           # Main Java source code
│   │   ├── resources/      # Application resources (if any)
│   ├── test/
│   │   ├── java/           # Unit tests
│   │   ├── resources/      # Test resources (if any)
├── target/                 # Compiled classes and packaged JAR
```

## Prerequisites
Make sure you have the following installed:
- Java 17 or later
- Apache Maven 3.x

## Build the Project
To clean and package the project, run:
```sh
mvn clean package
```
This will:
- Clean previous build artifacts.
- Compile the source code.
- Run unit tests.
- Package the application into a `.jar` file in the `target/` directory.

## Running Tests
To run unit tests:
```sh
mvn test
```

## Running the JAR
After a successful build, you can run the generated JAR file:
```sh
java -jar target/hemap-1.0-SNAPSHOT.jar
```

## Notes
- The project currently includes one test class (`devOps.AppTest`), which runs successfully.
- Modify `pom.xml` to add dependencies as needed.

## License
This project is licensed under the MIT License.

