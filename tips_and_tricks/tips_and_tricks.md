---
layout: page
step: 5
prev:
  url: /interactions/interactions.html
  title: Interacting with others

---
# Other useful features and tricks
In this section we will present some SMC features and useful tricks that will make the management of your project easier.

## Text fields generally support markdown and LaTeX
SMC not only facilitates the creation of LaTex documents, but the multiple text sections in SMC support and render LaTex and markdown  (specifically  [GitHub Flavored Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)).

For example, you can use LaTex syntax in the chat rooms:

![before image](./assets/before_latex_render.png)

which renders as

![after image](./assets/after_latex_render.png)

## Making multiple assignment folders quickly
So far we have shown how to create folders and files by using the **New** button every time. ->![New Button](./assets/new.png)

However, such a method could be quite time consuming when you need to create multiple folders, subfolders, and documents. If you are a terminal fan you could create a shell script in your preferred programming language and run it from the terminal.


Alternatively, in the files menu of your project, you can enter paths such as `assignments/assignment1/directions.md` then hit **enter** or **ctrl+enter** to create `directions.md` inside the folder `assignment1` within `assignments`. Hitting **enter** will open up the new file while **ctrl+enter** will silently create the necessary files and folders in the path.

![search bar file creation](./assets/file.png)

You can also create folders here just by ending with a `/`

![search bar folder creation](./assets/folder.png)

## Starting up everyone's project before class
By default, projects have an idle time of 24 hours before they spin down and need to be restarted. However, it may be handy to start everyone's project before a class or presentation so that they are all "hot loaded".

You can easily do this from your course manager:
first, make sure you are in your course settings and not your project settings.

![course settings](./assets/settings.png)

Then scroll down to find and click on the `Start all...` button

![after click](./assets/start_all_clicked.png)


## Restarting a project
Every time you open a Jupyter notebook or a Sage Worksheet, its state is stored in memory. This can become quite costly if you open multiple files one after the other (e.g. when you are marking your students' work).

To solve this you can stop every instance using the  stop button (for both Jupyter notebooks and Sage worksheets) once you are done with your marking.

![Stop notebook](./assets/stop_notebook.png)

Alternatively, you can restart the entire project, which will clean everything. You just need to go to your project settings and click on **Restart project**.

![Restart project](./assets/restart_project.png)

### Using Git
As SMC supports the usage of terminal people can collaborate using Git within a course-affiliated project.

If you already have a project or some files allocated in GitHub you can add them to your project.
Click on the **New** button and add/paste the link to your repository in the appropriate text box. Click on the **Download from Internet** button.

![Download from Internet](./assets/download.png)

(*Obvious note*: You need to have internet access enabled in your project.)

Also you can use the terminal to commit and push changes to your repository in GitHub.

## Time Travel Diffs
The editor based documents (e.g. python code, sage worksheets, LaTex documents, etc.) as well as the Jupyter notebooks and Sage worksheets are Time Travel Diffs supported. The Time Travel Diffs feature allows you to see what happened with a file within a certain time interval.

Open up **Time travel** from any document:

![Time travel](./assets/time_travel.png)

then click on changes and drag the sliders to see the document in a given time interval.

![TT sliders](./assets/time_travel_sliders.png)

If you need to revert the document to a previous state, just drag the sliders to the desired interval and click on **Revert live version to this**, this will revert the document to that specific version and discard any modifications made afterwards.
