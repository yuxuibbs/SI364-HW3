# Homework 3 - SI 364 W18

### Deadline: February 11, 2018 at 11:59 PM

## To submit

* Fork and clone this repository.
* Submit the link to your fork to the Canvas assignment as specified on Canvas.

## Instructions

There are a number of tasks to complete, mainly in the `SI364W18_HW3.py` file, in order to replicate [this application](sample364hw3.herokuapp.com/) locally.

Each of the things you need to do is marked with a comment including **`TODO 364`**.

For some, there are also hints!

The majority of the 1000 total points for this assignment come from, approximately in order:

* The correct view functions to fill in that are provided (`index`, `see_all_users`, `see_all_tweets`)
* Creating the form and custom validation for it
* Defining the models
* Adding the `longest_tweet` route properly (see instructions in the file)
* Doing the app setup (e.g. creating a database) according to the instructions

However, that is *not* the order in which you should complete these tasks, because some can't be done without the others!

*We will not grade code that does not run.* Make sure yours runs, even if it does not have every feature you want in it.

**We recommend this approximate order of tasks:**

* Consider and write/draw out the things you'll need to do and how data will move through the application. Make sure you understand the problem(s) at hand.
* First do all the app setup. Make sure you've created a database, etc, and fill in that URL...
* Define the form and test it out.
* Define your models.
* Work on, and then test, your scaffolded view functions, including making the database queries (which you can also check with the Flask shell as shown in class!)
* Add the `longest_route` view function and corresponding template.
* Test it all again.


## Files and structure included

### Provided:

* Custom error routes for 404 and 500 errors
* Custom error templates
* Other templates:
    * `base.html` (the basis from which others inherit)
    * `index.html`
    * `all_users.html`
    * `all_tweets.html`
* Necessary import statements and some parts of necessary app setup
* Scaffolding comments

### You should add:

* A form class definition
* Model class definitions
* A bunch of code, as specified in the `SI364W18_HW3.py` file
* 1 template (see the instructions for `longest_route` at the end of the .py file)

You should *not* change any file names or edit provided templates.
