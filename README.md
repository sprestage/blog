[![Dependency Status](https://gemnasium.com/sprestage/blog.png)](https://gemnasium.com/sprestage/blog)

What is it?
=======

A basic rails app with static pages.  I used  minispec and capybara to BDD this app.  I created a Home
controller to handle the static pages.  I customized the HTML template a little.  I set up some basic
Rails routing.


Critical failures
=======

This doesn't currently run since the RailsCast (#250) that I used was using rails 3 and I tried using rails 4,
not realizing the challenges involved in switching to strong params.  I know how to do this now (as
evidenced in my trakehner-db project.  I should get back to this at some point and implement strong params
to get this working properly.  No time right now, so use at your own risk.  -sprestage
