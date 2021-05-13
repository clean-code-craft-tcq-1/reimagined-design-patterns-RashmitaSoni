Memento Design Pattern

"Memento", in dictionary meaning, also called as remembrance, memorial, token, etc. (like The Statue of Unity is made in memorial of Vallabhbhai Patel)

1. How the pattern works, what the basic idea of the pattern is?
   The basic idea: This pattern is to restore the state of an object to its previous state. Sometimes happened, that objects in software’s are keep on updating and changing time   
   to time. And sometimes we required to get back to the previous state of that object so this design pattern gives the capability to restore the previous state of any object. 
   In simple terms Memento Design Patter supports the UNDO operation.

   How it works: The Memento captures the object’s internal state so that the object can later be restored to that state. In simple words, this pattern gives the capability to 
   perform or achieve unlimited number of times, Undo and Redo operations. 

2. What kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example.
   When to Use: Whenever we need to perform Undo, Redo or Ctrl + Z operation then we go for Memento Design Pattern.
   For example in Microsoft Power Point or Microsoft Word we are performing Undo and Redo operations, hence we use this pattern.
   
3. What the main advantage and what the main disadvantage is of using this pattern
   Main advantage: Provide capability to restore objects previous state. In simple words allows to perform Undo or Rollback operations
   Main disadvantage: Extra memory is required because we need to store the previous as well as current state of the objects hence it results in extra memory conjunction.
