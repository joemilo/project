Rafi Mirza Rubayed Hasan 1837613<br>
Joyaddar Md Jobayer 1731833<br>
Farid Bin Affendy 1924303<br>
Muhammad Faiq Bin Zainuddin 2011141<br>
Muhammad Khairul Muslim bin kamaruddin 2015803<br>


<h1>Project Title</h1> 
<h1>“ StudPort “ stands for Student Portal</h1>

<h2>Introduction</h2><br>
A StudPort is a portal exclusively for student. The student portal is a gateway to help students focus on mainly objective in study such as attendance, online courses, assignments and others which is useful for doing student activities. Online student portal is a web application which is useful for learners to choose right information. StudPort works like, initially the one who needs to get access only after his or her registration to the application. Before the student get to use the portal, they need to register first and the admin will check the correctness of information provided by the student. Only certified student that have been registered that can use the StudPort. 

<h2>Objective</h2><br>
The Studport provides the students with the details about the students’ achievements and the student can also have a chit chat with their lecturer. So, the objective for this StudPort is to: -
&#x2022;Make the students ease to have access for their online courses<br>
&#x2022;Students can make attendances and see their record of attendances<br>
&#x2022;Perform as a platform for students to reach out their lecturers<br>
&#x2022;Make the students to have access to their own profiles <br>

<h2>Features and functionalities of the proposed web application.</h2>

This existing systems involves the student filling a from which contain student’s personal details as well as the their own and studies information.After filling those forms,the student gets can login into the system and get to know what to do through it.

This web application system will have five pages.Below are the features and functionalities for each page.

1. Login Page : Students can login into their account that has been created by inserting their matric no and password.
2. Homepage : The student homepage dashboard will show the overview of the website.There were several features that will be included in this homepage section :

&#x2022;List of student subjects enrolment.<br>
&#x2022;Academic calender.<br>
&#x2022;Study week/Lecture week.<br>
&#x2022;Class timetable.<br>
&#x2022;Lecturer details.<br>
&#x2022;Important bulletin.<br>
3. Student Outline Page : This page will displaying personal information about the students.For example : Full name,Student ID,Email address and university address.<br>
4. Attendance Page : Students are able to record and check their own attendance according to the subjects they enrolled throughout the semester.<br>
5. Piece of work Page : Students are able to check the due dates of the task that has been assign to them by the lecturer and they submit their work within the same pages.<br>

<h2>View,Model,Controller and route</h2>

From Start the website, user need to register and login in login and register .php. The data will stored in database at student table.Not just that, the database will contain at least 5 table for the data from all pages. After that, user will proceed with login.php to login the website using matric number and password. The data will retrieved from database. Next, the view contain homepage, attendance page and assignment page and at least 1 additional page for profile page. All the view page will collect user data and retrieve data from database. The model will synchronize database data with form format. The view section will interact with model and will directly interact with database either when user change their data or key in their data. Additionally ,controllers will handle and fill the model with data that has been modified or updated. The website will contain at least 3 controller . Next, route will help to redirect from page to page or from .php to .php and  will map the URL to a particular action when the user start to use the application, For example, when the user click signup button, the page will redirect to register page.


<br>
    
<h2> ER Diagram</h2>

![WhatsApp Image 2022-05-31 at 2 14 00 PM](https://user-images.githubusercontent.com/37135726/171105986-8ed239da-62a7-4e79-aaba-82b219e93651.jpeg)

<br>
<h2>Sequence Diagram</h2>

![image](https://user-images.githubusercontent.com/37135726/171106923-5a25d22a-54bf-4953-9839-2b4589acb974.png)

     Sequence diagrams show how objects in the system interact with one another and it shows the sequence of the system. In our system there are seven objects that are represented in the rectangle boxes. The process begins when the user that is represented by the actor key in their login details that they have and it will pass to the database part to check whether the details is in the database or not. Moreover, it will then pass to the verification part to check whether the details are correct or not. The alternative happens when the details are correct, it will send the message to the user in the login page while if it is incorrect and it will pass the warning message in the login page to the users.

Furthermore, after successfully login the object will go through to the homepage and an alternative happens when they would like to logout rather than proceed to the next page and the object will pass through until the login page back. Next, if users would like to proceed from homepage to profile page, the object will continue to pass until profile page and will encounter alternatives when they would like to logout from the profile page, the object will be passed to the login page. Furthermore,objects will pass from profile page to attendance page if the user proceeds from profile page to attendance page and the object will be passed to login page if they log out from the page. Finally, the object will continue to be passed from attendance page to work page if they proceed to the page and will make the object being passed to login page if they logout. In addition, the object from the homepage can be passed directly to the profile page, attendance page and work page because the user can directly access it from the homepage. Next, activation boxes at each of the life lines shows that the longer the activation box, the more the object interacts in the system.

<br>
<h2>Mock-up</h2>

Login page<br>
![image](https://user-images.githubusercontent.com/37135726/171107178-2b9fe6ec-2ab4-442a-a81e-fc3ba4bb8971.png)

Homepage<br>
![image](https://user-images.githubusercontent.com/37135726/171107310-3e3eaf94-b0d0-4f80-a9a7-32e044928ea1.png)

Student profile page <br>
![image](https://user-images.githubusercontent.com/37135726/171107382-2ef7365c-d928-432c-ae40-1347e1fb421a.png)

Attendence page<br>
![image](https://user-images.githubusercontent.com/37135726/171107495-3569ce4e-1ffd-407c-9482-292c21011b66.png)

Task page<br>
![image](https://user-images.githubusercontent.com/37135726/171107568-c277d9e4-d67d-4b14-a231-9a2eee9ad015.png)







