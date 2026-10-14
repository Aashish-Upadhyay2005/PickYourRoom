# PickYourRoom 

## Description

PickYourRoom is a Java-based Room Booking System developed by Aasish Upadhyay that provides both a text-based Command Line Interface (CLI) and a Graphical User Interface (GUI) using Java Swing. The program follows the Model-View-Controller (MVC) architectural pattern for effective code organization and separation of concerns. To ensure reliability, JUnit 5 was used for comprehensive testing, and all test cases are included in the submission.

PickYourRoom offers a range of functionalities, including user management, building management, room management, reservation booking, reservation deletion, reservation viewing by Booking ID or email ID, displaying all booked rooms, and data persistence through file save and load operations.

This project was developed by Aasish Upadhyay as part of the CS5001 Object-Oriented Modelling, Design and Programming course practical.

## Functionalities Implemented

PickYourRoom supports the following functionalities for both the GUI and CLI interfaces:

Add, Delete, and View Users.

Add, Delete, and View Buildings.

Add, Delete, and View Rooms.

Book or Delete a Room Reservation.

View Your Reservations by Booking ID.

View All Booked Rooms.

View Your Reservations by Email ID.

Save Data to a File.

Load Data from a File.

Exit the Application.



## Application Files
PickYourRoom comprises several files, each responsible for specific aspects of the application:

PickYourRoom.java (Main File)

User Service

Building Service

Room Service

Reservation Service

User Model

Building Model

Room Model

Reservation Model

BookingResource Controller

CLI View

GUI View

## Additional Features

In addition to the core system requirements, PickYourRoom incorporates the following additional features:

BookingID: Users can create a unique booking reference to store multiple instances of reservations, enhancing the booking experience.

User Email_ID: Essential for implementing Role-Based Control, as administrative privileges are available. This facilitates logging the creation, updating, and deletion of objects.

Viewing All Objects: Users can view all objects for Users, Buildings, Rooms, and Reservations

## User Functionalities

PickYourRoom offers the following user functionalities:

Add and remove people, rooms, buildings, and bookings.

Select a specific time to view all available rooms at that time.

Choose a time slot (start and end times) and view all rooms available for that entire period.

View the schedule for a given room, including existing bookings and free periods.

View all bookings made by a specific person.

Save data to a specified filename.

Load data from a specified file.



## Setup and Installation

### Terminal Usage or IDE Based
Follow these steps to set up and run PickYourRoom:

Extract the downloaded *.zip file.

Navigate to the src folder of the program.

Compile the .java files in the terminal:

text
javac *.java
Run the PickYourRoom.java file:

text
java PickYourRoom
Note: The command-line and GUI interfaces run together with threading implemented for a seamless user experience.

Technologies Used
PickYourRoom is built using the following technologies:

Java 17

JUnit 5 (for testing)

Git (for version control)

Author
Aasish Upadhyay

Feel free to explore and use PickYourRoom for your scheduling and reservation needs.

