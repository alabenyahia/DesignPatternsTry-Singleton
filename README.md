In OOP a singleton class can have only one object (an instance of the class) at a time.
After first time if we try to instantiate the singleton class the new variable also points to the first instance created.
To design a singleton class : 
1- Make constructor private.
2- Write a static method that has return type object of this singleton class.

The difference in normal and singleton class in terms of instantiation is that for normal class we use constructor,
whereas for singleton class we use getInstance() method.
