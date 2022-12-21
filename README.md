# CS50 - Final Project - ONLINE NOTES

## *Our team*
- [Pavlo Zinchenko](https://github.com/PaulSNDX)
- [Daria Katsai](https://github.com/DarunkaKa)

## *Description*
First of all, you have to register. Provide a unique username and a password.
After that, you can use your online notebook and a calendar.
To save new notes, you should write any content and press the save button.
All notes can be edited, downloaded, sorted by different algorithms or deleted.
Also, you may use the calendar tracking day function to check how many days are left.

An error message will appear when you provide incorrect input for registration, login or calendar. Follow the instructions in these messages and try again.

Examples of error messages and actions:
Must provide username - username field is empty;
Must provide password - password field is empty;
This name is already taken by another user - input another name because this one exists in the database;
Password length should be more than 7 symbols and less than 25 - incorrect password length;
Passwords don't match - confirmation password do not the same;
Incorrect credentials - maybe the user is not existing or the username/password is wrong;
There is no data. Nothing to save - you have to input data before press save.

### *Available sortes*
* By alphabet order
* By reversed alphabet order
* By creation time

## *Calendar functional*
To add a new date - provide the event name, month, and day and press add
It will count how many days are left.
For instance, if today is 01.11.2023 and the target date (is 10.11.2023) - 9 days are left.

If it is today - you will see the following message: It`s today!
After that, you ought to delete an event. Otherwise, it will start counting again from 364 / 365 days left.

## *Development tools*
* The interpreted object-oriented programming language [Python](https://www.python.org/) was chosen for software development.
* The language of tags - [HTML](https://css.in.ua/html/tags) and the language of page style - [CSS](https://www.w3schools.com/css/) were also chosen. These are the main web scripting languages for creating web pages and web applications.
* [Flask](https://flask.palletsprojects.com/en/2.2.x/) was chosen to build the software, which is a small and lightweight web framework written in Python.
* Also chosen was the [Jinja](https://jinja.palletsprojects.com/en/3.1.x/) templating engine, a fast, expressive, extensible templating engine.
* [SQLite](https://www.sqlite.org/index.html) was chosen as the DBMS.

## *YouTube demonstration video*
https://youtu.be/_ND1KgHJcxE

## *Documentation*
+ https://www.python.org/
+ https://css.in.ua/html/tags
+ https://www.w3schools.com/css/
+ https://flask.palletsprojects.com/en/2.2.x/
+ https://jinja.palletsprojects.com/en/3.1.x/
+ https://www.sqlite.org/index.html

## About CS50x
>https://cs50.harvard.edu/x/2022/

An entry-level course taught by David J. Malan.

CS50x teaches students how to think algorithmically and solve problems efficiently. Topics include abstraction, algorithms, data structures, encapsulation, resource management, security, software engineering, and web development. Languages include C, Python, SQL, and JavaScript plus CSS and HTML.
