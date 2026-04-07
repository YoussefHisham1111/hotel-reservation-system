# 🏨 Hotel Reservation System

**Course:** CSE241 Object-Oriented Computer Programming  
**University:** Faculty of Engineering, Ain Shams University  
**Semester:** 2nd Semester 2025/2026  

---

## 👥 Team Members

| Name | ID | GitHub Username | Responsibility |
|------|----|----------------|----------------|
| Youssef AlaaElDin Nabil | 25P0163 | @username1 | Guest class + Payable interface |
| Youssef Hisham Abdaltwab | 25P0118 | @username2 | Admin, Receptionist, Staff |
| Omar Khaled Mohamed | 25P0110 | @Omarsawy119-web | Room, RoomType, Amenity |
| Ali Mohamed Hassan | 25P0107 | @NotAliX1 | Reservation, Invoice, Enums |
| Omar Ali Sayed | 25P0282 | @T0as1 | HotelDatabase + UML + Report |

---

## 📁 Project Structure
```
src/
├── interfaces/
│   ├── Payable.java
│   └── Manageable.java
├── enums/
│   ├── Gender.java
│   ├── Role.java
│   └── ReservationStatus.java
├── Guest.java
├── Staff.java
├── Admin.java
├── Receptionist.java
├── Room.java
├── RoomType.java
├── Amenity.java
├── Reservation.java
├── Invoice.java
├── HotelDatabase.java
└── Main.java
```
---

## 🚀 How to Run

1. Clone the repository:
  git clone https://github.com/T0as1/hotel-reservation-system.git
2. Open the project in IntelliJ IDEA or Eclipse
3. Navigate to `src/Main.java`
4. Run `Main.java`

> No external libraries are required. Pure Java only for Milestone 1.

---

## 📌 Milestones

| Milestone | Description | Due Date | Status |
|-----------|-------------|----------|--------|
| Milestone 1 | OOP Backend — all Java classes, UML diagram, report | April 24, 2026 | 🔄 In Progress |
| Milestone 2 | JavaFX GUI + Multithreading + Java Sockets | April 30, 2026 | ⏳ Not Started |

---

## 🌿 Branch Strategy

| Branch | Purpose |
|--------|---------|
| `main` | Final stable version — only updated after each milestone |
| `milestone-1` | Integration branch for Milestone 1 |
| `milestone-2` | Integration branch for Milestone 2 |
| `feature/guest-class` | Member 1 workspace |
| `feature/admin-receptionist` | Member 2 workspace |
| `feature/room-roomtype` | Member 3 workspace |
| `feature/reservation-invoice` | Member 4 workspace |
| `feature/database-uml` | Member 5 workspace |

---

## 🛠️ Technologies Used

- Java (Milestone 1)
- JavaFX — GUI (Milestone 2)
- Java Sockets — Networking (Milestone 2)

---

## 📄 Deliverables

- [ ] Source code (.zip)
- [ ] Project report (.docx)
- [ ] UML Class Diagram
- [ ] GitHub repository
- [ ] YouTube demo video — link coming soon

---

## 🎨 OOP Concepts Used

- **Inheritance** — Admin and Receptionist extend Staff
- **Abstraction** — Staff is an abstract class
- **Interfaces** — Payable, Manageable
- **Encapsulation** — all fields are private with proper access
- **Enums** — Gender, Role, ReservationStatus
- **Composition** — Room contains RoomType and a list of Amenities
