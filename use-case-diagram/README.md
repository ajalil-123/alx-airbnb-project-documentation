# 🧩 Airbnb Clone - Use Case Diagram Documentation

## 🎯 Objective

This README outlines the steps I followed to create a **Use Case Diagram** for the **Airbnb Clone backend project** using **Draw.io**. The diagram visualizes how different users (guests, hosts, and admins) interact with core system functionalities such as user registration, booking, and payments.

---

## 🧱 Tools Used

- [Draw.io (diagrams.net)](https://draw.io) for creating the UML Use Case Diagram
- Exported as: `use_case_diagram.png`
- Stored in the directory: `use-case-diagrams/`

---

## 👥 Actors Identified

I identified the following primary **actors** (users of the system):

- **Guest** – a user looking to book properties
- **Host** – a user listing properties for rent
- **Admin** – a user managing the platform
- *(Optional)*: **Payment Gateway** for handling transactions

---

## 🧩 Use Cases Included

I mapped out all essential backend features into **use cases (functional actions)** for each actor:

### For Guests
- Register
- Login
- Search Listings
- Book Property
- Cancel Booking
- Make Payment
- Leave Review
- Receive Notifications

### For Hosts
- Register
- Login
- Add Property Listing
- Edit Listing
- Delete Listing
- View Bookings
- Receive Payout
- Respond to Reviews
- Receive Notifications

### For Admin
- Manage Users
- Manage Listings
- Manage Bookings
- View Payments

---

## 📐 Diagram Layout & Design

I followed these steps in **Draw.io**:

1. Enabled the **UML shape library** from the left panel.
2. Added **stick figures** for each actor (Guest, Host, Admin).
3. Drew **ovals** representing each system use case (e.g., Register, Book Property, Make Payment).
4. Connected each actor to their respective use cases using solid **association lines**.
5. Organized actors into columns to clearly separate their roles and interactions.
6. Grouped related use cases visually (e.g., booking-related actions together).

---

## 📁 File Structure

```bash
alx-airbnb-project-documentation/
└── use-case-diagrams/
    └── use_case_diagram.png
    └── README.md 