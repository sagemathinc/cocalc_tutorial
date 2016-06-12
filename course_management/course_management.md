# Course management

No matter what you've added in the instructors view of the course, the students will not see any files until you explictly assign them.

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