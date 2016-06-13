# Course management

No matter what you've added in the instructors view of the course, the students will not see any files until you explicitly assign them.

## Creating a new assignment

An assignment consists of a folder that contains one or more files to be distributed to your students.

Start off by creating a folder called **assignments** in the root directory of your course project. 
Within this folder create a subfolder called, say, **Assignment1** and populate it with a Jupyter Notebook that contains the question(s) that you want your students to answer.

Open the **.course** file and click on the **Assignments** tab

![The assignment tab](./assets/assignment_course.png)

Enter **assignment1** in the search box on the right hand of the screen.

![Assignment search box](./assets/find_assignment.png)

The system will look for any folders with **assignment1** in their path name and  return a set if options. 
Highlight the one you want and click on **Add Selected Assignment**.

![Find assignment](./assets/find_assignment2.png)

The new assignment will be added to the top of the list of assignments available for this course.

![Find assignment](./assets/assignment_list.png)

## Assigning an assignment to students

Click on the assignment in the assignment list. 
When the assignment opens, set the **Due** date and click on the **Assign** button to assign to all students in the course.

Alternatively, you can assign just to individual students.

![Find assignment](./assets/send_assignment.png)

When an assignment is made to a student, a **copy** of the assignment folder will appear in their course project.

Advise the students that all work on the assignment should take place in this folder. Any work performed outside of this folder will not be collected.

## Collecting assignments from students

## Grading

## Returning an assignment to students

## Course folder structure

I tend to place course content in one of two categories:

* Content that you only push out to students (e.g. lecture notes, data)
* Content that requires pushing out and pulling back (e.g. assignments and homeworks)

The reason for splitting content in this way is to save on disk space. 

When you push content out to the students, a copy is placed in their individual projects. When you pull it back for marking, a fresh copy of each student's assignment is made in **your** project. If the assignment contains large files, the lecturer's project can quickly run out of space for large classes.

Each project has 3Gb of disk space provided for free with more being provided by purchasing upgrades.

There are many ways one could organise a course in SageMathCloud but the following schema has proven to be useful for many people.


* notes/date1
* notes/date2
* ...
* assignments/date1
* assignments/date2
* ...
* data/xyz
* data/abc

This way, the students just see the following three folders in their course project.

* notes/
* assignments/
* data/

The **notes** and **data** folders contain content that you push to the students and **assignments** contains material that you also collect back from them.