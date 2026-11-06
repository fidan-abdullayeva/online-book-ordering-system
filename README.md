# Online Book Ordering System

## Project Overview
An individual educational IT Business Analysis project focused on designing an online book ordering system.
The project aims to replace the traditional order management process, which relies on phone calls, WhatsApp messages, and manual Excel records, with a structured online ordering system.

## Project Objectives
- Define the main functionality of an online book ordering system.
- Design a relational database structure for managing books, customers, and orders.
- Define REST API endpoints for the main system operations.
- Prepare JSON request and response examples.
- Document API parameters, schemas, and error handling.

## Project Scope
The project covers the following functionalities:
- Displaying book categories and sections on the home page.
- Viewing detailed information about individual books.
- Creating orders with delivery and payment information.
- Tracking order status and delivery details.
- Cancelling orders and displaying refund information.

## Database Design
The database structure was designed using DBML and visualized with dbdiagram.io.
The database model includes the following entities:
- Books
- Customers
- Cards
- Reviews
- Orders
- OrderItems
The database design defines primary keys, foreign keys, and relationships between entities.

## API Design & Documentation
REST API endpoints were defined and documented for the main system operations.
The documentation includes HTTP methods, endpoint descriptions, path parameters, header parameters, JSON request and response bodies, schemas, and error handling.

### Documented Endpoints
| Method | Endpoint | Description |
|---|---|---|
| GET | `/home` | Retrieves home page data, including book sections and categories. |
| GET | `/books/{book_id}` | Retrieves details of a specific book. |
| POST | `/orders` | Creates a new order. |
| GET | `/orders/{order_id}/tracking` | Retrieves order tracking information. |
| DELETE | `/orders/{order_id}` | Cancels an existing order. |

## Tools & Technologies
- dbdiagram.io – Database modeling and visualization.
- DBML – Database structure definition.
- Postman – API request practice.
- JSON – Request and response data structures.
- REST API – API methods and endpoint design.
- Microsoft Word – API documentation.

## Project Status
Educational individual project developed as part of IT Business Analysis coursework.
The project focuses on database modeling and API design and documentation. It is not a deployed application or a live API.
