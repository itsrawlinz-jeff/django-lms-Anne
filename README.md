# MODULE ATTENDANCE TOOL INTERGRATION WITH LEARNING MANAGEMENT SYSTEM
#ANNE ATIENO: BBIT/14548/1/19
#SUPERVISOR: MADAM SHEILAH MIRENJA
#A RESEARCH PROPOSAL SUBMIT TO THE DEPARTMENT OF COMPUTING AND INFORMATION TECHNOLOGY IN PARTIAL FULFILLMENT FOR THE AWARD OF BACHELORS OF BUSINESS INFORMATION TECHNOLOGY OF PAN AFRICA CHRISTIAN UNIVERSITY


Current features
----------------
* News And Events
* The admin can Add Students
* The admin can Add Lecturers
* Students can Add and Drop courses
* Lecturers submit students score (Attendance, Mid exam, Final exam, assignment)
* The system calculat students Total, Avarage, point, and grade automaticaly
* Also, the system tells the student whether he/she pass, fail or pass with a warning
* Assessment result
* Grade result
* Upload video and documentations for each course
* PDF generator for students registration slip and grade result
* Storing of quiz results under each user
* Question order randomisation
* Previous quiz scores can be viewed on category page
* Correct answers can be shown after each question or all at once at the end
* Logged in users can return to an incomplete quiz to finish it and non-logged in users can complete a quiz if their session persists
* The quiz can be limited to one attempt per user
* Questions can be given a category
* Success rate for each category can be monitored on a progress page
* Explanation for each question result can be given
* Pass marks can be set
* Multiple choice question type
* True/False question type
* Essay question type
* Custom message displayed for those that pass or fail a quiz
* Custom permission (view_sittings) added, allowing users with that permission to view quiz results from users
* A marking page which lists completed quizzes, can be filtered by quiz or user, and is used to mark essay questions

# Installation



- Create and activate a python virtual environment

- `pip install -r requirements.txt`

- Create `.env` file inside the root directory and setup your database (DB_NAME, DB_USER, DB_PASSWORD, DB_HOST, DB_PORT)

- `python manage.py makemigrations`

- `python manage.py migrate`

- `python manage.py runserver`

Last but not least, go to this address http://127.0.0.1:8000

### References
- Quiz part: https://github.com/tomwalker/django_quiz

#ANNE ATIENO: BBIT/14548/1/19
