![qlp_4.png](https://egator.greenriver.edu/courses/2433432/files/235842483/preview)
**Overview**

This is a multi-stage project in modern and practical application development on the web. As developers you will build a website using both front-end and back-end code and then deploy your application on a popular cloud platform.

**Objectives**

Here is what we'd like you take out of this assignment.

Course objectives

- Use a framework to build a software as a service (SaaS) application that is developed or deployed in the cloud.

Assignment objectives

- Create a new Spring Boot project.
- Use version control tools to track progress in a project.

**Project Outline**

This document describes a series of assignments that are meant to be a quarter long project. The end-goal is to deploy a website, using modern techniques, to a cloud platform. This will take many smaller steps and some learning along the way. On this journey we will do the following:

- Learn about a modern server-side framework (Spring).
- Learn how to write remote web apis.
- Learn (more) about client-side coding (Javascript).
- Learn about deployments on a popular cloud platform (AWS, Azure, or GCP).

Here is an outline of the milestones we will complete this quarter:

![qlp_1.png](https://egator.greenriver.edu/courses/2433432/files/237375681/preview)

**Getting Started**

We will be using Spring Boot for our work. To begin you should create a new project using Spring Initialzr. Make sure to set the following properties:

- Use Maven or Gradle as a build/dependency manager
- Pick appropriate artifact and package names
- Use Java version 17 (or newer)
- Package the application as a JAR
- Have the following dependencies:
  - Spring Web - this gives you access to web controllers for HTTP traffic
  - Spring Boot Dev Tools - this configures a development environment for debugging your code
  - Lombok - this is a quality-of-life tool for creating POJO Java classes

Once you have access to your project files you should add the following files & folders:

![qlp_3.png](https://egator.greenriver.edu/courses/2433432/files/235842378/preview)

**Working With Github Classroom**

We will be using Github Classroom for all assignment submissions this quarter. This provides a new remote that you can push your code to. The remote is easy to see and review by your instructor. You should first complete the following steps:

- Click on the following assignment link: [https://classroom.github.com/a/6uO-0btN](https://classroom.github.com/a/6uO-0btN)
- Accept the organization and assignment and go the new remote repository that Github Classroom creates for you.

**Using the Github Issue Tracker**

It is expected that each of the steps, within each milestone, are recorded using an issue-tracker tool. Github provides this feature in the Issues tab under a repository. For each milestone completed this quarter, you should create a list of tasks and mark each as "done" once they are completed. For example, in this first milestone you might create the following tasks, each of which are described in this document.

1. Commit initial project files
2. Update project description file (README.md)
3. Add a default home page for the website

After adding the tasks, your issue tracker should look similar to the following screenshot. **Note:** Your issues may be slightly different than what is seen here. You will be responsible for identifying and recording tasks for all future steps in the project.

![qlp_9.png](https://egator.greenriver.edu/courses/2433432/files/235842466/preview)

When working on a new task you should do the following:

- Assign the task to yourself in the issue tracker using the **assignees** drop-down on the right.
- Once completed, you should commit your work and close the issue. 
  - You can close the issue manually by:
    - opening the issue on Github
    - clicking the "Close Issue" button
  - You can close an issue at the same time you commit your work. To do this you will need to end the commit message with "Closes #x" where x is the issue number.
    - For example, "Finished creating project. Closes #1", would enter a commit message of "Finished creating project." and would close issue #1 in the issue tracker.

**Using Version Control**

![qlp_12.png](https://egator.greenriver.edu/courses/2433432/files/235842447/preview)

To put your code under version control, complete the following steps:

- Initialize your project directory as a local Git repository.
- Update the .gitignore file to ignore files that you don't want to commit to Git.
- Add all primary files from your project to Git
  - Files under the src directory.
  - The **pom.xml** and **README.md** files.
- Commit your changes
- Add the Github Classroom URL as a remote.
  - **Note:** This is the not the same as the link listed above! Each student will have a unique URL that includes the assignment name and their Github account name.
- Push your changes up to Github Classroom.

How you interact with git and Github is up to you. These steps can be completed in two ways:

- Using the command-line
  - Using the skills learned in your web classes, you can type in commands manually. You should already understand how to do this.
- Using a GUI tool
  - This can be done through built-in IntelliJ tools.
  - You can learn about how to do this here - [https://www.youtube.com/watch?v=uUzRMOCBorg](https://www.youtube.com/watch?v=uUzRMOCBorg)

Once this step is completed your project files should be visible on Github. From this step forward you should be regularly committing changes through Git and Github.

**Choosing a Website Theme**

![hobbies.jpg](https://egator.greenriver.edu/courses/2433432/files/235842479/preview)

In this first milestone you will need to decide on a topic for your website. The topic should be something you are passionate about. Here are some ideas:

- Pick a hobby: reading, cooking, gardening, gaming, comics, ...
- Pick a general subject: technology, history, education, mathematics, ...
- Pick a data-related topic: corgis datasets, data.gov, kaggle.com, ...

Once you have settled on a topic, update the README.md markdown file in your repository with a description of your project. You should include the following information:

- A project title
- A project logo/image
- Information about the project (developer, class, quarter, ...)
- A list of the milestones in the project
- A paragraph description of the project. This should include why you picked your topic and what you hope to learn along the way.

When complete your README.md file should look something like the following:

![qlp_10.png](https://egator.greenriver.edu/courses/2433432/files/235842451/preview)

**Adding a Home Page**

This step will be brief. To verify that your Spring Boot project is working, add an HTML and CSS file to the static folder in your project. The content in this page should be simple. You should verify that your page (and styles) are loading in the browser over the localhost server provided by IntelliJ. For example, you should see the following in your browser of choice:

![qlp_11.png](https://egator.greenriver.edu/courses/2433432/files/235842468/preview)

**Note:** I'm not expecting you to spend much time designing your page & styles. Keep things simple as the page will change in our upcoming milestones!

**How to Submit Your Work**

You can submit the URL to your Github repository when you have completed this first milestone.

- Since your repository is private, you will need to add your instructor as a collaborator on the project. Your instructor can be found at - [https://github.com/joshbarcher](https://github.com/joshbarcher)
- Make sure to commit your work as you go. A best practice is to "commit early and often!"
- Make sure to close your issues as you complete the work, through the issue-tracker on Github.
