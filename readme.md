# Final Project — Sales Control System

Final project developed for the **Algorithms and Programming 2** course, taught by **Professor Eloize Seno**. The goal is to build an application for controlling product sales in a supermarket, using arrays, strings, records, and functions in C.

## Project Objective

The application allows users to:

- Store and manage information about customers, products, and completed sales.
- Perform listing, insertion, update, and deletion operations for each entity (customers, products, sales).
- Generate specific reports about customers, products, and sales based on user-defined criteria.

## Main Features

### Entities and Attributes

1. **Customer**
   - CPF (Primary Key)
   - Name
   - Date of Birth
   - Gender
   - Salary
   - Emails
   - Phone Numbers

2. **Product**
   - Code (Primary Key)
   - Description
   - Size
   - Weight
   - Height
   - Width
   - Price
   - Discount
   - Expiration Date

3. **Sale**
   - Customer CPF (Key)
   - Product Code (Key)
   - Date (Key)
   - Time (Key)
   - Amount

### Menu Options

1. **Customer Submenu**: List, add, update, and delete customers.
2. **Product Submenu**: List, add, update, and delete products.
3. **Sales Submenu**: List, add, update, and delete sales.
4. **Reports Submenu**:
   - Customers with more than X phone numbers.
   - Products with an expired expiration date.
   - Sales between two user-specified dates.
5. **Exit**

### Business Rules

- **Unique keys**: Duplicate values for key attributes are not allowed.
- **Data Persistence**: The system uses files for permanent data storage.
