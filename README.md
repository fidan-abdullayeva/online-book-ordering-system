Online Book Ordering System

Project Overview

An individual educational IT Business Analysis project focused on designing an online book ordering system. The project aims to replace the traditional order management process, which relies on phone calls, WhatsApp messages, and manual Excel records, with a structured online ordering system.

Business Problem

The existing order management process relies on manual communication channels and Excel records. This approach can lead to inefficient order processing, difficulties in tracking orders, and limited visibility into order information.

The proposed system aims to centralize the ordering process and improve order management through a structured online platform.

Project Objectives

- Define the main functionality of an online book ordering system.
- Analyze business requirements and stakeholder needs.
- Model business processes using BPMN.
- Design UML Use Case Diagrams.
- Design a relational database structure for managing books, customers, and orders.
- Define REST API endpoints for the main system operations.
- Prepare JSON request and response examples.
- Document functional and non-functional requirements.
- Define acceptance criteria and identify potential edge cases.

Project Scope

The project covers the following functionalities:

- Displaying book categories and sections on the home page.
- Viewing detailed information about individual books.
- Creating orders with delivery and payment information.
- Tracking order status and delivery details.
- Cancelling orders and displaying refund information.

Requirements Analysis

The project documentation includes:

- Project Overview
- Business Problem
- Business Objectives
- Project Scope
- Stakeholder Analysis
- Functional Requirements
- Non-Functional Requirements
- Use Case Specifications
- Edge Cases
- Acceptance Criteria

Process Modeling (BPMN)

Business processes are modeled using BPMN diagrams to illustrate the flow of activities, system interactions, decision points, and alternative process paths.

The process modeling documentation includes individual BPMN diagrams in PNG format and a consolidated PDF document.

UML Modeling

A UML Use Case Diagram illustrates the interactions between system actors and the main system functionalities.

Database Design

The database structure was designed using dbdiagram.io and includes the following entities:

- Books
- Customers
- Cards
- Reviews
- Orders
- OrderItems

The database model defines primary keys, foreign keys, and relationships between entities.

API Design & Documentation

REST API endpoints were defined and documented for the main system operations.

The API documentation includes HTTP methods, endpoint descriptions, path parameters, header parameters, JSON request and response bodies, schemas, and error handling.

Documented Endpoints

Method| Endpoint| Description
GET| "/home"| Retrieves home page data, including book sections and categories.
GET| "/books/{book_id}"| Retrieves details of a specific book.
POST| "/orders"| Creates a new order.
GET| "/orders/{order_id}/tracking"| Retrieves order tracking information.
DELETE| "/orders/{order_id}"| Cancels an existing order.

JSON Examples

Separate JSON examples demonstrate request and response data structures for the documented API endpoints.

Tools & Technologies

- Lucidchart – BPMN business process modeling.
- draw.io (diagrams.net) – UML Use Case Diagram design.
- dbdiagram.io – Database modeling and ERD visualization.
- Postman – API request practice and testing.
- REST API – API endpoint design and documentation.
- JSON – Request and response data structures.
- Microsoft Word – Project and API documentation.

Project Status

Educational individual project developed as part of IT Business Analysis coursework.

The project covers business analysis, requirements engineering, process modeling, UML modeling, database design, and API documentation.

It is a documentation and system design project, not a deployed application or a live API.
