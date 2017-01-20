# Interacting with students and collaborators
There are multiple ways in which you can interact with your students or collaborators, in this section we will present some features that you might find useful when managing a course.

## Real-time chatrooms
You can create general real-time chatrooms for your SMC projects. You can create a project chat room by clicking on the **New** button, this will create a file with `.sage-chat` extension.

In addition, every file in SMC has a separate chat that can be found on the upper left corner of your screen.

![The chat button](./assets/chat_button.png)

Every time one of your students writes something into a chat on any one of their files, you will get a notification displayed on the top bar.

![The notification](./assets/instructor_notification.png)

Clicking on the notification button (bell icon on the top of the screen) displays a notification menu with the latest chats and modifications in the project or specific files.

![Notification Bar](./assets/notification_highlighted.png)

The chat notifications are always presented at the top of the menu, followed by any updates you or your collaborators have done to the project. Clicking on a chat notification will take you to **the student's copy** of the file inside **his/her project**.
From there, you can both reply to their questions and look at their work simultaneously.

![TA assistance example](./assets/student_question.png)

Once you have replied to the student's question (s)he will receive a notification.

## Live collaborative editing
Multiple users can collaborate on a project. As soon as a collaborator is added to a a project (see [Creating a Course](./creating_a_course/creating_course.md)) they share both the project and the associated files.

Live collaborative editing is possible in SMC. If one of your collaborators updates a notebook, the rest can see the changes as they are being made (similar to Google Docs).

## Creating a shared project
You can create a common shared project from any of your existing projects. You can think of a shared project to be your private course website for the students with automatic forum and code support. By default everybody (collaborators and students) will have **write** access to the project and its associated files.

To create a shared project you need to go to your **.course** file and click on the **Shared 'Project** button.

![Create shared](./assets/shared1.png)

If you create a **.sage-chat** file here, all students will receive automatic notifications when questions are posted on the chat.

If you want to make a file or an assignment **read only** so that students cannot modify it you need to modify the file permissions. Launch a terminal and type `chmod a-w filename` (in this example the filename is `Assignment1`).

![Read only files](./assets/read_only.png)

If you want to check the access permissions of all the files contained in a given directory use the command `ls -l` on the terminal.

![Access check](./assets/ls_assignment.png)

In the case you want to change a read only file into a read and write type `chmod a+w filename` on the terminal.

## Group Projects
There are various ways in which you can facilitate  students group projects in SMC. A couple of options are:

### One project per team
Have someone on each group make a project with all the group members as collaborators.
They will all then be able to collaborate on the same project and modify files simultaneously.

You should note, however, that by using the approach you cannot automatically collect assignments from the team. However, a workaround could be creating an assignment in your main project and have the students copy the file over to their group project.

### Using Git
Students can collaborate in their own course-affiliation using git via the terminal in SMC (for more tips on using git see the Interesting features and tricks section).
