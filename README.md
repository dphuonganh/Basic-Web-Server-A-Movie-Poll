   # Basic Web Server: A Movie Poll

### Intro:  :smile:

Intekers, you have been through a very long journey with Python as a developer until now!

Let it be fun games, the notorious shell or head breaking algorithms. You’re also get familiar with Object Oriented Programing through the Graph.

For now, you will be guild into a whole new world of Web development with Python through this project: the glorious “The Intek Movie Friday Night Poll with Basic Web Server” project.

As the name suggested, in this project you’ll be asked to install and config a simple Django webserver and build a simple polling application with Django framework.

As this is your very first python web project. The subject will include very detail instructions with step by step approach to guild you.

But please remember that the subject gives you a lot of materials doesn’t mean you just need to copy and paste. You have to understand clearly your setups, configs, or coding as these will be asked during the Staff review.

And finally, this project is very practical as we can use it to vote for what movie will be screen every Friday. We will have a beauty contest to choose the best functional and visual beauty to deploy for our use.

### Requirement:  :smile:

This project consisted of two parts.

**Part 1:**

In part 1, you have to install the Django framework into your local machine and do some setting & config with it.

Step 1: check python installed version and \*install vitualenv\* with \*pip\*, enable the \*vitualenv\*.

 * Install \*vitualenv\* is a good practice to create an isolated sandbox environment for your web development, but it is optional, you can still install Django into global scope if you want.
Step 2: install Django, creating a project name with name “pythonweb”, creating an app with name “moviepoll”.

 * In this step you must get familiar with the project and app skeleton structure, mean you have to know the folder and files structure Django created after you use the command and the functions of each file.
Step 3: Edit the \*setting.py\* to change timezone to Viet Nam, add “moviepoll” to installed apps, run initial migration, run server, edit \*url.py\* to include the route of “moviepoll” app.

 * You must understand the timezone format used in setting, know about the default apps and how to added new apps, what is route and how to add new one, what is the initial migration and why you have to run it. And finally, of course you have to know how to run the server and check everything are working fine.

**Part 2:**

In part 2, you have to build a simple web application called the ““The Intek Movie Friday Night Poll” using Django framework.

Features of the app:

Name: Intek Movie Friday Poll app

Pages:

 * Index page: show a list of poll questions (ie: “What to see on Friday 2019/01/11”), each question has a link to the poll detail.
 * Detail page: show the questions, a list of radio button with movie name for that poll question and a submit button. People have to choose an option before submit.
 * Result page: the page to display result after the user submit a poll.
Data:
 * Data will be saved with \SqlLite\ (default data engine of Django) and using the Build in ORM and admin page of Django.
 * Data model:

![basic.png](https://github.com/dphuonganh/Basic-Web-Server-A-Movie-Poll/blob/master/basic.png)

**Step by step guild of part 2:**

Because this is the first web project, a step by step guild will be provided to you. Hint:
 * There is an official Django tutorial for each step of making this poll app, it’s one of the reasons the poll app is chosen as your first Django web app project.
 * When you follow the tutorial, remember to read carefully and understand what you’re doing.
 
Step 1: Create project & poll app:
 * Should be done in part 1, re do with correct name if needed.
 
Step 2: Database setup, creating models, activating models, creating and running migrations, try interacting with the data through shell.
 * This part is one of the most difficult one, have to read a lot, try a lot to understand and do-able.

Step 3: Config and using the build-in admin site to add and manipulate data.
 * If done step 2, this step will be not so hard.

Step 4: Creating the views, using the template:
 * This step requires a lot reading to understand what a view & template are and the basic of request & response in Django, learn to write basic view using template, write python code to read the data models, using Render, return 404 and other errors, using URL template and path.

Step 5: Writing and processing form:
 * Must learn basic about HTML form and POST method of HTTP. Write a form template. Use python to catch and process the form data.

Step 6: Customize look and feels:
 * Learn how to serve static file in Django, add simple background image and css file to the project.
 
***Link Trello:*** [My Trello](https://trello.com/b/lOzhEdXh/basic-web-server-a-movie-poll)

