## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What is Webpack and why is it useful?
* Webpack is module bundler. It's main purpose is to bundle JS files for usage in a browser. It's comparable to the asset pipeline in rails. 
2. When do you want to use event delegation?
* We would want to use an event delegation when we have multiple event listeners on newly created DOM nodes. Tho, this may cause a memorly leak if the event listeners are not unbound from the element once its removed from the DOM and rather than managing the addition and removal of event listeners. The event listener is  set on the parent and it looks for event that match it in its child elements.
3. What's one difference between ES5 and ES6?
* String interpolation is easier to write, more Ruby like. example, "Hello" + student.name + "." vs `Hello ${student.name}.`
4. What's the deal with semi-colons in JavaScript?
* Semi-colons are not required in JS, it's more of a style choice, tho and on going piece of advice that I keep receiving is to use them until I have a good reason to not. 
5. How are you using the MVC design pattern in your Quantified Self project?
* In Quantified Self, the MVC pattern is being implemented in the following ways. The model for my food object harbors the CRUD functions, the views are being executed on the front end of the application, with the HTML views using JS. The controller is my delegator for the api calls that get executed, it directs that call to the proper function.
6. How do you execute raw SQL in node?
* To execute raw SQL in node we use database.raw. An example, database.raw('SELECT * FROM foods WHERE id = ? LIMIT 1')
7. What is CORS?
* CORS stands for Cross-Origin Resource Sharing, it's purpose is to allow sites to use data(apis) from a specific source.
8. What are some steps to avoid CORS?
* steps to avoid CORS is to enable CORS.

#### Review  

9. Why do people say "HTTP is stateless"?
* HTTP is stateless because the sessions intitated are not saved by the server, the session and its information are lost once the communication between the browser and the server is closed.
10. What is a RESTful API?
* A restful api is one that follows and uses HTTP requests to GET, PUT, POST, and DELETE data.
11. What are some main characteristics of a team following an agile workflow?
* Some characteristics that define agile workflow in a team setting are using tools such as pivital tracker to manage stories. This allows team members to be aware of what has been acomplished, what is next, where each member stands. Having good code review practice, being able to make suggestions on code that helps out the overall application is good. 
12. What are some advantages/disadvantages to using OAuth to authenticate a user?
* Advantages of Oauth are that you hand of the authentication/authorization part to another service that probably is more secure that making your own. It's quicker to implement and you can implement more than one provider, Facebook, Google, Twitter.
* One major disadvantage is that you are restricted to that providers service, its not flexible if you want to have other things going on in your authorization/authentication.
