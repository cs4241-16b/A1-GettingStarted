Assignment 1 - Hello World: Basic Deployment w/ Git, GitHub, Heroku  
===

Due Sep todo

This assignment is a "warm-up" exercise. 
You will simply deploy the starting Web site that you will use this term to the [Heroku Web platform](http://www.heroku.com/). 
Thanks to past instructors of the course, here is a short [getting started with Heroku movie](http://web.cs.wpi.edu/~gpollice/Movies/HerokuGettingStarted/) that should help you. 
You can also refer to the [Getting started with node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction).

*Tip*: When creating the website from scratch, Follow these instructions on how to create a heroku app from the command line interface. Further, if the shortcut code doesn't work, as it didn't for me, do it the long way. Also, keep in mind that Heroku create can take another argument that is a name, it will make everyone's life easier. So Heroku create ta-assignment1 for example.

Assignment details
---

Do the following to complete this assignment:

1. Fork the [starting project code](http://github.com/cs4241-16b/gettingstarted). This file contains:
    * the server code, server.js
    * the Procfile that you need for Heroku deployment
    * A starting index.html file that you will edit as described below
2. Edit the index file to show the following information about you:
    * your name and class at WPI (e.g. class of 2013) Note: Do not put any contact or personal information that you do not potentially want other people outside of this class to see.
    * your major(s) and minor(s)
    * previous computer science courses that you have taken at WPI
    * your experience with the following technologies and methods (none, some, a lot)
        * HTML
        * CSS
        * Java
        * JavaScript
        * Ruby
        * Python
        * unit testing
3. Test your project to make sure that when someone goes to your main page, it displays correctly.
4. Deploy your project to Heroku.
5. Submit a Pull Request (see "GitHub Details" below) with your updated code and readme. At the top of the readme, you must have a URL where graders can view your Web site. Make sure that you have your name as comments in all files that you create or modify. This includes HTML documents, CSS files, and JavaScript.

Notes
---

Notes:

When you create your Heroku application, give it a unique name. For example, if your name is Chris K. Smith, name it csk-cs4241-main, or something like that. This is the Web site that you will evolve into your working Web site for homework assignments and other things. You will continually be updating it.

When you test out your work, you may find out that you do not see the index.html file you've edited in the Firefox browser on your virtual machine. This is because the original page that I had at localhost:5000 is in the cache. To fix this you need to clear the cache. You do this by going to Tools>Clear History in the Firefox menu. Then clear everything so you start from scratch.

Resources
---

If you need a JavaScript/HTML/CSS refresher, see [Technology Fundamentals by Scott Murray](http://chimera.labs.oreilly.com/books/1230000000345/ch03.html#_html) and/or [JavaScript Codeacademy](https://www.codecademy.com/en/tracks/javascript).

If you need a Git/GitHub refreseher, see [GitHub Bootcamp](https://help.github.com/categories/bootcamp/), the [GitHub Guides](https://guides.github.com/) (especially the ones on Hello World, and Understanding the GitHub Flow, and Forking Projects), and [CodeSchool's Try Git Course](https://www.codeschool.com/courses/try-git).

GitHub Details
---

- Fork the [GitHub Repository for the assignment](http://github.com/cs4241-16b/gettingstarted). You now have a copy associated with your username.
- Make changes to index.html to fulfill the project requirements. 
- Make sure your "master" branch matches your "heroku" branch. If you don't know what this means, read about Heroku and GitHub branches until you master it.
- Edit the readme.md with a link to your heroku site.
- To submit, make a [Pull Request](https://help.github.com/articles/using-pull-requests/) on the original repository.
  - Be sure to format your readme appropriately so we can find your Heroku-hosted application.
