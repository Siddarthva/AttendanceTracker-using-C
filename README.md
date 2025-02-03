Attendance Management System

A Simple and Effective Attendance Tracking Solution

This Attendance Management System is designed to track attendance for multiple subjects, record attendance for each day, and calculate attendance percentages. The system saves attendance data to files for persistent storage and allows you to load previous attendance records.

Key Features

📝 Record Attendance: Record daily attendance for multiple subjects
📅 Track Attendance: Track the number of classes attended and the total number of classes for each subject
📊 Attendance Percentage: Calculate the attendance percentage for each subject and save it to a log
📁 File Persistence: Save subject names, attendance counts, and attendance percentages to files
💻 Flexible Subject Management: Add subjects and track attendance for each subject

System Files

📁 subjects.txt: Stores subject names and attendance data
📝 attendance_percentage.txt: Stores attendance percentages for each subject

How It Works

1. Initialization: Enter the number of subjects and their names on the first run. Attendance data is initialized to 0 for each subject.
2. Recording Attendance: Enter attendance for each subject for a given day. Mark each subject as Present (P) or Absent (A).
3. Saving Data: Save attendance data to subjects.txt and calculate attendance percentages for each subject.

Getting Started

1. Clone or download the repository to your local machine 💻
2. Compile the C code: gcc -o attendance_management attendance_management.c
3. Run the program: ./attendance_management

License

This project is open source and available under the MIT License 📜
