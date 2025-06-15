# Swim School Administration Console Application (Java 8)

This is a Java 8 console-based administration system designed to manage group swimming lessons, instructors, student qualifications, and waiting lists. The application simulates a weekly swim school operation with three levels of students: Novice, Improver, and Advanced.

---

## Features

- Manage swim students, instructors, and scheduled classes
- Handle lesson assignments and availability
- Record swim qualifications and handle level transitions
- Maintain waiting lists for new or progressing students
- View class, student, and instructor details interactively
- Uses **console I/O only** (no external files or databases)

---

## System Overview

### Swim Levels
- **Novice**
- **Improver**
- **Advanced**

### Days & Time Slots
- Monday, Wednesday, Friday
- Time slots: 17:00 – 19:30 (every 30 minutes)

### Instructors
- Qualified to teach all levels
- Can be assigned to multiple lessons per week

### Students
- Attend **one session per week**
- Can **progress levels** through instructor assessment
- Can be placed on **waiting lists** for level upgrade or entry

---

- **No external files or databases**: all data is coded directly in Java.
- Data added during runtime is **volatile** and will be lost after exit.
- All classes are **well-encapsulated**, with proper object interaction.

