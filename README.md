Hospital Patient Management System


1. Introduction
The Hospital Patient Management System is a console-based C++ application designed to streamline hospital operations involving patient registration, categorization, and discharge tracking. It supports two patient types: emergency and normal. Emergency patients are treated with priority and incur higher charges, while normal patients follow a queue-based system.

2. Objective
To create a simple, efficient, and functional system that manages patients through stacks, queues, and linked lists, while also incorporating revenue tracking and preventing duplicate entries through ID validation.

3. System Features

Patient Registration: Records patient name, age, ID, and phone number.

ID Validation: Ensures no two patients share the same ID.

Emergency Stack: Uses a LIFO stack to manage emergency cases.

Normal Queue: Uses a FIFO queue for normal cases.

Discharged List: Tracks all discharged patients using a linked list.

Revenue Tracking: Calculates total revenue ($10 per emergency, $5 per normal patient).

4. Data Structures Used

Stack (Emergency Patients): Prioritizes urgent cases.

Queue (Normal Patients): Processes patients in the order they arrive.

Linked List (Discharged Patients): Stores and displays patient discharge records.

5. Flow of the Program

User inputs number of patients.

For each patient: name, age, ID, phone, and type (emergency/normal) are collected.

System checks for unique ID.

Based on type:

Emergency patients are pushed to the stack.

Normal patients are enqueued.

Patients are treated and added to the discharged list.

Total revenue is calculated and displayed.

6. Benefits

Improved patient handling through organized data structures.

Faster treatment process for emergency patients.

Reduced manual tracking through digital discharge records.

Revenue transparency and management.

7. Conclusion
This project combines real-world hospital workflow concepts with essential programming techniques in C++. The implementation of stack, queue, and linked list reinforces data structure knowledge while solving a practical problem.

