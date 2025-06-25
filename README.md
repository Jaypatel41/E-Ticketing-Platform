# E-Ticketing-Platform

🎫 E-Ticketing Platform – DBMS Project
The E-Ticketing Platform is a relational database system built entirely using SQL, designed to simulate the backend of a real-world ticket booking system. It manages booking operations for movies, concerts, and stand-up shows, and supports multiple user roles including buyers, organizers, and administrators.

🛠️ Tech Stack
Language Used: SQL (Structured Query Language)

Database Systems Tested On:

MySQL 8.0+

PostgreSQL 15+

🎯 Key Features
🔒 Multi-Role Support
Buyers can:

Browse available events by date, location, or type

View seat availability in real-time

Book, cancel, or modify tickets

View their personal booking history and payment records

Organizers can:

Create and manage events (e.g., concerts, movies)

Assign venues and seat layouts

View bookings and seat occupancy

Track event-wise earnings

Admins can:

Manage users and permissions

Generate system-wide reports

Monitor total revenue, popular events, and active venues

Audit organizer performance

🧠 Advanced SQL Querying
Complex JOINs, GROUP BY, HAVING, NESTED QUERIES, VIEWS, and AGGREGATE FUNCTIONS used throughout.

Queries provided for both operational tasks and analytics:

“Top 5 most booked events this month”

“Total earnings by venue”

“List of upcoming events for a particular organizer”

“Users who have booked tickets for all shows at a venue”

📐 Normalization & Design
✅ All relations are in Boyce-Codd Normal Form (BCNF) ensuring:

No data redundancy

Referential integrity

Improved update and query performance

Proper use of foreign keys, primary keys, and cascading constraints ensures data consistency across all operations.

🏟️ Event & Venue Management
Detailed schema for managing:

Events (with category, description, date/time)

Venues (location, capacity, seating layout)

Seats (individual seat metadata)

Schedules (event-specific time slots at a venue)

💳 Ticketing & Orders
Each booking stores:

Seat-specific ticket details

Order ID, user ID, event ID

Payment status and transaction metadata

Tracks cancellations and seat re-availability

