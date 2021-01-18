# Kahoot Clone

This is a clone of the famous online quiz web application "Kahoot!". This application however has only one of the functionalitites of kahoot, that is create a quiz and host it as a challenge by setting start date and time, end date and time and share it with students. This application makes use of chart.js library for generating and displaying charts and dialogFlow for chatbot. This is developed using MEAN stack.<br/>
There are two roles, namely student and teacher. The teacher can create a quiz and host it as a challenge by setting title, description, start date time, end date time. The students can log in to their account and play the quiz by entering the game PIN shared by the teacher. The student can see his score once the deadline has passed. The teacher can get a consolidated view of all student's performances with the help of charts.

## Development server

Before starting the application, first create a database in mongo named "quizzards"
<br/>
To start the Server :
<br/>

1. cd server<br/>
2. node index.js
   <br/>

To run the application on the browser: <br/>

3. Open a new terminal and run cd client/quizzards_client<br/>
4. ng serve <br/>
5. Navigate to `http://localhost:4200/`.

## Features

1. Used JWT for login
2. The user can play a quiz only once
3. On submitting a quiz, the user is redirected to the feedback page. Here the student cannot redirect back to the Quiz.
4. Chatbot is provided, so new users can easily navigate through the appication
5. Teachers can get an overview of student's performances with the help of charts.

Landing Page
![Landing Page](client/quizzards-client/src/assets/img/landing_page.png)

Registration Page :
![Registration Page](client/quizzards-client/src/assets/img/register.png)

Login Page :
![Login Page](client/quizzards-client/src/assets/img/login.png)

ChatBot
![Chatbot](client/quizzards-client/src/assets/img/chat_bot.png)

<br/>
Teachers Side:
<br/>

Dashboard Page
![Dashboard Page](client/quizzards-client/src/assets/img/teacher_dashboard.png)

Create Quiz
![Create Quiz](client/quizzards-client/src/assets/img/teacher_create_questions.png)

Challenge List
![Challenge List](client/quizzards-client/src/assets/img/teacher_challenges_list.png)

View Feedback recived by Students
![View Feedback](client/quizzards-client/src/assets/img/teacher_view_feedback_reports.png)

View students performances via Charts
![View Student Reports](client/quizzards-client/src/assets/img/teacher_view_student_reports.png)

<br/>
Student Side:
<br/>

Dashboard Page
![Dashboard Page](client/quizzards-client/src/assets/img/student_dashboard.png)

View report of challenge
![View Report](client/quizzards-client/src/assets/img/student_reports.png)

Join Game
![Game Pin](client/quizzards-client/src/assets/img/student_join_challenge.png)
