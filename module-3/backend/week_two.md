Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!).

Note: When you're done, submit a PR.

1. What's OAuth?
 * OAuth is an a token based authentication sevice on the web. It allows for multiple services to use a User's information without exposing their password.

2. What are some advantages/disadvantages of implementing OAuth?
* Several advantages of OAuth are that we, developers, do not need to handle the authorization process fo our site and instead use OAuth to take care of it.

How many exhanges of information need to take place before a user is authenticated with OAuth?
* There are 5 exchanges between my application an OAuth to vet the user. 1. The  browser/client initiates the request. 2. The server authenticates the user, returns authorization code. 3. The browser/client requests a token. 4. the server provides that token. 5. now the client has access. So 4 steps are taken to provide authentication with OAuth.
Why do we want to create services?
* A service gives us access to the API.

Why is it good practice to create PORO's with the data received from an API?
* Using a PORO for the data received from the API, gives us access to that information without having to save to our database and bloating it.

What do we use VCR for? Why is it a good idea to use this tool?
* Using VCR allows us to test our API endpoints without having to constantly ping it, making for faster response time. 

Review

What does HTTP stand for?
* HTTP stands for Hypertext Transfer Protocol.

How do you create the following table in SQL? In Active Record?
(Users table with columns first_name, last_name, email, and age)
* ActiveRecord
* create_table(:users) do |t|
t.string :first_name
t.string :last_name
t.string :email
t.string :age
end

* SQL
 * create_table "users"
 ("first_name" "string",
  "last_name" "string",
   "email" "string",
   "age" "string");


Writing Files: given a text file located at "/Documents/pizza.txt", write code to read the file from the filesystem, then write a new file at "/Documents/line_count.txt" containing the number of lines in the original file.


Self Assessment

Rate yourself on the following scale.
 4. I know and understand all these concepts and did not have to look anything up
3. I know and understand most of these concepts but had to look something up
2. I am uncertain about some of these concepts and had to look some things up ^^

I am feeling lost about with these concepts and had to look many things up ^^
^^ Please let an instructor know where you'd like support to catch you up.
* I would give myself a three for this checks for understanding questionaire. What I need to focus on is creating a structure and abiding by that structure during projects. Using something like Waffle, I know I need to do this but yet have failed to implement it the past two projects. 