# SDA
TOPIC : POLYMORPHISM

DEFINITION:
Polymorphism is a core concept in object-oriented programming (OOP) that allows objects of different classes to be treated as objects of a common superclass.

TWO TYPES OF POLYMORPHISM
  Compile-time Polymorphism (Method Overloading): 
Achieved by function overloading or operator overloading.

  Runtime Polymorphism (Method Overriding):
  
 Achieved through inheritance, where a subclass can provide a specific implementation of a method that is already defined in its superclass.
Upcasting:

In the main method, we create references of type Animal but instantiate them with Dog and Cat objects. This is known as upcasting, allowing a superclass reference to refer to subclass objects.
Method Call:

The animalSound() method takes an Animal object as an argument. When we call this method with myDog and myCat, it invokes the speak() method specific to the actual object type, demonstrating runtime polymorphism.
Even though the method animalSound() expects an Animal, it correctly calls the speak() method of the Dog or Cat class based on the object passed in.

Description:
Base Class (Animal): Defines a method speak() that can be overridden by subclasses.
Derived Classes (Dog and Cat): Each class provides its own implementation of the speak() method.
Main Class (PolymorphismExample):
In the main method, Animal references are created for Dog and Cat objects (upcasting).
The animalSound() method is called with different Animal references, demonstrating runtime polymorphism by invoking the correct speak() method based on the actual object type.
