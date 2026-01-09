# java-face-recognition
Project to create App for Face Recognition
### Requirements  
- Java 25
- OpenCV https://opencv.org/
- SpringBoot
- SFace model (https://huggingface.co/opencv/face_recognition_sface/blob/main/face_recognition_sface_2021dec.onnx)
- Maven
### Setup
1. Build the project:
* mvn clean install

2. Run app
* ./mvnw spring-boot:run

The application will start on http://localhost:8080

Once the application is running, you can access the Swagger UI at: http://localhost:8080/swagger-ui/index.html

[static](src/main/resources/static) have some samples for test


