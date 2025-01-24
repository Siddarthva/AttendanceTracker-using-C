Attendance Management System 📚

This is a simple Attendance Management System implemented in C. The program tracks attendance for multiple subjects, records attendance for each day, and calculates attendance percentages. It saves attendance data to files for persistent storage and allows you to load previous attendance records.

Features 📝

- Record Attendance: The system allows recording daily attendance for multiple subjects 📅
- Track Attendance: It tracks the number of classes attended and the total number of classes for each subject 📊
- Attendance Percentage: Calculates the attendance percentage for each subject and saves it to a log 📝
- File Persistence: Saves subject names, attendance counts, and attendance percentages to files, which can be loaded and updated across sessions 💻
- Flexible Subject Management: You can add subjects, and the system keeps track of attendance for each subject 📚

Files Used 📁

- subjects.txt: Stores the subjects and their attendance data (present and total counts) 📝
- attendance_percentage.txt: Stores the attendance percentage for each subject on each day 📊

How It Works 🤔

1. Initialization: On the first run, you will be prompted to enter the number of subjects and their names. Attendance data is initialized to 0 for each subject 📊
2. Recording Attendance: The program prompts you for the day and asks you to enter attendance for each subject. You can mark each subject as Present (P) or Absent (A). The attendance for each subject is updated 📅
3. Saving Data: After recording the attendance, the data is saved to subjects.txt. The attendance percentage for each subject is calculated and logged in attendance_percentage.txt 📝

Getting Started 🚀

To run this program:

1. Clone or download the repository to your local machine 💻
2. Compile the C code:

gcc -o attendance_management attendance_management.c

3. Run the program:

./attendance_management


License 📜

This project is open source and available under the MIT License.
