# Smart Home Automation System

The **Smart Home Automation System** is a console-based project developed in C++ that simulates the operation and management of a smart home. It enables users to register accounts, log in, create rooms, add smart devices, and control them through a centralized interface. Built using Object-Oriented Programming (OOP) principles, the project models real-world smart home functionality in a structured and maintainable way.  

The system incorporates automation through scheduling, monitors device energy consumption, generates notifications for key events, and ensures data persistence using file handling. While currently console-driven, its architecture is designed to be scalable for future upgrades such as graphical interfaces (GUI) or IoT integration.  

---

## Features

###  User Management
- Secure registration and login functionality  
- Each user has independent access to their rooms and devices  
- Authentication includes password validation and exception handling  

###  Room and Device Management
- Users can create multiple rooms within the smart home  
- Each room can contain different smart devices  
- Supported device types: **Lights, Thermostats, Air Conditioners, Cameras, Door Locks**  

###  Device Control
- Devices can be switched on/off and managed individually  
- Each device performs type-specific actions (e.g., brightness adjustment, temperature regulation, motion detection)  
- Unified interface allows remote control of devices  

###  Scheduling and Automation
- Users can schedule device actions at specific times  
- A scheduler continuously checks system time and executes actions automatically  
- Scheduling options include adding, updating, viewing, and removing tasks  

###  Energy Monitoring
- Tracks energy consumption of devices based on usage  
- Generates detailed reports on energy usage  
- Provides threshold-based warnings when consumption exceeds limits  

###  Notification System
- Alerts users about events such as motion detection, scheduled actions, and energy overuse  
- Notifications are stored and can be reviewed later  

###  Persistent Storage
- System data (users, rooms, devices, and states) is saved to files  
- Data loads automatically at startup, ensuring continuity across sessions  

---

## OOP Concepts Applied
- **Encapsulation**  
- **Abstraction**  
- **Inheritance**  
- **Polymorphism**  
