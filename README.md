Employee Tracker
================

by <a href="http://duanemoody.io" target="_blank">Duane M. Moody</a>.

Employee Tracker is an app that will help track what employees of a company are working on.


Epicodus Coursework Objectives
------------------------------

* Let users add and list employees.
* Let users create divisions in the company and add employees to a division. In this company, an employee only belongs to one division (there is a one-to-many relationship between employees and divisions). Let users list out divisions, and then choose a division to see what employees are in it.

Installation
------------

Install Employee Tracker by first cloning the repository.  
```
$ git clone http://github.com/dmmoody/employee_tracker.git
```

Install all of the required gems:
```
$ bundle install
```

Database Setup
--------------

Run the following in the command line:
```
$ rake db:create
$ rake db:migrate
$ rake db:test:prepare
```

Running the app
---------------

To run the app, ```\cd``` into the root folder for the app and start the webserver:
```
$ ruby app.rb
```

In your web browser, go to http://localhost:4567

Contribute
----------

- Issue Tracker: https://github.com/dmmoody/employee_tracker/issues
- Source Code: https://github.com/dmmoody/employee_tracker

Support
-------

If you are having issues, please let me know at: dmmoody@gmail.com

Bug reports
===========

If you discover any bugs, feel free to create an issue on GitHub. Please add as much information as possible to help me fixing the possible bug. I also encourage you to help even more by forking and sending me a pull request.

https://github.com/dmmoody/employee_tracker/issues

License
=======

MIT License. Copyright 2014 Duane M. Moody | <a href="http://moodyco.de">MoodyCode</a>