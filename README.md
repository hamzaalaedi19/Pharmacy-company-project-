
#  Pharmacy Management System (Web Project)

A web-based multi-role management system for a Pharmacy Company. Built using ASP.NET (Web Forms) and Microsoft SQL Server, this system allows HR, Warehouse, Marketing, Delivery staff, and Customers to manage operations based on their roles.

---

##  Overview

This project simulates a real-life pharmacy administration system where:

- Users log in via a unified Login page.
- Based on their role and credentials, users are redirected to their specific home page.
- Each department (HR, Warehouse, Marketing, Delivery) has dedicated functionality for both employees and managers.

---

##  User Roles & Credentials (for testing)

| Role                | Username | Password   |
|---------------------|----------|------------|
| HR Manager          | rami     | rami1234   |
| HR Employee         | ali      | ali1234    |
| Warehouse Manager   | hamza    | hamza1234  |
| Warehouse Employee  | mhd      | mhd1234    |
| Marketing Manager   | mohamad  | mohamad1234|
| Marketing Employee  | osama    | osama1234  |
| Delivery Employee   | baraa    | baraa      |
| Customer            | khalid   | khalid     |

---

##  Project Structure

- Login.aspx — Unified login interface for all users.
- Home.aspx — User dashboard based on role and permissions.
- HR Module:
  - HR employee: Insert & update products (employee_HR.aspx).
  - HR manager: Insert, update, delete, evaluate candidates (ManagerHR.aspx).
- Warehouse Module:
  - Employee: Insert & update products (employeeindex.aspx).
  - Manager: Full CRUD + product evaluation (Index.aspx).
- Marketing Module:
  - Handles orders, cart, showroom display.
- Delivery Module:
  - Employees can update delivery status of orders.
- Customer Module:
  - View products, place orders.

---

##  Technologies Used

- ASP.NET Web Forms (Visual Studio 2022)
- Microsoft SQL Server (SSMS)
- C#
- GridView controls for displaying and editing data

---

##  ERD & Diagrams

The project includes full database diagrams and an ERD for the pharmacy database. (See documentation or .sql files.)

---

##  Contributors & Work Distribution

| Student         
| Hamza Alaedi  
| Mohammad Smadi  
| Rami Yahya       


---

##  Installation & Setup

1. Open solution in Visual Studio 2022.
2. Import the SQL file into Microsoft SQL Server under a database named pharmacy.
3. Update connection strings in Web.config if needed.
4. Run the application locally and test using the credentials above.
