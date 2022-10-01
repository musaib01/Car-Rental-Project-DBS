# Car-Rental-Project-DBS
Keeping the tradition alive, we (once again) tried to improve our Car Rental Service project. This time we used our newly learned SQL skills to attach a database to our program and in order to make it more visually appealing we used C# for creation of a GUI.

# Introduction
As more and more people tend to move towards renting instead of ownership due to high maintenance and fuel costs, we have created a fully functional database application which could be used to manage a car rental company and its services. Users may sign up for the application. Authorized personnel with a predetermined combination of username and password can create and delete bookings, modify vehicle data, and access multiple other features of the projects.

# Project Breakdown
![Project Breakdown](https://user-images.githubusercontent.com/91963525/193409909-965632d9-f2b1-44c4-985b-4c1638103adc.png)

# Description:
Our project consists of two major elements:

# 1. Backend:
The backend was created by using SQL Server as IDE and SQL as the programming language. The project mainly consists of three tables:

1) car_info: This table will be used to store and retrieve information of the vehicles under the ownership of the company. Primary Key: number_plate
2) login_info: This table will be used to store information of the people authorized to access the main dashboard. Primary Key: username
3) user_info: This table consists of information regarding each booking made. It includes the customers information for example their contact information and CNIC number. Primary Key: CNIC Foreign Key: car_info(number_plate)

# 2. Frontend:
The front end of the project has been programmed on the C# programming language, where we have used System.Windows.Forms library that provides a huge amount of options to create an interactive and presentable interface for the user. Our project primarily consists of 9 forms each with its individual functionality. Some of the following functions are stated as below:

1) Login and Sign Up: These forms can be used to access the application using a combination of username and passwords. The user may if, not already a member, can sign up by entering their information and choosing a username and password of their choice. They can then use the login information to access the main dashboard.
2) Search: The users may use the primary keys such as Number Plate in car_info, CNIC in user_info to look up relevant information. This would display all the information present in the database with respect to that primary key using a select query.
3) Modify and Delete: Similar to search, the primary keys may be used to display information in textboxes, where they can be easily modified and even deleted from the database if required.
4) View: The data present will be displayed from the tables. This includes the vehicles in the table car_info and all the current bookings in user_info.

# Screenshots
# Sign Up Screen
![SignUp](https://user-images.githubusercontent.com/91963525/193409997-95fc79d4-a7c0-404b-9934-6ff17f140af3.png)

# Login Screen
![Login](https://user-images.githubusercontent.com/91963525/193410024-3a560e41-0359-449e-ac0e-c42a0bb3e280.png)

# Main Menu
![Main Menu](https://user-images.githubusercontent.com/91963525/193410033-43771247-0a94-46b9-a78a-63c1bcdf9be9.png)

# Booking Services
![Booking Menu](https://user-images.githubusercontent.com/91963525/193410050-1104ff59-b705-4627-97b3-673140c718ff.png)

# Booking Verification
![Booking Verification](https://user-images.githubusercontent.com/91963525/193410062-7a14ff77-d5e1-4be1-a954-d0048fccbcc7.png)

# View Booking
![ViewBookings](https://user-images.githubusercontent.com/91963525/193410072-d70a6d8b-9710-4603-ab2c-133c7870c49d.png)

# Vehicle Menu
![VehicleMenu](https://user-images.githubusercontent.com/91963525/193410085-891196d6-a10d-4046-ac1a-79dbbeffce69.png)

# Add New Vehicle
![VehicleEnter](https://user-images.githubusercontent.com/91963525/193410096-7a4c7f1a-e575-463d-969e-f52aeebafb1b.png)

# Collaborators
1) Syed Ali Raza
