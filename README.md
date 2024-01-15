<h1 align="center">Senior Capstone Project</h1>

<h2>PlannedIt.io Planning Application</h2>
This is a display of the application that was created by me and my group for IST440W as our senior capstone project.

<h2>Environments and Technologies Used</h2>

- Flutterflow.io (Front-end)
- Firebase (Back-end)

<h2>PlannedIt.io</h2>

<p>
The goal of this project and application was to create a simple to use planning application that was not focused on planning for an enterpise environment. Instead, focusing on helping users plan out their own personal daily life, but with the catch of being able to create groups and share certain tasks with these groups. This way, not only can they plan out their own daily tasks, but also share this information with other users of their choice, such as family or friends. Allowing user to not only plan out their lives, but more clearly communicate their schedules with those they deem are necessary. Ideally, users would be able to improve their schedule planning and communication of that schedule with others.
</p>

![image](https://github.com/noles498/capstone_project/assets/143885547/d0207fda-6178-4c25-9382-c660a5664997)

<p>
The application starts with a basic Sign In or Sign Up screen.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/17ff91ef-0ff8-4381-90f6-da7e0b9459aa)


<p>
Once logged in, the user starts on the Tasks page. This is where all the planned tasks they want to keep track of are displayed. Now due to our groups inexperience developing applications and with Flutterflow, some weird design decisions were made to make sure the project was functioning as desired and completed by our class deadline. Therefore, for tasks to appear properly the user must first create themselves a group.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/c3221b46-30ff-4321-996a-7581d93f714e)

<p>
This is the groups page. The user can navigate here by clicking [Groups] on the navigation panel on the right side of the application. Here they can view all the groups they are apart of and even create new groups.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/68cb92db-0464-4146-a6dc-173b20319099)

<p>
If they opt to create a new group it would take them to this page where they can type the desired group name, and a description of the group.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/f9e1381a-eda7-4b21-9329-b34ce89a0e26)

<p>
Once the group was created they could then, from the [Groups] page, click on the Group Details button under each group to see the various details. Here they could see all the users who were apart of the group, add/remove members, or leave the group. There is also the Add to your Groups button. This was one of the weird design decisions made to make sure the application function as desired when displaying tasks on the Tasks page. The idea was for the Tasks page to display all the tasks assigned to the groups the user was assigned to. However, this became one of the biggest hurdles we had to deal with during development. The best workaround we could find was the use of this button. This button allowed for the user to officially assign themselves to the group, and have it properly assigned to them in the database. This way when the database was queried on the Tasks page for what groups they were assigned to, this would all function properly. When a user creates a new group, it successfully acclomplishes assigning that user to the group. However, when that user adds another user to the group, it would not assign that user properly. That is where this button came in, as a way for the added user to then officially assign themselves to the group. Once the button was clicked and the user was officially assigned, this button no longer appears for them.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/d5fb4a8b-cd1f-4a36-b071-cfa21eb54ee9)

<p>
Now with the groups created the user can navigate back to the Tasks page and click create a task. This is the create a task screen, where they can give the task a name, description, and assign the day and times for the task.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/2ec0d1e9-54b3-4343-8844-f7074bfa485b)

<p>
Once they fill out the task information and click Create Task, it moves to the Select Group screen. Here they can select which group they want this task to be assigned to. Anyone apart of the group select will see this task and it will appear on their Tasks page. Note: there was a weird glitch we could not find a fix for before the deadline, where sometimes when a user first logs in, the first task they attempt to create would not create properly. When they would click Create Task, it would not move to the Select Group screen.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/57bf8a07-2204-48ed-adf3-2c99f0478aa3)

<p>
The user can also click on the tasks to view its details. Here they can see all the information for the task along with what group its assigned to.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/32301dff-4eb6-42ad-bc42-0eb6fea2b5fe)

<p>
By clicking their [Display Name] at the bottom of the navigation bar the user can see their profile. Here they can change password, edit their profile information, sign out, or even switch the application between light or dark mode.
</p>
<br />

![image](https://github.com/noles498/capstone_project/assets/143885547/a50b7c8d-cbfe-4113-bea6-ce0e9ae99d34)

<p>
Our database was stored in Google's Firebase. This Cloud Firestore is where all of our user, group, and task information is stored.
</p>
<br />

<p>
While the application is far from perfect, with the timetable we had and inexperience of the group going into it, we were very satisfied with the results of the project. Neither myself, nor my other group member felt strong enough in programming to create a project in that manner. We found the Flutterflow tool and decided that would be the best way for us to create our project. It allowed us to create this project with out writing any lines of code for the front-end or the back-end, and it seemlessly integrated with Firebase with just a few simple steps. Not only were we having to learn how to develop this application, but also how to use the Flutterflow application and its features. This led to many of the frustrations and hardships we had throughout the projects development.
</p>









