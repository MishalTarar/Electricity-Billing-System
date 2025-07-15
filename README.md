# Electricity Billing System - Java + MySQL

A desktop-based application that simulates an electricity billing system. Built using **Java Swing** for GUI and **MySQL** for data management.

## Features
- User Login and Signup
- Add New Customer with Meter Info
- Calculate Monthly Electricity Bill
- View & Pay Bills
- Generate PDF-style Bill Reports
- Update/View Customer Info

## Tech Stack
- Java (Swing for GUI)
- JDBC (Database Connection)
- MySQL

## How to Run
1. Clone this repo
2. Import into any Java IDE (e.g., NetBeans or IntelliJ)
3. Setup MySQL Database:
    - Import `electricity.sql` or create tables manually
4. Update database credentials in `database.java`
5. Run `main_class.java`

## Project Structure
- `Login.java`: User authentication
- `Signup.java`: New user registration
- `newCustomer.java`: Add customer details
- `calculate_bill.java`: Generate bill based on units
- `generate_bill.java`: View bill report
- `pay_bill.java`: Payment section
- `database.java`: MySQL connection

## Author
[Mishal Tarar](https://linkedin.com/in/mishal-tarar-850600235/)
