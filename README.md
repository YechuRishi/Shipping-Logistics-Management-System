# Shipping  and Logistics Management System

## Overview

The **Shipping Logistics Management System** is a comprehensive solution designed to streamline and simplify shipping and logistics operations. It manages critical data related to senders, receivers, packages, delivery methods, billing, and shipment tracking — all organized efficiently within a relational database.

This system helps logistics companies and businesses to:

- Efficiently record and manage shipment details
- Track package status and delivery progress
- Manage billing and cost calculations
- Maintain accurate sender and receiver information

By centralizing this data, the system ensures smoother logistics workflows and better customer service.

---

## Features

- **Sender Management:** Store and maintain sender information including contact details and location.
- **Receiver Management:** Keep detailed records of shipment recipients.
- **Package Tracking:** Log packages with sender, receiver, delivery method, and order details.
- **Delivery Methods:** Manage different transportation types (air, sea, land) and associated costs.
- **Billing:** Generate and track billing transactions related to shipments.
- **Shipment Tracking:** Monitor origin, current location, and destination of packages with timestamps.

---

## Technologies Used

- **SQL / Oracle SQL:** For database schema design and data management
- **Relational Database:** Structured storage with foreign keys to maintain data integrity
- **PL/SQL Scripts:** For inserting initial data and managing operations

---

## Database Schema

The database consists of the following core tables:

- `Sender` — Sender details
- `Receiver` — Receiver details
- `Package` — Package details linking sender, receiver, and delivery
- `Delivery` — Delivery methods and cost per unit
- `Billing` — Billing transactions related to packages
- `Tracking` — Shipment tracking details

---

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/YechuRishi/Shipping-Logistics-Management-System.git

 ## Contact
 Rishi Yechu — yechurishi2003@gmail.com




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
