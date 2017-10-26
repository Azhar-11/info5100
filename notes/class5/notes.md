Polymorphism
	- Method Overloading : Happens in the same class
		- Methods have a same name but different input parameters and same return types
	- Method Overriding : Happens in the child classes

<<Base class reference can point to child class object>>

Abstract classes
	- Base class whose objects can't be created
	- They are marked as abstract
	- They can have abstract methods

When you have a class and you believe that you can't create the object of this class - make it abstract


Interfaces

	- Interface is a special type of an abstract class that has only definitions of behaviors
	and no implementation. It is considered as a contract of an object
	- interface is a keyword that can be used instead of class when defining it
	- A class can implement multiple interfaces using implements keyword
	- A class should write code for all the methods defined in the interface
	- An interface reference can point to an object that is implementing this interface	

final keyword

```java
- final instance variables can't be changed **once set**
- final methods can't be override
- final classes can't be subclassed
```


static 
```java
- static fields are common data for all the objects of a particular class
- static fields can be accessed by the class
- static methods can be invoked by the class
- static methods can't access non-static (aka instance) fields
- non static methods can access static fields
```

packages

```java
- a logic way of grouping related classes in java
- Create a folder for a package and define classes in that package
- Make sure that the first line in the class has package <name_of_package>;
- Classes defined in package can be imported into other package by using import <package_name>.class 
- Classes defined in package can be imported into other package by using import <package_name>.*
- java.lang package is available to all classes by default
- default scoped variables or methods or classes can only be accessible by all the other classes in the package
```


​	
​	

