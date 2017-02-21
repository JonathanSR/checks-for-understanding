## Week Four Recap

### Instructions
Fork this repository. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

* What is a cookie?
  * A cookie is an item that stores data from the user's broswer session.
* What’s the difference between a session and a cookie?
  * A cookie stores data in the browser while a session is stored on the server side. Sessions are more secured than cookies.
* What’s a flash and when do you want to use flashes?
  * A flash passes information between actions, which is useful when you want to alert the user when an object has been created, destroyed or updated.
* Why do people say “HTTP is stateless”?
  * HTTP is stateless because it does not require the server to retain session information between multiple requests.
* What’s authentication? Explain.
  * Authentication is the process of identifying a a user/session.
* What’s the difference between authentication and authorization?
  * Authorization is the process of verifying that the user that was authenticated has certain access privilages.
* What’s a before filter?
  * A before filter is a method that is used in the controllers that runs a piece of code before anything else in that controller.
* How do we keep track of a user once they’ve logged in?
  * The user is kept track of by initiating a session that stores that user's data, like the user's id.
* When do you want to namespace a resource? When do you want to nest a resource? What's the differences between those two approaches?
  * 
* At a high level, what tools can you use to implement authorization? How would you use them?
  * Tools such as a before action, enums help us implement authorization. A before action method would check the user's privilages before running the code. An enum allows us to 
* What's an enum, and what advantages does it offer? What data type needs to be in your database to use an enum? Where do you declare an enum?
  * An enum sets a variable to a predifined constant. The enum is declared in the model of the affected database.
* What are some strategies you can use to keep your views DRY?
  * Creating similar forms, search bars, etc in anothe file and calling that file into the view being worked on.
