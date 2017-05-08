## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
* The most useful thing that I learned from the intermission work was learning what a function in javascript is, how to define one and that it has many uses.
2. What are some tools to help debug JavaScript code?
* Some tools to help with debugging in JS are console.log and debugger.
3. What are some tools you need in order to unit test your JavaScript?
* Some tools needed to unit test in JS are express, mocha, chai, npm.
4. What is the syntax for invoking a function?
* To invoke a function we call it with () at the end of its name, with the needed params inside of ().
5. What's the difference between `==` and `===` in JavaScript?
* == is an abstract comparision,while === is a strict comparison, it will return false if the types are different.
6. What's the difference between asynchronous and synchronous JavaScript? 
* Asynchronous runs in no particular order, while synchronous runs in order. Asynchronous has benefits with speed.
7. What's a callback function and what are some reasons when we use/need callback functions?
* A callback function is a function that is passed to another function as a parameter. We use this to pass around the function definition until we need to execute it.
8. What's the biggest difference between a promise and a callback?
* A promise can be used to work synchronously while a callback is used async.
9. How do we setup a route when creating an API with Node and Express?
* To set up a route we create a variable app that is set up to the express framework. Then we set up our route as app.get('/api/foods, function(request, response{//code goes here}));
10. What's `npm` and what do we use it for?
* NPM is the javascript version of rails gemfile, its a package manager that allows us to install various libaries into our application. It stands for Node Package Manager. 

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
* The MVC pattern, model, views and controller is a pattern used commonly in the rails community. Model is an object, the Controller delegates the responses received, the view displays our information.
12. What is AJAX? What are some benefits of using AJAX?
* 
13. What's a background worker? When would we want to use a background worker?
* Background workers delay the action that its assigned to, usually implemented to increase speed on an application, can be used on 3rd party api calls, views and other sections of the app.