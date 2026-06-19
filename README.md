Based on your uploaded project, the DBMS project is a **Bus Ticket Booking and Management System** with three main users:

* Admin
* Customer
* Driver

# Project Title

**Bus Ticket Booking and Management System Using DBMS**

# Project Abstract

The Bus Ticket Booking and Management System is a database-driven web application designed to automate the process of bus ticket reservation, trip management, driver management, and passenger services. The system enables customers to book tickets online, view bus schedules, track buses, and cancel reservations. Administrators can manage buses, routes, drivers, trips, and reports, while drivers can view assigned trips and earnings. The system improves efficiency, reduces manual work, and provides real-time information to users.

---

# Project Objectives

1. Automate bus ticket booking process.
2. Manage customer records efficiently.
3. Maintain driver and trip information.
4. Generate reports for administration.
5. Track bus schedules and routes.
6. Reduce paperwork and manual errors.
7. Provide secure and fast ticket reservation.

---

# Existing System

### Problems

* Manual ticket booking.
* Long waiting time.
* Data redundancy.
* Difficult route management.
* Lack of real-time information.
* Poor record maintenance.

---

# Proposed System

The proposed system provides:

* Online ticket booking.
* Customer registration and login.
* Bus route management.
* Driver assignment.
* Ticket cancellation.
* Bus tracking.
* Notification services.
* Report generation.

---

# Modules Description

## 1. Login Module

### Purpose

Provides secure authentication for Admin, Customer, and Driver.

### Features

* User Login
* Password Verification
* Role-Based Access
* Session Management

---

## 2. Registration Module

### Purpose

Allows new customers to create accounts.

### Features

* User Registration
* Data Validation
* Account Creation
* Secure Credential Storage

---

## 3. Customer Module

### Purpose

Provides ticket booking facilities.

### Features

* Book Tickets
* View Tickets
* Cancel Tickets
* Track Buses
* View Bus Timings
* Contact Support

---

## 4. Ticket Booking Module

### Purpose

Handles seat reservation.

### Features

* Source Selection
* Destination Selection
* Seat Availability Check
* Fare Calculation
* Ticket Confirmation

---

## 5. Ticket Cancellation Module

### Purpose

Allows customers to cancel booked tickets.

### Features

* Ticket Search
* Cancellation Request
* Refund Processing
* Seat Reallocation

---

## 6. Bus Timing Module

### Purpose

Displays bus schedules.

### Features

* Arrival Time
* Departure Time
* Route Information
* Bus Availability

---

## 7. Bus Tracking Module

### Purpose

Tracks bus location and trip status.

### Features

* Real-Time Tracking
* Route Monitoring
* Trip Status Updates

---

## 8. Driver Management Module

### Purpose

Manages driver information.

### Features

* Driver Registration
* Driver Assignment
* Driver Records
* Driver Availability

---

## 9. Trip Management Module

### Purpose

Handles bus trips and route planning.

### Features

* Create Trips
* Modify Trips
* Route Assignment
* Schedule Management

---

## 10. Earnings Module

### Purpose

Tracks income and performance.

### Features

* Daily Earnings
* Monthly Earnings
* Driver Performance
* Revenue Analysis

---

## 11. Notification Module

### Purpose

Sends updates to users.

### Features

* Booking Confirmation
* Cancellation Alerts
* Schedule Updates
* Service Notifications

---

## 12. Report Module

### Purpose

Generates reports for administrators.

### Features

* Ticket Reports
* Revenue Reports
* Driver Reports
* Trip Reports

---

# Software Requirements

| Component | Specification         |
| --------- | --------------------- |
| Frontend  | HTML, CSS, JavaScript |
| Backend   | PHP                   |
| Database  | MySQL                 |
| Server    | XAMPP                 |
| Browser   | Chrome, Edge, Firefox |
| OS        | Windows 10/11         |

---

# Hardware Requirements

| Component | Specification       |
| --------- | ------------------- |
| Processor | Intel i3 or Above   |
| RAM       | 4 GB Minimum        |
| Storage   | 20 GB Free Space    |
| Monitor   | 1366×768 Resolution |
| Internet  | Required            |

---

# Database Tables

## Users

| Field    |
| -------- |
| User_ID  |
| Name     |
| Email    |
| Password |
| Role     |

---

## Customers

| Field       |
| ----------- |
| Customer_ID |
| Name        |
| Contact     |
| Address     |

---

## Drivers

| Field      |
| ---------- |
| Driver_ID  |
| Name       |
| License_No |
| Phone      |

---

## Buses

| Field      |
| ---------- |
| Bus_ID     |
| Bus_Number |
| Capacity   |
| Type       |

---

## Routes

| Field       |
| ----------- |
| Route_ID    |
| Source      |
| Destination |
| Distance    |

---

## Trips

| Field     |
| --------- |
| Trip_ID   |
| Bus_ID    |
| Driver_ID |
| Route_ID  |
| Date      |
| Time      |

---

## Tickets

| Field       |
| ----------- |
| Ticket_ID   |
| Customer_ID |
| Trip_ID     |
| Seat_No     |
| Fare        |
| Status      |

---

# Project Architecture

```text
+------------------+
|     CUSTOMER     |
+------------------+
         |
         v
+------------------+
|   WEB INTERFACE  |
| HTML/CSS/JS/PHP  |
+------------------+
         |
         v
+------------------+
| APPLICATION LOGIC|
+------------------+
         |
         v
+------------------+
|     MYSQL DB     |
+------------------+
   |      |      |
   |      |      |
   v      v      v

+--------+ +--------+ +--------+
| ADMIN  | | DRIVER | |CUSTOMER|
+--------+ +--------+ +--------+

Admin Functions:
- Manage Drivers
- Manage Trips
- View Reports
- Send Notifications

Driver Functions:
- View Assigned Trips
- Earnings
- Route Information

Customer Functions:
- Book Ticket
- View Ticket
- Cancel Ticket
- Track Bus
```

# Data Flow Diagram (Level 0)

```text
Customer
    |
    v
Bus Ticket Booking System
    |
    +----> Ticket Database
    |
    +----> Bus Database
    |
    +----> Driver Database
    |
    +----> Reports Database

Admin <------> System <------> Driver
```

# Advantages

* Faster ticket booking.
* Easy record maintenance.
* Secure data storage.
* Reduced paperwork.
* Improved customer satisfaction.
* Real-time updates.
* Accurate reporting.

# Conclusion

The Bus Ticket Booking and Management System provides a complete solution for managing bus reservations, trips, drivers, routes, and customer services. By integrating a centralized MySQL database with a web-based interface, the system improves operational efficiency, ensures data accuracy, and enhances the overall transportation management process.

This content is suitable for your **DBMS mini project report, viva, documentation, and presentation**.
