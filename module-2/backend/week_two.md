## Week Two - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON - YOU are a web developer!!!). 

Note: When you're done, submit a PR. 

1. At a high level, what is ActiveRecord? What does it do/allow you to do?
  ActiveRecord is a library, the model in the MVC structure, which is resposible for representing business data and logic. It provides an ORM framework that is wrapped around a relational database. It allows us to wrap our data in Ruby objects so that we can manipulate them. 

2. Assume you have the following model:

```ruby
class Team << ActiveRecord::Base
end
```

What are some methods you can call on `Team`? If these methods aren't defined in the class, how do you have access to them?
I can call find, group, select, where. 
If the methods aren't defined in the class then I am not sure as how we have access to them.

3. Assume that in your database, a team has the following attributes: "id", "name", owner_id". How would you find the name of a team with an id of 4? Assuming your class only included the code from question 2, how could you find the owner of the same team?
 ```ruby
  team4 = Team.find(4)
  team4.name
end
```

```ruby
  team4 = Team.find(4)
  team4.owner_id
  end
  ```

4. Assume that you added a line to your `Team` class as follows:

```ruby
class Team << ActiveRecord::Base
  belongs_to :owner
end
```

Now how would you find the owner of the team with an id of 4?

```ruby
  team4 = Team.find(4)
  team4.owner
  end
  ```

3. What do they allow you to do?
????

7. In a database that's holding students and teachers, what will be the relationship between students and teachers? Draw the schema diagram.

8. Define foreign key, primary key, and schema.
Foreign key - Is the key associated from one table that links up to another.
Primary key -  Is the unique identifier for the table that it is present in.
Schema - is the blueprint of what our tables look like.

9. Describe the relationship between a foreign key on one table and a primary key on another table.
The foreign key on table 1 is associated with table 2, table 1 has a primary key that belongs to itself. While table 2's primary key not only belongs to itself but it also used to establish the link to table1.
10. What are the parts of an HTTP response?

11. Describe some techniques to make our Sinatra code more DRY. Give an example of when you would use these techniques.
????

### Optional Questions

1. Name your five favorite ActiveRecord methods (i.e. methods your models inherit from ActiveRecord) and describe what they do.
  Pluck - It maps over an array.
  Sum - It adds up the specified field.
  Where - It finds record with single or multiple arguments.
  Limit - It limits the return of records to what you specify.
  Exists? - It returns a boolean value of wether your record exists or not.

2. Name your three favorite ActiveRecord rake tasks and describe what they do.
rake db:migrate:reset - This runes drop, create and migrate, therfore dropping your database, creating it and migrating the migrations.
rake db:test:prepare - This setups your test environment.
rake db:seed - This seeds your database.

4. What can you expect from a group as you begin working together? As you continue working together?

5. What two columns does `t.timestamps null: false` create in our database?
This creates two time columns, one is a created at and the other is updated at, the updated column changes with every update to that specific row/object. 

6. What cURL flag can you use to send a `POST` request?

7. What case does JSON (and JavaScript) use for multi-word variables?
8. What case does Ruby use for multi-word variables?
9. In a database that's holding schools and teachers, what will be the relationship between schools and teachers?
Schools and teachers is a one to many relationship. A school can have many teachers and a teacher can have one school.

10. In the same database, what will you need to do to create this relationship (draw a schema diagram)?
The two tables, schools and teachers, would be joined by the primary key of the school that would become the foreign key in the teachers table.

11. Give an example of when you might want to store information besides ids on a join table.
When attributes are created or become byproducts of joining two tables together.

12. Describe and diagram the relationship between patients and doctors.
13. Describe and diagram the relationship between museums and original_paintings.
14. What are some examples of acceptable values for the parts of an HTTP response?
15. What types of output do we want to test when we test our controllers?
16. What could you see in your code that would make you think you might want to create a partial?
17. Why might you use a helper method?
