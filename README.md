# Exam.MCQ
An innovative online MCQ (Multiple Choice Question) exam platform.
The platform's main objective is to enable teachers to create MCQ-based exams,
while providing users with the opportunity to participate in these online exams in real-time.

# Features and Functionalities
1. Exam Creation: Teachers should have the ability to create exams with
multiple-choice questions, set the time duration for the exam, and
define the number of questions.

2. Real-time MCQs: Users should be able to answer the multiple-choice
questions in real-time during the exam.

3. Solo or Group Participation: Users should have the option to take
exams individually or in groups.

4. Competitive Environment: In group exams, participants should be able
to view each other's progress and scores in real-time, encouraging
healthy competition.

5. Instant Results: Users should receive their exam results immediately
after completing the exam.

6. Secure and Reliable: The platform should be secure, reliable, and
able to handle multiple users simultaneously.

7. User-friendly Interface: The platform should have an intuitive and
user-friendly interface for both teachers and users.
---
## screenshots
### Homepage
![homepage](https://github.com/bhaveshjain144/mcqexam/blob/main/static/screenshots/homepage.png)
### Admin Dashboard
![dashboard](https://github.com/bhaveshjain144/mcqexam/blob/main/static/screenshots/admin/admin_dashboard_page.png)
### Exam Rules
![exam rules](https://github.com/bhaveshjain144/mcqexam/blob/main/static/screenshots/student/student_exam_rules_page.png)
### Exam
![exam](https://github.com/bhaveshjain144/mcqexam/blob/main/static/screenshots/student/student_take_exam_page.png)
### Teacher
![teacher](https://github.com/bhaveshjain144/mcqexam/blob/main/static/screenshots/teacher/teacher_question_page.png)
---
## Functions
### Admin
- Create Admin account using command
```
py manage.py createsuperuser
```
- After Login, can see Total Number Of Student, Teacher, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete, Approve Teacher.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Teacher
- Apply for job in System. Then Login (Approval required by system admin, Then only teacher can login).
- After Login, can see Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.
> **_NOTE:_**  Basically Admin Will Hire Teachers To Manage Courses and Questions.

### Student
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.
