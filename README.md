Problem Statement
The Gym Membership Management System is designed to manage gym operations, including membership plans, members, trainers, gym locations, and class schedules. The system helps in organizing member enrollments, assigning trainers to classes, and managing membership subscriptions. By leveraging SQL commands, we efficiently handle day-to-day tasks like adding or removing members, updating class schedules, and managing payments.

SQL Commands Description
Table Creation:

Creates tables like MembershipPlans, Members, Trainers, Locations, Classes, and MemberClasses with appropriate primary and foreign key constraints to maintain relational integrity.
Data Insertion:

Inserts records into the tables (MembershipPlans, Members, Trainers, etc.) to populate them with sample data like membership plans, member names, trainers, locations, and classes.
Data Update:

Updates specific records. Example: changing a member's membership plan.
Data Deletion:

Deletes records while maintaining referential integrity. Example: removing a class from the schedule after ensuring all related entries are first cleared.
Join Queries:

Retrieves combined data from multiple tables, such as fetching member details along with their assigned membership plans using inner joins.
Screenshots (To be Attached)
Table Creation:

Screenshot of table creation SQL queries (CREATE TABLE statements).
Insert Data Example:

Screenshot of INSERT INTO operations.
Join Query Results:

Screenshot of a query joining Members and MembershipPlans tables to show member names and their plans.
Update and Delete Operations:

Screenshots showing how member plans are updated and how class records are deleted.
Conceptual Diagram:

A diagram visualizing the relationships between the tables (one-to-many between MembershipPlans and Members, many-to-many between Members and Classes).
Explanation of Results and Transactions
Table Creation:
Ensures data is stored efficiently with relationships between tables maintained by foreign keys.

Inserting Data:
Populates the system with essential information like members, plans, and trainers.

Updating Records:
Demonstrates how member data is kept up-to-date, such as modifying a member's plan.

Deleting Records:
Safely deletes records without violating constraints (e.g., class deletion requires prior member-class removal).

Joins:
Retrieves data across related tables, making reporting (e.g., list of members and their plans) simple and clear.

