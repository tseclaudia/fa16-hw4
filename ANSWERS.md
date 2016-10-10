## Questions

1. What is the difference between new and create for a model?
.new only creates a new instance of an object but doesn't validate it or save it to the database. .create instantiates a new object, validates it, and also saves it to the database.

2. What command combined with new will emulate the same behavior as create?
.save will first validate the new model and then create it in the database if the model is new and update the model if it already exists.

3. What is the default integer column that exists on every table but we did NOT define?
Actice Record Migrations automatically creates the integer column named id when creating tables.

4. What single line of ruby code can insert a cat with the name "Kira" in the database?
cat = Cat.create(name: "Kira")

5. How did you like this homework in comparison with the previous homeworks?
I liked last week's homework more simply because I think making forms is more interesting. 
