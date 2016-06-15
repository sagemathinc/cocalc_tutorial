# Tips and Tricks
Here are some things to know that can make your life easier.

## Chat and helping students
Every file in SMC has chat available on the upper right side of the screen.

![The chat button](./assets/chat_button.png)

Every time one of your students writes something into a chat on any one of their files, you get a little notification.

![The notification](./assets/instructor_notification.png)

Which brings up this menu when you click on it.
![Notification Bar](./assets/notification_highlighted.png)

Clicking on this chat notification (chats are always at the top) will bring you to **their copy** of the assignment  inside **their project**.
From there, you can directly reply to their question and look at their work simultaneously.

![TA assistance example](./assets/student_question.png)

Once you reply, they will see their own notification like the one you saw.
## Using the shared project
You can think of the shared project to be like your private course website for the students with automatic forum and code support.
If you create a .sage-chat file here, all students will get notifications when someone asks something here.

![example image]

If you want to upload the assignment here, you can make it read only so that students can't change it.

![read only example]

Every time you update the assignment, you can give the students a notification by typing something into the chat in that copy of the assignment

![updated assignment example]

Students can also ask questions and share code snippets here since by default everyone has write privileges to the project.

## Group Projects
There are a few ways to facilitate group projects on SMC.

### One project per team
Have someone on each group make a project with all the group members as collaborators.
They can then all edit the same document(s) together in real time much like Google Docs.
This method has the downside that you cannot automatically collect anything from their project.

However, you can definitely make an assignment and just make them copy the files over from their group project.


### Using Git
Since it supports the terminal, students can also collaborate using git right in their own course-affiliated project.

## Text fields generally support markdown and LaTeX
For example in chat:

![before image](./assets/before_latex_render.png)

**Renders as**
![after image](./assets/after_latex_render.png)

Specifically, it supports [GitHub Flavored Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Making multiple assignment folders quickly
For extremely fast folder creation, you can make a shell script in the language of your choice since SMC gives you terminal access.

However, you can also do this in another way that is still faster than going to ![New Button](./assets/new.png) every time.

In the files menu of your project, you can enter text like `assignments/assignment1/directions.md` then hit **enter** or **ctrl+enter** to create `directions.md` inside the folder `assignment1` which will be inside `assignments`. Hitting **enter** will open up the new file while **ctrl+enter** will silently create the necessary files and folders in the path.

![search bar file creation](./assets/file.png)

You can also create folders here just by ending with a `/`

![search bar folder creation](./assets/folder.png)

## Starting up everyone's project before class
By default, projects have a idle time of 24 hours before they spin down and need to be started again.
Inside your course manager, you can start everyone's project so that they are all "hot loaded".<br/>
This can be useful to do before class or presentations.

First, make sure you are in your course settings and not your project settings.
![course settings](./assets/settings.png)

Then scroll down to find and click on the `Start all...` button

![after click](./assets/start_all_clicked.png)