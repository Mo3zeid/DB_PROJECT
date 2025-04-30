# 📚 Library Management System

A comprehensive **Library Management System** developed as a university database course project. It manages library resources, borrowing, memberships, staff, vendors, and book club activities through a relational database model.

---

## 🚀 Features

- **Book Management**  
  Store and organize book metadata and link to authors, publishers, genres, shelves, and vendors.

- **Membership Management**  
  Handle member registrations, preferred genres, and membership types with feedback support.

- **Borrowing & Fines**  
  Enable book borrowing/returning, fine calculation, and payment tracking.

- **Branch & Shelf Management**  
  Allocate books across multiple branches, rooms, and shelves with capacity planning.

- **Staff & Role Control**  
  Assign roles and manage staff permissions and branch assignments.

- **Vendor Management**  
  Maintain vendor profiles, contracts, and supplied resources.

- **Book Club Integration**  
  Create and manage book clubs, member participation, and scheduled activities.

---

## 🧾 Database Design

Includes 24 normalized entities with keys, constraints, and foreign key relationships:

- **Core Entities**: `Book`, `Author`, `Publisher`, `Genre`, `Vendor`
- **Users & Access**: `Member`, `Membership`, `Staff`, `Role`
- **Operations**: `Borrowing`, `Payment`, `Fines`, `Feedback`
- **Structure**: `Branch`, `Room_Category`, `Shelf`
- **Clubs**: `BookClub`, `BookClub_Activities`, `MemberBookClub`
- **Join Tables**: `BookGenre`, `BookBranch`, `BookBorrow`

---

## 📎 Project Files

- 📄 `ERD.pdf` – Visual representation of the database schema  
- 📄 `Schema.pdf` – Mapping from business rules to relational schema  
- 💾 `FinalSQLTables.sql` – SQL script to create the full database schema  
- 📄 `Database System Project.docx` – Full project documentation

> ⚠️ Make sure to run the SQL script in a compatible RDBMS such as Microsoft SQL Server or MySQL (with adjustments if needed).

---

## 👥 Project Team

- **Hossam Mohamed Ibrahim** – 320220247  
- **Anass Ehab Einshouka** – 320220199  
- **Mahmoud Omar Elkhaligy** – 320220188  
- **Moaz Mohamed Mahmoud Eid** – 320220196  
- **Seifeldeen Usama Khaled** – 320220226  

---

## 📌 Note

This academic project demonstrates database design principles, including ER modeling, normalization, and SQL implementation. It's intended for learning and educational purposes.

