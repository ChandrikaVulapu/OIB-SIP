# Task 1 - Online Reservation System (Java + MySQL)
Oasis Infobyte Java Internship Project  
Intern Name: Vulapu Chandrika  
Date: July 2025

## Requirements:
- Java installed (JDK 8+)
- MySQL Server installed and running
- mysql-connector-j-9.4.0.jar (included)

## Setup Instructions:
1. Create the database:
   - Open MySQL and run:
     CREATE DATABASE railwaysystem;

2. Create the `reservations` table:
USE railwaysystem;
CREATE TABLE reservations (
pnr_number INT PRIMARY KEY,
passenger_name VARCHAR(100),
train_number VARCHAR(20),
class_type VARCHAR(20),
journey_date DATE,
from_location VARCHAR(50),
to_location VARCHAR(50)
);

markdown
Copy
Edit

3. Place all files in one folder:
- Task1.java
- mysql-connector-j-9.4.0.jar

4. Open terminal in that folder and run:
**
**Compile:**
javac -cp ".;mysql-connector-j-9.4.0.jar" Task1.java

shell
Copy
Edit

### Run:
java -cp ".;mysql-connector-j-9.4.0.jar" Task1

pgsql
Copy
Edit

5. Login using your MySQL credentials (e.g., root / your password)
6. Follow the menu to insert/delete/show reservation records.
