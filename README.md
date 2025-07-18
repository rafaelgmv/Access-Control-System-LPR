# Access Control System using ANPR/LPR
This project presents an access control system for gates based on license plate recognition, designed as a cost-effective and scalable solution. The system utilizes affordable components such as Arduino microcontrollers, an ESP32-CAM, an ultrasonic sensor for real-time detection, and a potentiometer to adjust the detection range.

The core functionality involves identifying vehicles by processing captured images using a Flask API hosted in a Docker container. This API leverages OpenCV and Tesseract OCR for license plate recognition. A key feature is the validation of license plates based on specific Portuguese patterns.

The system's architecture is hybrid, combining centralized hardware control (via Arduino) with distributed image processing (via a remote Flask API) to ensure efficiency and scalability. A safety mechanism is also included, where the ultrasonic sensor checks for obstacles before the gate closes.

For more details, including the full source code and a demonstration video, please refer to the public repository. For an in-depth technical overview, please access the

`AccessControlSystem_Paper.pdf` document.

#### License

This project is licensed under the MIT License - see the **LICENSE** file for details.
