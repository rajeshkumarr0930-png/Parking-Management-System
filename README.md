## Project Title
**Parking Management System**

## Name : Rajesh Kumar R 
## Register Number : 711524BEE043

## Project Description

The Parking Management System is a web-based application developed to simplify and improve vehicle parking operations. It enables users to register vehicle entries, allocate parking slots automatically, monitor available and occupied spaces, and manage vehicle exits. The system calculates parking fees based on vehicle type and parking duration. Its user-friendly interface and automated processes help reduce manual work, improve parking efficiency, and provide a convenient parking management experience.

## Objectives

- Automate vehicle entry and exit management.
- Allocate available parking slots efficiently.
- Display total, occupied, and available parking spaces.
- Calculate parking fees based on parking duration and vehicle type.
- Reduce manual errors and improve operational efficiency.
- Provide a simple and responsive user interface.

## Technologies and Tools Used

**Frontend**
- HTML5
- CSS3
- JavaScript

**Backend**
- Java
- Spring Boot
- REST API

**Build Tool**
- Apache Maven

**Development Tools**
- Visual Studio Code / IntelliJ IDEA / Eclipse
- Git
- GitHub

## Key Features

- Vehicle registration with vehicle number, owner name, and vehicle type.
- Automatic allocation of the next available parking slot.
- Parking slot availability dashboard.
- Vehicle exit management.
- Automatic parking fee calculation.
- Responsive interface for desktop and mobile devices.

## Installation and Execution

### Prerequisites
- Java JDK 17 or later
- Apache Maven
- A web browser

### Steps to Run
1. Clone or download this repository.
2. Open the project folder in a terminal.
3. Run the following command:

   ```bash
   mvn spring-boot:run
   ```

4. Open your browser and visit:

   `http://localhost:8080`

## Project Structure

```text
Parking_Management_System/
├── pom.xml
├── README.md
└── src/
    └── main/
        ├── java/com/parking/
        │   ├── ParkingManagementApplication.java
        │   ├── controller/
        │   │   └── ParkingController.java
        │   └── model/
        │       └── ParkingSlot.java
        └── resources/static/
            ├── index.html
            ├── style.css
            └── app.js
```

## Future Enhancements

- Integration with a MySQL database for permanent data storage.
- Online payment integration.
- User authentication and administrator dashboard.
- Real-time parking sensors and IoT-based slot monitoring.
- Parking reservation and booking functionality.

## Repository Link

**GitHub Repository:** [Paste Your GitHub Repository URL Here]

## Conclusion

The Parking Management System provides a simple and efficient solution for managing parking spaces. By automating slot allocation, vehicle tracking, and fee calculation, the application helps improve convenience, accuracy, and overall parking management efficiency.

---

**Note:** This is an academic demonstration project. The current version stores parking data in memory, so records reset when the application restarts.
