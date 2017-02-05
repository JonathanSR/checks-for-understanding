## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.
  Get - it retrieves informatiom
  Post - it sends the information
  Puts - it displays the current information
  Delete - it deletes the information

2. What is Sinatra?
  Sinatra is a "server" implemented in Ruby that is used for writing web apps.

4. What is MVC?
    MVC(models, views, controllers) is the format that is used for writing web apps.

5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?
    Following conventions makes it easier to read the code for anyone new to the project.
    It's an established pattern within the community.

6. What types of variables are accessible in our view templates without explicitly passing them?
    Variables in the model are accessible within the view templates.

7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
  
  ```ruby
  get '/horses' do
    erb :index
  end
  ```
Within the view file we would call horses.count.

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed` to the view?
    horses.name

9. What's the purpose of ERB?
It's purpose is to display information to the user

10. Why do I need a development AND test database?
To keep data from mixing within all stages.

11. What's responsive design?
Responsive design adapts to the user's screensize.

12. What is CRUD and why is it important?
CRUD(create, read, delete, update) is the format that web development and all apps follow. Following CRUD gives us all main functionality of an app/page.

13. What does HTTP stand for? 
HTTP stands for Hyper Text Transfer Protocol.

14. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?
One way is to inject ruby in the ERB file within <%= %>
The second way is to call a method created in the models section by <% %>
The second way is prefered as we want to keep single responsibilty and ERB's main focus is to display info.

15. What's an ORM?
ORM stands for Object Related Mapping, which allows us to convert and use data in Ruby or other OOP languages.

16. What's the most commonly used ORM in ruby (Sinatra & Rails)?
ActiveRecord

17. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.


18. What's a migration? 
A migration creates/updates/deletes our table model.

19. When you create a migration, does it automatically modify your database?
Creating a migration gives us the ability to modify the database but its not after it has run that it then modifies it.

20. How does a model relate to a database?
The model is the object that will be created from the database.

21. What's the difference between agile workflow and waterfall method?
Agile workflow runs in having workable code at all iterations while waterflow builds out independent features.

22. What is the difference between `#new` and `#create`?
New creates an object but does not save it while create, creates and saves.
