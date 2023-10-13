# Project Report: OIBSIP Level 3 Pizza Delivery Application

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Project Overview](#project-overview)
3. [Objectives](#objectives)
4. [Scope](#scope)
5. [Requirements](#requirements)
6. [Architecture and Design](#architecture-and-design)
   - [System Architecture](#system-architecture)
   - [Database Design](#database-design)
   - [User Interface Design](#user-interface-design)
7. [Technologies Used](#technologies-used)
8. [Implementation](#implementation)
   - [Milestones and Timeline](#milestones-and-timeline)
   - [Development Tools](#development-tools)
9. [Testing](#testing)
   - [Unit Testing](#unit-testing)
   - [Integration Testing](#integration-testing)
   - [User Acceptance Testing](#user-acceptance-testing)
10. [Deployment](#deployment)
11. [Maintenance and Support](#maintenance-and-support)
12. [Conclusion](#conclusion)
13. [Future Enhancements](#future-enhancements)
14. [References](#references)
15. [Appendices](#appendices)

## 1. Executive Summary

The OIBSIP Level 3 Pizza Delivery Application is a full-stack app created using React, MongoDB, and Node.js. It includes both admin and user logins with complete registration, authorization, and email verification. After logging in, users can view the available pizza varieties in the dashboard and proceed to checkout with payment integration using Stripe API in test mode. In test mode, a successful payment leads to the placement and confirmation of the order.

Admin functionality allows for receiving orders and changing the status of the pizza, including order received, in the kitchen, and sent to delivery. All updates made by the admin are reflected in real-time on the user dashboard using Socket.IO.

## 2. Project Overview

The project aims to create a comprehensive pizza delivery application with features for both users and admin. The motivation behind the project is to streamline the pizza ordering and delivery process.

## 3. Objectives

- Develop a full-stack pizza delivery application.
- Implement admin and user login functionality.
- Create a registration system with email verification.
- Display available pizza varieties in the user dashboard.
- Integrate a payment gateway (Stripe API) for order checkout.
- Admin functionalities include order management and status updates.
- Implement real-time status updates for users via Socket.IO.

## 4. Scope

The project includes creating a pizza delivery application with admin and user roles, registration, authorization, and payment integration. The application covers the entire process from order placement to delivery status updates.

## 5. Requirements

The functional and non-functional requirements for this project encompass the following:
- User and admin authentication and authorization.
- User registration with email verification.
- Real-time status updates for orders using Socket.IO.
- Integration with Stripe API for payment processing.

## 6. Architecture and Design

### System Architecture
The application follows a full-stack architecture with React on the front end and Node.js and Express.js on the back end. Socket.IO is used for real-time updates.

### Database Design
The database is MongoDB, and a 'pizza' database with a 'menus' collection stores pizza varieties.

### User Interface Design
The user interface is designed to provide a user-friendly experience for ordering pizzas.

## 7. Technologies Used

The project utilizes the following technologies:
- Node.js
- Express.js
- Socket.IO
- Payment integration with Stripe API

## 8. Implementation

### Milestones and Timeline
The project was developed following a set timeline, with specific milestones achieved at each phase.

### Development Tools
Development tools used during the project include [list your development tools here].

## 9. Testing

Various levels of testing were conducted, including unit testing, integration testing, and user acceptance testing.

## 10. Deployment

The project was deployed with specific server configurations, hosting, and release plans.

## 11. Maintenance and Support

Post-deployment activities include ongoing support, bug fixes, and updates.

## 12. Conclusion

The project successfully developed a pizza delivery application with robust features for both users and admin.

## 13. Future Enhancements

Future improvements may include [list potential future enhancements].

## 14. References

Include relevant sources and documentation used during the project.

## 15. Appendices

Attach supplementary materials such as code snippets and diagrams.

To run this project, follow the installation steps below:

## Installation

1. After downloading or cloning the project, run `npm install` to install all the dependencies.

2. Open a test account in the payment gateway (Razorpay) and paste the secret key in the `.env` file and the publishable key in the resources file.

3. Create a database named 'pizza' in MongoDB and create a collection named 'menus.' Paste the 'menus.json' data into the collection.

4. To run the project, use the command `node server.js` in the terminal.

If you find this repository helpful, don't forget to give it a star ⭐️.
