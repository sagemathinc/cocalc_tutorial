---
layout: page
title: Getting started

next:
  url: /handson/lab02.html
  title: Adding people

prev:
    url: /handson/
    title: Introduction
---
In this first part of the tutorial we will create a basic template for your course material.

1. If you have not done so, create an account in [CoCalc](https://cocalc.com/) using your institutional email.
2. Log into your CoCalc account and create a new project named **SMC_hands_on** and make sure you add a meaningful description.
3. Once you have created your project the next thing to do is create a **.course** file (you can name it SMC_hands_on.course as well).

## Structuring your course
A commonly used structure for CoCalc courses is as follows:

  - notes

    - week1

  - data

    - data set 1

  - assignments

    - week1

    - week2

  - lab_sessions (if applicable)

(Note this is a suggested basic structure, which has been proved to be useful for some people. You can always add directories to satisfy your needs e.g. supplementary material, demo codes, etc.).

---

Now let's start populating your course with some content.

If you have Internet access in your CoCalc account (upgraded account) follow the next steps:

1. Create a terminal session (**>_Terminal**), you can give it whatever name you want.
2. We have created a GitHub repository for this session, which contains some directories and files to populate your project. In your terminal checkout the repo:

```bash
git clone https://github.com/trallard/SMC_HandsOn.git
```

Once you have done this your project should look something similar to this:

![after image](./assets/files.png)

If you don't have internet access you can clone the repository on your personal computer and then drag and drop the files into your CoCalc project.

Note that the drag and drop functionality has a size limit so you might need to create your project directories first. You can do this by using the **New** button or typing directly the terminal commands:

```bash
mkdir notes
mkdir notes/week1
```
Alternatively:

```bash
mkdir -p notes/week1
```
Note that the repository you have just copied only contains some Jupyter Notebooks and a .csv file containing some data. If you have a GitHub repo containing any sort of CoCalc supported files (LaTex, Juypter notebooks, Sage worksheets, etc.) you can add them directly by using `git clone repo_url` from the terminal.

---

## Exercise 1:
* Create/Import a LaTex document, which will be the "lecture material" for your course. Save it in the notes directory of your course (we are going to use this later in the session).

* Make a few changes to the document. Even if just changing some layouts bits and stuff.

---
