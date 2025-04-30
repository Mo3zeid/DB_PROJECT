# 📚 Library Management System

A comprehensive **Library Management System** designed for academic purposes to manage books, members, staff, borrowing processes, and more. This project was developed as part of a Database Systems course and showcases a fully normalized relational schema with rich entity relationships.

---

## 🚀 Features

- **Book Management**  
  Track book metadata (ISBN, title, edition, language, year) and link to authors, publishers, genres, shelves, and vendors.

- **Membership Management**  
  Support various membership types, preferred genres, and detailed member profiles.

- **Borrowing & Fines**  
  Borrowing tracking with due dates, status updates, automated fine calculations, and payment processing.

- **Branch & Shelf Organization**  
  Organize branches, rooms, and shelves with capacity and location metadata.

- **Staff & Roles**  
  Manage staff data with assigned branches and role-based access control.

- **Vendor Management**  
  Track vendor contracts, products supplied, and borrowing-related financial transactions.

- **Book Clubs**  
  Manage book clubs, schedules, and member participation.

---

## 🧾 Database Design

The system includes 24 relational tables with normalized attributes and constraints:

- **Core Entities**: Book, Author, Publisher, Vendor, Genre  
- **Operations**: Borrowing, Payment, Fines, Feedback  
- **User Management**: Member, Membership, Staff, Role  
- **Structure**: Branch, Room_Category, Shelf  
- **Activities**: BookClub, BookClub_Activities, MemberBookClub  
- **Join Tables**: BookGenre, BookBranch, BookBorrow

Each table is designed with appropriate keys, constraints, and foreign key relationships for optimal performance, scalability, and integrity.

---

## 👥 Project Team

- **Hossam Mohamed Ibrahim** – 320220247  
- **Anass Ehab Einshouka** – 320220199  
- **Mahmoud Omar Elkhaligy** – 320220188  
- **Moaz Mohamed Mahmoud Eid** – 320220196  
- **Seifeldeen Usama Khaled** – 320220226  

---

## 📌 Note

This project was created for educational purposes and demonstrates the design and planning of a database-driven library management system, including ER modeling, normalization, and schema design.


