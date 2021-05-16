Composite Design Pattern

“Composite” in the dictionary meaning called things made up of several parts or elements. 
1. How the pattern works, what the basic idea of the pattern is?

   The basic idea: This design pattern is come into picture when there is a scenario where there is a need to create objects which represent a tree structure. Also this pattern allows you to treat individual object (leaf object) and composite object uniformly (equally). That means if any operation is performed on individual object same operation can be performed on composite objects as well.
   
2. What kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example.

   Let’s explore this with an example: In an organization we have organization hierarchy which somewhat represents a tree structure, suppose, on first level we have General Manager then under this we have 3-4 Sub Managers then under each manager we have several Developers/Technicians. This represents a hierarchy (tree structure). 
   
   Now in above example ‘General Manager’ and ‘Sub Manager’ are Composite objects because they have child objects/elements under them and they made by composing two or more objects under them. And Developer object do not have any child under them so these objects are called leaf objects.
   
   As we know that this design pattern allows to treat leaf and composite objects equally hence we can perform one operation to get salary of composite objects (General and Sub Managers) and leaf object (Developers).
   
   For such kind of scenarios we can approach for Composite Design Patterns
3. What the main advantage and what the main disadvantage is of using this pattern 

   Main advantage: We don’t have to take care for concrete objects, if we have an operation it applies to all objects down the tree. For example one operation of getting salary can be implemented for all objects (General/Sub Managers and Developers) down the tree at one go.

   Main disadvantage: Complexity of making objects and implementing the tree data structure

