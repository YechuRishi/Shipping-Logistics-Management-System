u# Shipping-Logistics-Management-System
This project helps manage shipping and logistics operations by organizing data for senders, receivers, packages, deliveries, billing, and tracking. It uses a database to make managing and tracking shipments simple and efficient


_______________________________________________________________________________________________________________________________________________________________________________________________

| Technology                              | Role / Importance in Project                                                                                                                        |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **IMU Sensor (ICM-20948)**              | Captures raw motion data: acceleration, gyroscope, and magnetometer readings necessary for detecting vehicle dynamics.                              |
| **Microcontroller (e.g., NXP S32K144)** | Interfaces with the IMU sensor and sends raw data over UART to PC for processing. Handles low-level hardware communication.                         |
| **UART Serial Communication**           | Provides the data transmission channel between microcontroller and PC in real-time. Reliable and widely used embedded interface.                    |
| **Python**                              | Backend programming language; used to read and parse sensor data, detect events, log data, and serve real-time updates.                             |
| **PySerial**                            | Python library for reading UART serial data from the microcontroller in the backend application.                                                    |
| **Flask**                               | Lightweight Python web framework used to create a server that handles communication between backend processing and frontend dashboard.              |
| **Flask-SocketIO**                      | Enables real-time bidirectional communication between backend and frontend using WebSockets, allowing live updates of sensor data on the dashboard. |
| **Threading (Python)**                  | Allows simultaneous serial reading and real-time server operations without blocking, ensuring smooth continuous data flow.                          |
| **CSV File Logging**                    | Stores all sensor data and detected events persistently for later review or analysis.                                                               |
| **React.js**                            | Frontend JavaScript framework used to build a dynamic, responsive, and interactive web dashboard for live visualization.                            |
| **Socket.IO Client (JavaScript)**       | Connects frontend React app to backend Socket.IO server for receiving live sensor updates in real-time.                                             |
| **Chart.js**                            | Library for rendering live, animated line charts for acceleration, gyroscope, and magnetometer data on the dashboard.                               |
| **Tailwind CSS**                        | Utility-first CSS framework used for clean, modern, and responsive UI design of the dashboard.                                                      |
