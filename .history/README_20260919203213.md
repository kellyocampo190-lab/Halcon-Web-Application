# Halcon Web Application

Web application proposal for managing and tracking customer orders for Halcon, a construction material distributor.

---

## Academic Information

| **Student** | Giovanna Ocampo Lopez |
| **Student ID** | AL03009988 |
| **Course** | Web Design |
| **Learning Outcome** | Learning Outcome 1 |
| **Lecturer** | Jonathan Alexis Puente Guerrero |

---

## Project Overview

Halcon is a construction material distributor that requires a web application to automate its internal order-management processes.

The proposed application will allow customers to check the status of their orders by entering their customer number and invoice number. Company employees will have access to an administrative dashboard where they can create orders, update their status, manage missing materials, upload delivery evidence, and consult active or logically deleted orders.

---

## Project Objective

The objective of this project is to analyze and design a web application that improves the management and tracking of Halcon’s customer orders.

The system must provide customers with clear information about their orders while allowing the company’s departments to participate in each stage of the order lifecycle.

---

## Main Users

The system will include the following users and roles:

| User or role | Main responsibility |
|---|---|
| **Customer** | Check an order using a customer number and invoice number. |
| **Administrator** | Register users and assign roles. |
| **Sales** | Register customers and create new orders. |
| **Purchasing** | Manage the purchase of materials that are unavailable. |
| **Warehouse** | Prepare orders, report missing materials, and update order statuses. |
| **Route** | Distribute orders and upload photographic evidence. |

Customers will not be able to create accounts or access the administrative dashboard.

---

## Order Lifecycle

Every order must follow the established lifecycle:

1. **Ordered:** The salesperson registers the order in the system.
2. **In process:** Warehouse prepares the order or requests missing materials from Purchasing.
3. **In route:** The order is loaded and assigned for distribution.
4. **Delivered:** The material is delivered and photographic evidence is uploaded.

An order must not skip any of these stages.

---

## Main Functional Requirements

### Customer order tracking

The customer will enter:

- Customer number.
- Invoice number.

The system will display:

- Current order status.
- Delivery evidence when the status is `Delivered`.

### Administrative dashboard

Authorized employees will be able to:

- Log in to the administrative dashboard.
- View active orders.
- Search by invoice number, customer number, date, or status.
- Open and update order information.
- Change an order’s status.
- Logically delete an order.
- View deleted orders.
- Restore a deleted order.


---

## Work Methodology

### Kanban

Kanban was selected as the work methodology for this project. It provides a visual and simple way to organize the activities required for the analysis and design of the Halcon web application.

The project will be managed using GitHub Projects connected to this repository. Each activity will be represented by an issue or project item and will move across the board according to its progress.

The Kanban board will use the following columns:

| Column | Purpose |
|---|---|
| **Backlog** | Activities identified but not yet scheduled. |
| **To do** | Activities ready to be started. |
| **In progress** | Activities currently being developed. |
| **Review** | Activities waiting to be checked against the requirements and rubric. |
| **Done** | Activities that have been completed and reviewed. |

Kanban is appropriate for this project because it makes progress visible, helps organize priorities, and allows each diagram or document to be reviewed before it is considered complete.

---

## GitHub Project Board

The project activities are organized in a GitHub Projects Kanban board.

[Open the Halcon Kanban board]
(https://github.com/users/kellyocampo190-lab/projects/2/views/1?system_template=kanban)

---

## Planned Activities

- [ ] Analyze the project requirements.
- [ ] Create the GitHub repository.
- [ ] Complete the descriptive README.
- [ ] Configure the GitHub Projects Kanban board.
- [ ] Create the BPMN diagram.
- [ ] Create the use case diagram.
- [ ] Create the activity diagram.
- [ ] Create the class diagram.
- [ ] Create the entity-relationship diagram.
- [ ] Create the database data dictionary.
- [ ] Complete the final reflection.
- [ ] Review the project using the evaluation rubric.

---

## Diagrams

### BPMN Diagram

The BPMN diagram will describe the complete business process, from the moment a customer places an order until the material is delivered.

*Diagram pending.*

### Use Case Diagram

The use case diagram will represent the actors, their permissions, and their interactions with the system.

*Diagram pending.*

### Activity Diagram

The activity diagram will show the decisions and activities involved in the order lifecycle.

*Diagram pending.*

### Class Diagram

The class diagram will describe the main classes, attributes, methods, and relationships required by the application.

*Diagram pending.*

### Entity-Relationship Diagram

The entity-relationship diagram will show the database entities, attributes, data types, keys, relationships, and cardinalities.

*Diagram pending.*

---

## Database Design

The database design will include the information required to manage:

- Users and roles.
- Customers.
- Orders.
- Products and order details.
- Order statuses.
- Status history.
- Photographic evidence.
- Purchase requests.
- Logically deleted orders.

The database documentation and data dictionary will be stored in the `database` folder.

---

## Repository Structure

```text
Halcon-Web-Application/
├── README.md
├── database/
│   └── data-dictionary.md
├── diagrams/
└── documentation/
    ├── methodology.md
    └── reflection.md
```

- `README.md` contains the general project documentation.
- `database` contains the database design documentation.
- `diagrams` will contain all exported diagrams.
- `documentation` contains the methodology and final 


