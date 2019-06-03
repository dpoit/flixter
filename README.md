# Flixter

A two-sided, video-streaming marketplace platform that features credit card payment capabilities, user role management, complex user interfaces, and advanced database relationships.

## URL

[http://flixter.dannypoit.com/](http://flixter.dannypoit.com/)

## Users

Use the 'Sign up' and 'Sign in' links at the top right to create a user and log into it. 

![](https://i.imgur.com/ir3RpKy.png "Sign up and Sign in links")

Creating a user will allow you to enroll in courses, pay enrollment fees, and keep track of all the courses in which you are enrolled. It will also allow them to create their own courses that they can then offer for sale to other users.

## Viewing a course

To view courses, users can click either 'See All Courses' at the top left or 'Browse Courses' in the middle of the hero section. 

<img src="https://i.imgur.com/aEVL9hl.png" alt="See All Courses and Browse Courses links" width="700"/>

From the courses page, scroll to find the course you want, then click either the title of the course or 'More Details...' 

<img src="https://i.imgur.com/OnR0ICr.png" alt="More Details button" width="500"/>

The course details page will show you the lessons available for that course, but you will not be able to view the lesson material unless you are enrolled in the course. 

<img src="https://i.imgur.com/6apqSCn.png" alt="Course details page" width="500"/>

To enroll in the course, click 'Pay with Card'. A pop-up window will open in which you can enter your credit card information to pay for the course.

<img src="https://i.imgur.com/y7yMFFl.png" alt="Pay with Card" width="500"/>

**PLEASE NOTE: The payment module is currently in test mode, but please do not enter actual credit card information at this time.**

Once paid, the user will be enrolled in the course and will be able to view the lessons.

<img src="https://i.imgur.com/SkhjAze.png" alt="View lesson" width="500"/>

The user can returned to a course they are enrolled in at any time by navigating to it or by clicking 'Dashboard' from the top right, which will show them only the courses in which they are enrolled.

<img src="https://i.imgur.com/r5cE7l6.png" alt="Dashboard" width="700"/>

## Creating a course

To create a course, click 'Create a course' from the footer section.

<img src="https://i.imgur.com/7VW3nZ2.png" alt="Create a course" width="500"/>

Enter the title, description, and cost for the course. Then, choose an image to upload that will serve as the main image for the course. Then, click Create.

<img src="https://i.imgur.com/lEYhB8t.png" alt="Add a new course" width="500"/>

Then, you can add Sections and Lessons. Sections are groups of lessons that only have a title. Lessons have a title, subtitle, and a video file. You can also 'Preview as student...' to see what the course will look like to students.

<img src="https://i.imgur.com/0EhW5Ns.png" alt="Adding sections and lessons" width="500"/>

## Adding more sections and/or lessons to a course

To add more sections and/or lessons to a course you've created, return to the course page and click 'Manage this course'. 

<img src="https://i.imgur.com/nR4mGAT.png" alt="Manage this course" width="500"/>

This will take the instructor back into the editing mode where they can add sections and lessons. Note: You can only add sections and/or lessons to courses you have created.

## Tech used

* [Rails](https://rubyonrails.org/) (5.0.7.2)
* [Bootstrap](https://getbootstrap.com/) (4.3.1)
* [simple_form](https://github.com/plataformatec/simple_form) (4.1.0)
* [Devise](https://github.com/plataformatec/devise) (4.6.2)
* [CarrierWave](https://github.com/carrierwaveuploader/carrierwave) (1.3.1)
* [Figaro](https://github.com/laserlemon/figaro) (1.1.1)
* [AWS](https://aws.amazon.com/)/[fog-aws](https://github.com/fog/fog-aws) (3.4.0)
* [ImageMagick](https://imagemagick.org/)/[MiniMagick](https://github.com/minimagick/minimagick) (4.9.3)
* [Stripe](https://stripe.com/) (4.11.0)
* [ranked-model](https://github.com/mixonic/ranked-model) (0.4.4)
* [jQuery UI](https://jqueryui.com/) (6.0.1)
* [Font Awesome](https://fontawesome.com) (4.7.0.4)

## Authors

* **[Danny Poit](https://github.com/dpoit)**

## Acknowledgments

* [The Firehose Project](http://thefirehoseproject.com/)
