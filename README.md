## Schoolmanagement

[![Button](https://img.shields.io/badge/Develop_by:-submit_Kumar-red)](https://www.passerellesnumeriques.org/what-we-do/cambodia/)



## screenshots

### Homepage

![Dashboard](./Screenshot-2025-02-18-151629-1024x563.png)

### Admin Dashboard

![Dashboard](./Screenshot-2025-02-18-150900-1024x576.png)

### Admin Manage Teacher

![Dashboard](./School-Management-System-in-Django-Manage-Student.png)

### Attendance

![Dashboard](./School-Management-System-in-Django-Attendance.png)


## Functions

### Teacher

First the teacher will apply for job,if he/she gets selected there accounts will be made and approved by the admin, after approval only teacher can access their dashboard. After account approval by admin, teacher can take attendance of any class and view their attendance later. Teacher can also publish/announce notice to student like submission of assignments.

## Student

First student will take admission/signup. When their account is approved by admin, only then the student can access their dashboard. After account approval by admin the student can view their details like attendance. Student can't view attendance of other student. Student can't announce, they can only view.

### Admin

First admin will signup for a account. After login they can see how many student/teacher wants to get job/admission in their school. They can approve or delete/cancel the request. They can update any student/teacher details. Admin can announce notice also.

## Drawbacks

- On update page of teacher/student you must have to update password.
- Anyone can become Admin

# HOW TO RUN THIS PROJECT

- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :

`python -m pip install -r requirements.txt`
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands:

```python
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc

```python
http://127.0.0.1:8000/

```
# CHANGES REQUIRED FOR CONTACT US PAGE

- In settins.py file, You have to give your email and password


```python
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'

```
- Login to gmail through host email id in your browser and open following link and turn it ON

```python
https://myaccount.google.com/lesssecureapps
```
## Disclaimer

This project is developed for demo purpose and it's not supposed to be used in real application.

## Feedback

Any suggestion and feedback is welcome. You can message me on facebook

-  [Tailwindcss](https://www.w3schools.com/tags/tag_form.asp)
-  [Tailwindcss](https://www.youtube.com/)