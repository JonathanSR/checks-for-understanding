## Week Three Recap

### Instructions
Fork this repository. Be sure to pull the latest changes to your local repo. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

1. What is the entry at the command line to create a new rails app?
  Rails new will create a new app, at the same moment variables can be combined to include or exclude certain programs that run beside it.

2. What do Models generally inherit from in rails?
Models inherit ActiveRecord::Base if the rails app was initiated in a version of rails 4.

3. What do Controllers generally inherit from in a rails project?
Controllers inherit from ApplicationController in versions of rails 4.

4. How would I create a route if I wanted to see a specific horse in my routes fitle assuming I'm sticking to standard conventions and that I didn't want other CRUD functionality?
We would use the resources method in the routes.rb file, calling the following syntax, resources :horses only:[:show].

5. What rake task is useful when looking at routes, and what information does it give you?
Rake routes shows us all available routes in our rails app.

6. What is an example of a route helper? When would you use them?
horses_path is an example of a route helper that helps us reroute to the index page of horses regardless of where we are.

7. What's the difference between what `_url` and `_path` return when combined with a routes prefix?


8. What are strong params and why are the necessary?
Strong params, keep our forms by being tampered with by checking that the information provided is assigned to that specific key. No tampering.

9. What role does `form_for` play in helping us create our forms?
Form_for "horse" gives our for the ability to add attributes for that object.

10. How does `form_for` know where to submit the user's input?
Form_for knows where to submit the data and where to route due to the object called at the beggining of the form. example Form for horse, the form submit button is going to be looking for a post route that pertains to horse.

11. Create a form using a `form_for` helper to create a new `Horse`. 
Form for @horse do |f|
f.label :name
f.text_field :name
f.submit
end


12. Why do we want to validate our models?
We want to validate our models to make sure that our models have all complete attributes. 
