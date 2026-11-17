# Hackathon Project 1

## 1. Project Overview

This project is designed to monitor multiple stations using real-time telemetry data.

The system receives station data, detects abnormal conditions such as sudden speed reduction, and displays the monitoring results on a web dashboard.

## 2. System Architecture

The project consists of three main components:

1. Backend (Laptop 1)
   - Node.js server
   - Receives telemetry data through HTTP POST requests.
   - Processes station information.

2. Frontend (Laptop 2)
   - HTML-based dashboard.
   - Displays station telemetry and status updates.

3. Testing and Integration (Laptop 3)
   - Automated telemetry simulation.
   - CSV-based test data.
   - Integration testing and documentation.

## 3. Technologies Used

- HTML
- Node.js
- JavaScript
- Git and GitHub
- Visual Studio Code

## 4. Project Structure

```text
Hackathon-Project-1/
│
├── backend/
│   ├── server.js
│   └── test_simulation.js
│
├── public/
│   └── Frontend files
│
├── simulator/
├── config/
├── data/
│   └── mock_telemetry.csv
│
└── README.md
```

## 5. Installation

1. Install Node.js.
2. Clone the GitHub repository.
3. Open the project in Visual Studio Code.
4. Install the required dependencies.

## 6. Running the Project

Backend startup command: To be confirmed with Laptop 1.

Frontend startup command: To be confirmed with Laptop 2.

Testing command:

```bash
node backend/test_simulation.js
```

## 7. Testing

The testing module will simulate:

- Normal station operation.
- Sudden slowdown at ST_02.
- Multi-station telemetry data.
- Abnormal operating conditions.

## 8. Team Responsibilities

| Laptop | Responsibility |
|---|---|
| Laptop 1 | Backend development |
| Laptop 2 | Frontend development |
| Laptop 3 | Testing, integration and documentation |