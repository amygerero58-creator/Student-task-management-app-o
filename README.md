# Student-task-management-ap
# application description
tudent Task Management App is a standalone Python application designed to help students organize their academic tasks, schedules, deadli# applines, and notes in one centralized system.:
# application allows users to
•Create and manage tasks, including deleting and marking them as 
completed.
• Organize schedules by assigning tasks to specific dates and times.
•Store and manage short notes for reminders or important information.
This project demonstrates core Object-
.Through this application, students can improve time management, track 
academic responsibilities, and increase productivity.
• View a summarized dashboard that presents all tasks, notes, and schedules 
in a structured format. And can export the report to a .txt file.

Built with a clean graphical interface,the system focuses On simplicity,
efficiency and accessibility it operates offline and follows the input >process> 
output model for reliable performance

•Through this application, students can improve time management, track rack 
academic responsibilities, and increase productivity
# OOp concepts used
Oriented Programming principles:
• Encapsulation: Private attributes using _variable
• Abstraction: Interface classes define standard methods.
• Polymorphism: Different services implement the same interface methods
•modularity
# technology used
•Python (core programming language)
• GUI framework (Tkinter)
• Object-Oriented Programming (OOP)
# projects structure
StudentTaskManager/
│
├── interfaces/
│   └── data_service.py
│
├── models/
│   ├── student.py
│   ├── task.py
│   ├── subject.py
│   ├── schedule.py
│   └── note.py
│
├── services/
│   ├── task_service_impl.py
│   ├── subject_service_impl.py
│   ├── schedule_service_impl.py
│   ├── notes_service_impl.py
│   └── report_service.py
│
├── ui/
│   └── main_gui.py
│
├── tests/
│   └── test_services.py
│
├── data/
│   ├── tasks.txt
│   ├── schedules.txt
│   └── notes.txt
│
├── main.py
│
└── report.txt (generated after export)
