1. What is the difference between new and create for a model?
New instantiates a new object (can be empty) but you have to manually go save it.
Create creates a model and saves it to the database. 

2. What command combined with new will emulate the same behavior as create?
create(attribute=something){}.save

3. What is the column that exists on every table but we did NOT define?
Timestamp and ID

4. What single line of ruby code can insert a cat with the name "hat" in the database?
c = Cat.create name:"Boots", age:3

5. What was the most confusing part over the last few weeks?
HW2 was quite difficult. On this homework I had alot of issues with virtualbox as things were not showing up correctly.

6. How did you like this homework in comparison with the others?
This is good. 