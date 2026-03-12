# Automated Attendance System – UI/UX Design

This repository contains the **UI/UX design prototype of an Automated Attendance System**, created using Figma.
The system is designed to simplify attendance management in educational institutions by combining **hardware-based attendance capture** with a **web interface for students, teachers, and administrators**.

---

## System Overview

The Automated Attendance System uses a **dedicated hardware device** distributed by the teacher during class.
Students use the device to verify their attendance through a **QR code scan and facial verification process**.

### Hardware Process

1. The **teacher distributes the attendance device** to students at the beginning of the class.
2. Each student:

   * Scans the **QR code on their ID card**.
   * The device captures the **student's face** and performs a **liveness check** to confirm identity.
3. Once all students have marked their attendance, the **device is collected back by the teacher**.
4. The attendance data is then synchronized with the system and displayed on the web interface.

This approach helps prevent **proxy attendance and identity misuse**.

---

## Key Features

### Attendance Marking

* Attendance recorded automatically with **date and time**.
* **QR code scanning** using student ID cards.
* **Face verification with liveness detection** to confirm identity.
* Instant confirmation after successful attendance submission.

### Department & Section Management

* Select **Department**, **Year**, and **Section**.
* Manage large groups of students efficiently.

### Timetable Display

* View **day-wise class timetable** in a structured format.
* Easy navigation between different days.

### Attendance Reports

* Detailed attendance history for each student.
* Visual representation of attendance percentage.

### Secure Login System

* Username and password authentication.
* Role-based system for **Student**, **Teacher**, and **Admin**.

---

# User Roles

## Student Dashboard

Students can log in to the website and:

* View **daily attendance records**
* View **total attendance percentage**
* Receive visual indicators:

  * 🟢 **Green indicator** – Attendance **above 75%**
  * 🔴 **Red indicator** – Attendance **below required limit**
* Track their attendance status easily.

---

## Teacher Dashboard

Teachers have access to tools that help manage attendance during classes:

* View **attendance of the entire class**
* View **class timetable**
* Start and manage **attendance sessions**
* Monitor student attendance status
* **Report system issues or disruptions** to the administrator if any problem occurs during attendance recording.

---

## Admin Dashboard

Administrators manage the overall system:

* View **attendance records of all students**
* **Add or remove students** from the system
* Manage departments and sections
* Send **notifications or warnings to students with low attendance**
* Handle reports submitted by teachers.

---

## Figma Prototype

The interactive UI/UX prototype can be viewed here:

**Figma Design Link:**
https://embed.figma.com/proto/d6vc7FUDoTOIuYJ7HN8Jx1/Attendance_webView?node-id=5-2&starting-point-node-id=5%3A2&embed-host=share

---

## UI Preview

Screenshots of the interface are available in the `images` folder.

---

## Project Purpose

This project demonstrates a **conceptual design of a smart attendance management system** that integrates **hardware-based identity verification with a web-based monitoring interface**.

The design focuses on:

* improving attendance accuracy
* preventing fraudulent attendance
* providing clear analytics for students, teachers, and administrators.

---
