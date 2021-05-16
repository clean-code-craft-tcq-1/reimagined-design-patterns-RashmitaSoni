Mediator Design Pattern

“Mediator” in the dictionary meaning called intermediator or in simple words thing that act as a middle man in between two or multiple objects.  

1. How the pattern works, what the basic idea of the pattern is?

   The basic idea: If multiple objects needs to communicate with each other, then this design pattern comes into picture to reduce the complexity of communication of multiple objects with each other.

   How it works: When multiple objects need to communicate with each other, then a middle man is introduced which we called as Mediator (a class) which helps in establishing communication or interactions between different objects or classes throughout the software application. 
2. What kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example.

   Let’s understand the concepts with a real life example, Air Traffic Controller is best example for this pattern. Suppose we have three flights F110, F216 and F265. Now these flights have to land or take off on a particular terminal but if two flights land on the same terminal it causes collision.

   So these flights need to communicate to each other for the correct timing of landing or taking off on the terminals. One way is these flights are communicating directly to each other, but this is an inefficient approach. 

   To solve the problem of collision the best approach is Air Traffic Controller (Mediator). Suppose flight F110 need to land on some terminal at some particular time, so it sends its message to the Air Traffic Controller and the mediator checks the availability of the terminal on that time in its database and communicate back to the flight F110.

   Hence, this pattern comes into picture when objects or classes need efficient communication establishment between them.

3. What the main advantage and what the main disadvantage is of using this pattern 

   Main advantage: Improves code readability and maintainability.

   Main disadvantage: Mediator becomes complex and hence difficult to maintain.

