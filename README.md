## clinic-management-system
A Java and MySQL-based Clinic Management System developed for the **COMP306 Database Systems** project. The system centralizes clinic operations including appointment scheduling, patient management, billing, payment processing, laboratory services, and analytical reporting.

The application was built using **Java Swing** for the graphical user interface, **MySQL** for database management, **JDBC** for database connectivity, and **JFreeChart** for data visualization.

## Project Overview
The system was designed to simulate the daily operations of a healthcare facility through a centralized relational database environment.

**Key capabilities:**
- Patient and staff management
- Appointment scheduling
- Medical record management
- Laboratory services
- Billing and payment processing (Cash, Card, Insurance)
- Revenue and analytics reporting
- Medication and inventory tracking

**Database concepts demonstrated:**
- Entity specialization (PERSON → PATIENT/STAFF, PAYMENT → Cash/Card/Insurance)
- 3rd Normal Form (3NF)
- Multi-table joins, GROUP BY, aggregation
- Stored procedures & triggers
- Transaction handling & PreparedStatements

---

# Technologies Used
| Technology | Purpose                   |
| ---------- | ------------------------- |
| Java       | Main programming language |
| Java Swing | Graphical User Interface  |
| MySQL      | Relational Database       |
| JDBC       | Database Connectivity     |
| JFreeChart | Data Visualization        |
| Maven      | Dependency Management     |

# Database Concepts Demonstrated
- Relational Database Design
- ER/EER Modelling
- 3rd Normal Form (3NF)
- Multi-table SQL Queries
- LEFT JOIN Operations
- GROUP BY Aggregation
- Stored Procedures
- Database Triggers
- Transaction Handling
- PreparedStatements
- Referential Integrity Constraints

# System Architecture
The application follows a modified MVC (Model-View-Controller) architecture:

- Model: Handles database interaction and SQL queries
- View: Java Swing graphical user interface
- Controller: Handles communication between GUI and database logic

# Main Modules

- Appointments Module
- Billing Module
- Payment Processing Module
- Reports Dashboard
- Inventory & Medication Tracking

## 🛠️ Installation & Setup
- Java JDK 17+
- MySQL Server 8+
- NetBeans or IntelliJ IDEA
- MySQL Connector/J

### Steps
1. git clone https://github.com/TlotlisoThene/clinic-management-system.git
2. Import the database:
   - Open MySQL Workbench
   - Import clinic_db_final.sql
3. Configure database credentials inside:
   - DatabaseConnection.java
4. Open the project in NetBeans or IntelliJ IDEA
5. Build the project using Maven
6. Run the application
## Default Login
 - Username: admin
 - Password: 123
   
# Reports & Analytics
The system generates analytical reports including:

- Doctor performance analysis
- Revenue by department
- Medication usage trends
- Patient treatment insights
- Payment method analysis

# Security & Data Integrity

- PreparedStatements used to prevent SQL injection
- Transaction handling for payment consistency
- Validation logic for data integrity
- Try-With-Resources for automatic resource management

# Challenges Encountered
 - Challenge	Solution
 - Database consistency	Implemented atomic transactions
 - SQL injection prevention	Used PreparedStatements
 - Database connectivity	Centralized DatabaseConnection utility
 - Data visualization	Integrated JFreeChart dashboards
 - Learning Outcomes

# This project strengthened practical skills in:

- Java GUI development
- Relational database design
- SQL and JDBC
- Software architecture
- Data visualization
- Team collaboration
- Database systems development
  
# Authors

  Developed as part of the COMP306 Database Systems project.

# License

  This project is for educational purposes only.
