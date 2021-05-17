Decorator Design Pattern

1. How the pattern works, what the basic idea of the pattern is?

   The basic idea: Decorator design pattern allows the user to add new functionality to an existing object without altering its already existing structure. Also called Wrapper Design Pattern and comes under structural design patterns.

   How it works: This design pattern comes into picture when we don’t need to disturb the existing structure and also need to add the additional functionality at runtime. In simple words it attach additional responsibilities to an object dynamically without altering the existing structure. It act as wrapper as it wraps the original object and allows us to add additional functionality at runtime. 

2. What kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example.

   Let’s understand better using one example, so ‘Wearing Clothes’ is a good example to understand this design pattern. So in winters, if you are feeling too cold you simply wrap yourself using a sweater. Even after wearing a sweater you are feeling cold, so you can wrap jacket around you. Now suppose it starts raining so you can put raincoat on. So usually we don’t wear these clothes, if we don’t need them we can easily remove them.

   So basically you are wrapping yourself with clothes according to weather requirement similarly decorator design pattern allows to add new functionality at runtime without disturbing the existing structure of the object.

   It solves the problem to add behavior or state to individual object at runtime. Inheritance is not feasible because it is static and applies to an entire class.

3. What the main advantage and what the main disadvantage is of using this pattern

   Main advantage: It is flexible than inheritance because inheritance adds responsibility at compile time but decorator pattern adds at run time.

   Main disadvantage: High complexity of software (especially decorator interface)
