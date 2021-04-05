# Reading assignment 4/5/2021
By Nguyen Duy Phu Quang 15890 
## What is OOP
Articles links: [1](https://www.educative.io/blog/object-oriented-programming?fbclid=IwAR0FYA60UgsawcBmMs5VLa20Hz3HWiipo4TCTCp84dORWRwprR56Hb1xims) and [2](https://www.freecodecamp.org/news/object-oriented-programming-concepts-21bb035f7260/?fbclid=IwAR25fhCwJlXFLg-DQsCtnlYEmlSWviLLXM8C7fLe7-wXphaIBTCD_om0Vno)

##### OOP definition

Object Oriented programming (OOP) is a programming paradigm that relies on the concept of classes and objects.
A class is abstract blueprint used to to create more specific, concrete objects and it contains **attributes**.These classes define what attributes an instance of this type will have, like color, but not the value of those attributes for a specific object.
A Class can also contain functions, which called **methods** available only to objects of that type.
**BENEFIT OF USING OOP**
- Reproducible,simple structures.
- Reusable.
- Esiear to debug.
- Secure, protects infomation.

##### Structure of OOP programs 
Grouping all related information together and organizing the OOP program:
- Create parent class.
- Create children class.
- Add unique atrributes and and behaviors.
- Create objects from the child class.

**A OOP programs fundamental: **
- Classes
  - classes are essentially user defined data types
  - Classes contain fields for attributes, and methods for behaviors. 
- Objects
  - Objects are instances of classes created with specific data.
- Methods
  - Methods represent behaviors. Methods perform actions; methods might return information about an object, or update an object’s data.
  - Methods often modify, update or delete data.
- Attributes
  - Attributes are the information that is stored.
  - The state of an object is defined by the data in the object’s attributes fields. 

##### Four Principles of OOP
- Inheritance: child classes inherit data and behaviors from parent class.
- Encapsulation: containing information in an object, exposing only selected information
- Abstraction: only exposing high level public methods for accessing an object.
- Polymorphism: many methods can do the same task

**inheritance**
- Inheritance allows classes to inherit features of other classes. Put another way, parent classes extend attributes and behaviors to child classes.
- Basic attributes and behaviors are defined in a parent class, child classes can be created extending the functionality of the parent class, and adding additional attributes and behaviors.
**Encapsulation**
- Encapsulation means containing all important information inside an object, and only exposing selected information to the outside world. 
- Encapsulation requires defining some fields as private and some as public:
  - Private/ Internal interface: methods and properties, accessible from other methods of the same class.
  - Public / External Interface: methods and properties, accessible also from outside the class.
- attributes and methods can be set to private, so they can’t be accessed outside the class.
**Abstraction**
- Abstraction means that the user interacts with only selected attributes and methods of an object.
- Abstraction is using simple classes to represent complexity. Abstraction is an extension of encapsulation. 
- By only displaying selected pieces of data, and only allowing data to be accessed through classes and modified through methods, we protect the data from exposure. 
**Polymorphism**
- Polymorphism means designing objects to share behaviors. Using inheritance, objects can override shared parent behaviors, with specific child behaviors.
- Polymorphism execute different behaviors in two ways: method overriding and method overloading:
  - Overloading method:
    - Methods or functions may have the same name, but a different number of parameters passed into the method call.
    - Different results may occur depending on the number of parameters passed in.
  - Overriding method:
    - Method overriding, a child class can provide a different implementation than its parent class. 

