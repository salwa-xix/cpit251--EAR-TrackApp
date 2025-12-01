# cpit251--EAR-TrackApp
TrackApp is a Java-based laundry management system that allows customers to create orders, track their cleaning progress, and receive their items directly from the laundry.

# TrackApp – Laundry Tracker Application

TrackApp is a Java-based laundry management system that helps laundry shops manage customer orders, update order status, and improve communication between employees and customers. The system allows employees to create and edit orders, while customers can track their order status, view order history, receive notifications, and rate the service after pickup.

This project was developed as part of the CPIT 251 – Software Engineering course using the Extreme Programming (XP) methodology.

## Main Features

- Create a new laundry order with customer details and service type  
- Edit order information before processing starts  
- Update order status through different stages (Created, In Progress, Ready, Completed)  
- Track the current status of an order  
- Cancel an order before it enters the "In Progress" stage  
- Receive notifications when the order status changes  
- View order history  
- Rate the service after the order is completed  
- View business reports (for employees)

_All features are based on the functional requirements and use case models in our SE report._

## Technology Stack

- **Language:** Java  
- **Paradigm:** Object-Oriented Programming (OOP)  
- **Architecture:** Modular design with separate components for orders, rating, notifications, and reports (as shown in our architecture diagrams)  
- **Data Storage:** Text files (or simple local storage) for orders, notifications, and reports

## Development Process (XP)

We followed a simplified Extreme Programming (XP) process:

- Defined the core system functions (create order, edit, update status, track order, cancel, notifications, history, rating, reports)
- Divided work into small iterations and tasks among team members
- Used pair programming for implementing core functions
- Continuously reviewed and refined our diagrams and code

In GitHub, XP is reflected through:

- **User stories** created as GitHub Issues  
- **Tasks** represented as checklists inside each Issue  
- **Assignees** to show which team members worked on each story  
- A **Project board** (Backlog → In Progress → In Review → Done) to track progress

## Team Members

- Salwa  Abdulrahim 
- Jana Bajaba
- Razan Aljezani
- Joud Ali 
- Mawadah Alahmadi 

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/Laundry-Tracker-TrackApp.git
