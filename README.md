Question No 1 Differentiate between method overriding and method overloading with an example.

Method Overloading:

Definition: Method overloading occurs within a single class when multiple methods share the same name but have different parameter lists. 
Purpose: It allows a class to provide multiple ways to perform a similar operation, differentiated by the type, number, or order of arguments provided. 
Resolution: Overloaded methods are resolved at compile-time (static polymorphism). The compiler determines which specific method to call based on the arguments passed. 
Inheritance: Inheritance is not required for method overloading; it can be implemented within a single class.

Method Overriding:

Definition: Method overriding occurs between a parent class (superclass) and a child class (subclass) when the child class provides a specific implementation for a method that is already defined in the parent class. The method signature (name, return type, and parameters) in the child class must exactly match that of the parent class. 
Purpose: It allows a subclass to provide its own specialized behavior for a method inherited from its superclass, tailoring it to the subclass's specific needs.
Resolution: Overridden methods are resolved at runtime (dynamic or runtime polymorphism). The actual method called depends on the type of the object at runtime, not the reference type.
Inheritance: Inheritance is a prerequisite for method overriding, as it involves a relationship between a parent and child class.

Question No 2 Describe the role and types of constructors in Python with a suitable example. 

a constructor is a special method used to initialize a newly created object. Its primary role is to set the initial state of an object by assigning values to its attributes. The constructor in Python is always named _init, and it is automatically called when a new instance of a class is created.
