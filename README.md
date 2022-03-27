## Overview
The purpose here is to collaborate on a simple, real-world project, and use all the techniques and tooling we use in our engineering jobs, including:
* git version control
* Github issues, for tracking progress and completion of issues
* Python, and eventually React / HTML / CSS
* SQL database
  * table creation / updates using migrations
  * CRUD operations (Create, Read, Update, Destroy)
* REST JSON API
* User authentication / authorization

We will not be writing code for this project on company time! Lunchtime, or a brief coffee break is acceptable during the day, to review a pull request, but we're not writing code for this project on company time.

## Suggested Background
There are many issues you'll have to understand in whole or in part, in order to successfully create a project like this on your own. It is highly recommended that you have the ability to write simple Python code on your own, and have a good grasp of
  * regular expressions
  * iterating over lists and dictionaries
  * datatypes, and their manipulation
    * strings, integers, floats, dictionaries, lists, tuples, etc.
  * classes and modules
  * basic querying
    * `SELECT * FROM user`
    * `INSERT INTO USER (email) VALUES ('you@example.org')`
A few key ideas to keep in mind:

This material requires 1) a good understanding of programming, and 2) significant time investment, and probably some significant struggle. Every experienced engineer on this team has spend hundreds or thousands of hours learning this material, and few among us have grasped all of it. How many engineers have struggled through material, then later pretended it was a breeze? This is all difficult material. Don't be afraid to put in the work!

Struggle is natural, and required. Banging your head against the wall on an issue others appear to get easily is part of the game. Some material you find easy is difficult for others, and vice-versa. It is strongly recommended that you try hard to understand all the issues for yourself, and don't rely too heavily on help from others. The rule of thumb is -- put a significant effort in (but not more than between two hours, and up to one day), before you ask for help.

Once you feel you've grasped any piece of this project, you will do very well to help someone else with that material. You'll achieve greater grasp over material, and also prove to yourself you really do understand material, if you can teach it to someone else.

If you find that you are not yet ready to tackle this kind of collaboration, *don't get discouraged!* No one picks up all this material on the first try! Keep plugging away at the basics, and join in later on this project, or a later project !!

## Install
Mac OSX

* brew install miniconda
* conda create -n get_your_first_engineering_job python=3.9
    * Your shell should look similar to this:
        * (get_your_first_engineering_job) charlie:get_your_first_engineering_job charlie$
* conda init bash
* close, reopen shell, then 
    * conda activate get_your_first_engineering_job
* conda install flask
* conda update -n base -c defaults conda
* pip install python-dotenv
* type `flask run`
    * You should see messages like this:
``` * Serving Flask app 'hello.py' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
## Branching and Merging
* Each contributor is welcome to perform each task listed in the [get_your_first_engineering_job repo](https://github.com/charliemcelfresh/get_your_first_engineering_job/issues). We'll choose one contributor's code, and merge it. You must receive an approval from another contributor, before you may merge your PR.
* We're going to merge directly into main. Here are the basic steps:
    * `git checkout -b 01-issue`
    * `git commit -am "Fixed README"`
    * `git push origin 01-issue`
    * Open a pull request [here](https://github.com/charliemcelfresh/get_your_first_engineering_job/pulls)