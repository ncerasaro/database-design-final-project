# database-design-final-project
final project for database design class based on internship



# Internship-Themed Business Database Project

This project is a final project for Database Design. It is a mock relational database based on my internship experience and focuses on tracking employee AI use submissions, help desk tickets, AI tools, sales forecasts, and forecast results across departments.

## Project Purpose

The purpose of this project is to model how a company could organize and track business data related to AI usage, support requests, and sales forecasting. The project connects to my internship experience because I worked in IT and explored different ways AI could be used across departments.

## Tables Included

- Departments
- Employees
- AI_Tools
- AI_Use_Submissions
- Help_Desk_Tickets
- Ticket_Updates
- Sales_Forecasts
- Forecast_Results

## Repository Contents

- `sql/create_tables.sql` – SQL used to create the tables
- `sql/business_queries.sql` – SQL used for business query results
- `data/` – CSV files used to populate the database
- `docs/` – project documentation
- `screenshots/` – screenshots of pgAdmin tables and query results

## How to Run the Project

1. Create a new database in pgAdmin/PostgreSQL.
2. Run `create_tables.sql` to create the tables.
3. Import each CSV into the matching table.
4. Run the queries in `business_queries.sql`.

## Author

Nicholas Cerasaro  
Database Design Final Project
