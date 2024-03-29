# Online Quiz
---
## Screenshots
>**_HOMEPAGE_**
![image](https://user-images.githubusercontent.com/78221502/175472050-6f065a5c-295d-4f17-a22a-d1ec05334f10.png)

>**_ADMIN_PAGE_**
![image](https://user-images.githubusercontent.com/78221502/175472220-7acc9d44-96e1-4fd1-95ea-ef4e4e029089.png)

>**_ADMIN_DASHBOAD_**
>![image](https://user-images.githubusercontent.com/78221502/175473072-05f933dd-0db2-4715-904b-2374f4454e70.png)


>**_STUDENT_DASHBOAD_**
![image](https://user-images.githubusercontent.com/78221502/175472583-09356ccc-159b-497c-b877-1387a996a991.png)

>**_TEACHER_DASHBOARD_**
![image](https://user-images.githubusercontent.com/78221502/175472798-331f0f09-9556-42b0-bead-4d72a2935e16.png)

>**_ABOUT_US_**
![image](https://user-images.githubusercontent.com/78221502/175472870-cf280c6c-3b42-4f0f-a431-d7ea6279e6af.png)



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
---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc 
```
http://127.0.0.1:8000/
```
- Developed by :
Prananjay & Prathmesh
