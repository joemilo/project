Rafi Mirza Rubayed Hasan 1837613
Joyaddar Md Jobayer 1731833
Farid Bin Affendy 1924303
Muhammad Faiq Bin Zainuddin 2011141
Muhammad Khairul Muslim bin kamaruddin 2015803


Project Title 
“ StudPort “ stands for Student Portal

Introduction
A StudPort is a portal exclusively for student. The student portal is a gateway to help students focus on mainly objective in study such as attendance, online courses, assignments and others which is useful for doing student activities. Online student portal is a web application which is useful for learners to choose right information. StudPort works like, initially the one who needs to get access only after his or her registration to the application. Before the student get to use the portal, they need to register first and the admin will check the correctness of information provided by the student. Only certified student that have been registered that can use the StudPort. 

Objective
The Studport provides the students with the details about the students’ achievements and the student can also have a chit chat with their lecturer. So, the objective for this StudPort is to: -
-	Make the students ease to have access for their online courses
-	Students can make attendances and see their record of attendances
-	Perform as a platform for students to reach out their lecturers
-	Make the students to have access to their own profiles 

Features and functionalities of the proposed web application.

This existing systems involves the student filling a from which contain student’s personal details as well as the their own and studies information.After filling those forms,the student gets can login into the system and get to know what to do through it.

This web application system will have five pages.Below are the features and functionalities for each page.

1. Login Page : Students can login into their account that has been created by inserting their matric no and password.
2. Homepage : The student homepage dashboard will show the overview of the website.There were several features that will be included in this homepage section :

	List of student subjects enrolment.
	Academic calender.
	Study week/Lecture week.
	Class timetable.
	Lecturer details.
	Important bulletin.
3. Student Outline Page : This page will displaying personal information about the students.For example : Full name,Student ID,Email address and university address.
4. Attendance Page : Students are able to record and check their own attendance according to the subjects they enrolled throughout the semester.
5. Piece of work Page : Students are able to check the due dates of the task that has been assign to them by the lecturer and they submit their work within the same pages.

<h1>View,Model,Controller and route</h1?

From Start the website, user need to register and login in login and register .php. The data will stored in database at student table.Not just that, the database will contain at least 5 table for the data from all pages. After that, user will proceed with login.php to login the website using matric number and password. The data will retrieved from database. Next, the view contain homepage, attendance page and assignment page and at least 1 additional page for profile page. All the view page will collect user data and retrieve data from database. The model will synchronize database data with form format. The view section will interact with model and will directly interact with database either when user change their data or key in their data. Additionally ,controllers will handle and fill the model with data that has been modified or updated. The website will contain at least 3 controller . Next, route will help to redirect from page to page or from .php to .php and  will map the URL to a particular action when the user start to use the application, For example, when the user click signup button, the page will redirect to register page.




