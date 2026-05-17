

<h1 align="center">Airline Reservation and Ticketing System</h1>

<p align="center">
  A web-based platform for automating airline reservations, ticketing, and administrative operations.
</p>

<p align="center">
  Developed by <strong>Omnira</strong> — Mindanao State University, College of Information and Computing Sciences
</p>

---

## Overview

The Airline Reservation and Ticketing System is a web-based application developed to streamline and automate the complete airline booking process — from flight search to electronic ticket issuance. The system addresses the limitations of traditional manual reservation processes by providing a centralized, secure, and user-friendly platform for both passengers and airline administrators.

---

## Objectives

- Automate core reservation processes including flight search, booking, and payment
- Provide passengers with an intuitive interface for real-time flight booking and seat selection
- Ensure secure handling of user credentials, personal data, and payment information
- Equip administrators with tools to manage flights, bookings, and system reports
- Support scalability for future integration with third-party payment gateways and airline networks

---

## Features

### Passenger-Facing
- **Flight Search & Availability** — Search flights by destination, date, and airline; view flight details including price and seat availability
- **Booking System (PNR Creation)** — Select flights, choose seats, apply promo codes, and automatically generate a unique Passenger Name Record (PNR)
- **Payment Processing** — Secure payment via card or e-wallet with validated receipts upon success
- **E-Ticket Issuance** — Automatic generation and email delivery of electronic tickets upon confirmed payment
- **Booking Retrieval** — Retrieve existing bookings using PNR and last name; option to resend confirmation email

### Admin / Staff Portal
- **Flight Management** — Add, edit, and remove flight schedules
- **Booking Management** — View and manage all passenger bookings
- **Reports and Analytics** — Access booking manifests and sales summaries
- **User Management** — Manage passenger accounts and system access

### Security
- Encrypted user credentials and payment data
- Role-based access control for passengers and administrators
- Compliance with data protection standards

---

## System Actors

| Actor | Description |
|-------|-------------|
| Passenger | Searches, books, and pays for flights; retrieves bookings and e-tickets |
| Admin / Airline Staff | Manages flights, bookings, users, and system reports via a dedicated portal |
| System | Handles automated processes such as PNR generation, notifications, and payment validation |

---

## Use Cases

| ID | Use Case | Actor |
|----|----------|-------|
| UC-001 | Search for Flights | Passenger |
| UC-002 | Book a Flight | Passenger |
| UC-003 | Make a Payment | Passenger |
| UC-004 | Receive E-Ticket | Passenger |
| UC-005 | Manage Flight Schedules | Admin |

---

## Data Entities

- **Users** — Account information for passengers and administrators
- **Flights** — Flight schedules, routes, pricing, and seat inventory
- **Bookings** — PNR records linking passengers to flights, including seat and status
- **Payments** — Transaction records with status (pending, completed, failed)

---

## Reports

| Report | Audience | Description |
|--------|----------|-------------|
| E-Ticket | Passenger | Flight details, PNR, and passenger info; downloadable PDF |
| Booking Manifest | Admin | List of confirmed passengers per flight |
| Sales Summary | Admin | Total bookings and revenue for a given period |

---

## Development Methodology

The system follows an **Incremental and Iterative Development Model**, progressing through the following phases:

1. Planning and Requirement Analysis
2. System Design
3. Implementation and Coding
4. Testing and Quality Assurance
5. Deployment and Integration
6. Maintenance and Support

Documentation adheres to **IEEE 29148** and **IEEE 830** standards.

---

## Team

| Name | Role |
|------|------|
| Mohammad Zulkifli S. Macadato | Team Lead |
| Amber Miguel B. Malinis | Documentation Lead |
| Junnel Francis S. Jonson | Frontend Developer |
| Mohammad Hosni U. Palantig | Backend Developer |
| Aliyah M. Salmorin | QA Tester / UI-UX Designer |
| Ilham O. Gamal | Member |

---

## References

- IEEE Std 29148-2018 — Requirements Engineering
- IEEE Std 830-1998 — Software Requirements Specifications
- ISO/IEC 27001 — Information Security Management Systems
- Sommerville, I. (2015). *Software Engineering*, 10th Edition. Pearson.
- Pressman, R. S. (2019). *Software Engineering: A Practitioner's Approach*. McGraw-Hill.

---

<p align="center">
  Mindanao State University — College of Information and Computing Sciences | CCC181 | November 2025
</p>
