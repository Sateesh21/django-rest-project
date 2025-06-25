MyTravels is a full-stack bus ticket booking web application built using Django for the backend and React.js for the frontend. It offers users a seamless experience in browsing available buses, viewing full bus details, booking seats, and managing their bookings

## Tech Stack
React.js | Tailwind CSS | Axios | React Router | Django | REST Framework | Django Admin Auth | JWT | django-rest-framework-simplejwt | Media Storage Azure Blob Storage | Cloud Storage | Crypto-js

## 🔹 All Available Bus Details
This admin panel view displays all the registered buses in the system. It allows the administrator to view, edit, or delete bus entries with ease. This page was created using Django's built-in admin interface, which automatically generates user-friendly CRUD screens from the model definitions.

Features of this screen:

**Bus Name**: The registered name of the bus operator. <br>
**Number**: The unique identification number assigned to each bus. <br>
**Origin**: The starting point of the journey. <br>
**Destination**: The ending point or terminal of the journey. <br>
**Actions**: Admins can perform actions like editing, deleting, or bulk updating buses from this screen. <br>
This interface provides a centralized location for managing the backend bus data without writing extra frontend code, thanks to Django Admin.
<br> <br>
![be_allBusDetails](https://github.com/user-attachments/assets/9ae78ea0-3278-4fb6-895d-9886a20ee645)
<br> <br>

## 🔹 Available Seats per Bus
This screen displays all the seats associated with a particular bus in the system. Developed using Django Admin, it provides a clear overview of seat availability for administrators.

## Key Features:

**Seat Number**: Each seat is uniquely identified (e.g., S1, S2... S36). <br>
**Bus Info**: Every seat is linked to its respective bus, displaying the bus name, number, origin, and destination. <br>
**Is Booked**: A boolean field that indicates whether a seat has been booked or not, making it easy to track real-time seat occupancy. <br>

#### Admins can:

View all seat records, <br>
Filter or sort based on booking status, <br>
Add or update seat entries directly from the admin panel. <br>

This ensures efficient backend seat management without manually interacting with the database.
<br> <br>
![be_availbleSeats](https://github.com/user-attachments/assets/39818c5a-febf-49ff-8440-dff0ba517511)
<br> <br>


## 🔹 Add Bus - Admin Feature
This screen enables the admin to add new buses into the system with complete travel and operational details. Built using Django’s model-backed admin interface, this form simplifies data entry without custom frontend development.

Fields Included:

**Bus Name**: The name of the bus service (e.g., InterCity, Garuda). <br>
**Number**: A unique identifier for the bus (e.g., 2801). <br>
**Origin & Destination**: Specifies the starting and ending cities of the route. <br>
**Features**: Optional field for describing onboard facilities (e.g., AC, WiFi). <br>
**Start Time & Reach Time**: Indicates when the bus departs and when it arrives at its destination. <br>
**Number of Seats**: Total seats available for booking on that bus. <br>
**Price**: Fare per passenger for this bus route. <br>

### Highlights:
Easily scalable: Admin can add unlimited buses. <br>
Time fields are server-synced and timezone aware. <br>
Seamless integration with the seat model for tracking availability. <br> <br>

This admin utility ensures backend users can manage fleet data effectively without accessing the database manually. <br> <br>

![be_busdetails](https://github.com/user-attachments/assets/0dc63870-4361-45f7-97d1-84d7e3208224) <br> <br>


## 🔹 User Details - Admin Feature
This section of the Django Admin Panel provides a comprehensive overview of all users who have signed up or logged into the application. It allows the admin to manage user accounts, monitor activity, and apply permissions where necessary.

#### Displayed Information:

**Username**: The unique username selected by the user (e.g., Sateesh21). <br>
**Email Address**: Registered email used during signup. <br>
**Staff Status**: Indicates whether the user is part of the staff/admin group. <br>

##### Search and Filter Options:
**By staff status**: Filter users based on their admin privileges. <br>
**By superuser status**: Identify if a user has full control over the admin panel. <br>
**By active status**: Check which accounts are currently active. <br>

##### Key Features:
Admin can add, edit, or remove users. <br>
Permissions and roles can be assigned from the admin interface. <br>
Secure authentication is integrated using Django's built-in user management.<br><br>

This functionality supports seamless access control, user tracking, and better management of authenticated users within the system. <br><br><br>
![be_userDetails](https://github.com/user-attachments/assets/639ec885-70e7-452e-b0da-835a61bb9b97)

