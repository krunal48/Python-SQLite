# ITC-Data-Science
# ITC-Data-Science

Project:

Design and implement a Complete University Management System in Python using SQLite and functions (def) with the following requirements:
1. Database (SQLite)
Create the following tables:
Departments (dept_id, dept_name, hod_name)
Students (student_id, name, class, dept_id)
Subjects (subject_id, subject_name, dept_id)
Marks (mark_id, student_id, subject_id, marks)
Insert:
At least 2 departments, 5 students, 4 subjects, and marks for each student in all subjects.
2. Python Functions
Implement the following:
def add_student(name, class, dept_id)
def add_subject(subject_name, dept_id)
def add_marks(student_id, subject_id, marks)
def show_students() → Display students with department name (JOIN)
def show_subjects() → Display all subjects with their department
def show_marks() → Display each student’s marks with subject names (JOIN)
def student_report(student_id) → Show subject-wise marks, total, average, grade, pass/fail
def toppers() → Show topper in each subject + overall topper
def department_summary() → Show average marks department-wise (JOIN + GROUP BY)
def unique_subjects() → Return unique subjects as a set

