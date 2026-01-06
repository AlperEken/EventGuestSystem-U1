# GuestFlow Manager

**GuestFlow Manager** is a Java-based console application developed by Alper Eken as a primary project for the Object-Oriented Programming course at Malmö University. The software serves as a centralized administrative tool for event organizers to register guests, update personal profiles, and monitor attendance data through a structured and interactive terminal interface.

##  Key Features

The application is built around an intuitive menu system that manages a dynamic guest list stored within a 2D String array. Beyond basic registration and removal of attendees, the program features a robust statistics module that provides real-time insights into the total guest count, age-based demographics (adults versus children), and identification of the oldest and youngest guests. Users also have the ability to reorganize seating charts by swapping guest positions and can update specific details like names and ages without needing to restart the registration process.

## Technical Implementation

This project utilizes core Java functionalities, employing the `java.util.Scanner` class to handle interactive user input. The architecture emphasizes a modular approach where data-altering logic is encapsulated within specific methods, while the `main` method governs the user interface flow through a `switch-case` structure. This design ensures that input validation and error handling are centralized, preventing redundant data passing and making the codebase significantly easier to debug and maintain.

## Challenges & Reflection

A major focus of the development process was implementing rigorous error handling to manage invalid user inputs. By utilizing `hasNextInt` and input validation loops, the program is protected from crashes when users enter non-numeric data or negative ages. Shifting the input-reading logic to the `main` method was a critical design choice that improved the overall clarity of the program, ensuring that methods are only called when valid data is ready to be processed.

## Getting Started

To run the application locally, ensure you have the Java Development Kit (JDK) installed and follow these steps:

 **Compile the source code:**
   ```bash
   javac DA339A_U1.java
```

 **Run the source code:**
   ```bash
  java DA339A_U1
```

 *Author: Alper Eken Course: Objectoriented programming Semester: Autumn 2024*
