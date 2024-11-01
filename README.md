# sql-challenge
# Employee Database Analysis

This project uses PostgreSQL (pgAdmin 4) to manage and analyze a relational database containing employee information, such as departments, salariess, titles, and department assignments. The project involves table development, data import from CSV files, and SQL queries to investigate various aspects of the employee data (module 9 challenge).

# Database Structure
The database has the following tables, each having a primary key, a foreign key, and the appropriate constraints for data integrity:

- **departments**: Contains department ID and name.
- **dept_emp**:  Maps employees to their departments.
- **dept_manager**: Lists department managers with their department IDs and employee numbers.
- **employees**: Stores details of employees, including employee number, title ID, birth date, name, sex, and hire date.
- **salaries**: Stores salary information for employees.
- **titles**: Lists job titles and their IDs.

# Data Import

Use pgAdmin's Import/Export tool to load CSV files for each table (found in EmployeeSQL/data).

# SQL Query Descriptions

The following SQL queries are used to analyze the data:

  1. **Employee Details**: Retrieve each employee’s ID, name, sex, and salary.
  2. **Employees Hired in 1986**: List names and hire dates of employees hired in 1986.
  3. **Department Managers**: Retrieve department manager information, including department ID, name, and manager's employee details.
  4. **Employee Department Info**: Retrieve department details for each employee.
  5. **Specific Employee Names**: Find employees named "Hercules" with last names starting with "B".
  6. **Sales Department Employees**: List all employees in the Sales department.
  7. **Sales and Development Departments**: List employees in Sales and Development departments.
  8. **Last Name Frequency**: Count the frequency of each last name in the database.

# Database Integrity and Constraints

  - **Primary Keys**: Ensure unique identification for each record.
  - **Foreign Keys**: Maintain relationships between related tables.
  - **Data Types**: Use appropriate data types for each column (e.g., `VARCHAR(30)` for names).
  - **NOT NULL Constraints**: Enforce mandatory fields for critical data (e.g., department name).

# Conclusion

This project demonstrates the fundamentals of data modeling, data engineering, and SQL querying for real-world data analysis. By creating tables with proper primary and foreign keys, as well as using constraints like NOT NULL and data types, we ensure accurate, organized, and meaningful data retrieval. The queries used here provide thorough insight into employee information, departmental structure, and salary data.


