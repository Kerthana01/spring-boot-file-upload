# Spring Boot File Upload & Download REST API Example

A simple Spring Boot project demonstrating how to upload and download files via RESTful APIs. This project supports storing files locally and retrieving them through HTTP endpoints.

## Features

- Upload single or multiple files
- Download files by filename
- List all uploaded files
- RESTful API endpoints
- Exception handling for missing files

## Technologies Used

- Java 17
- Spring Boot 3.x
- Spring Web
- Spring MVC
- Maven
- Lombok (optional)
- Swagger (optional for API testing)

## Project Structure


## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.x
- IDE (IntelliJ, Eclipse, VS Code)
- Postman (for testing APIs)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Kerthana01/spring-boot-file-upload.git
   cd spring-boot-file-upload-download-rest-api-example
2.Build the project:
 mvn clean install
3.Run the application:
mvn spring-boot:run
Example using cURL

Upload a file:
curl -F "file=@/path/to/your/file.txt" http://localhost:8080/uploadFile
Download a file:
curl -O http://localhost:8080/downloadFile/file.txt
Configuration

Update application.properties if you want to change the file storage location:
file.upload-dir=uploads
License

This project is open-source and available under the MIT License.

If you want, Kerthana, I can also make a **shorter, more visually appealing version with badges, GIF preview, and quick setup instructions** for GitHub—it will make your repo look super professional.  

Do you want me to do that?





