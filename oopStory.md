# objectOrientedJavaScriptStory

## The zombie apocalypse just happened. Alfred is stuck without any survival tools and he pulls into a Walmart parking lot. He doesn’t have any zombie survival tools and is excited to see what Walmart has to offer. Walmart is a store that contains everything in it (all objects), therefore, making it the parent object. An object contains a group of information. At Walmart (parent object) it holds many objects which are the sections in the store like food, medicine, clothing, and weapons.

## Alfred is headed over to an object, food. In the food section, he noticed the food was even further classified into more specific sections. Alfred walked the aisles and noticed the fresh produce, frozen food, canned food, and packaged food (6 months - 1 year shelf life). Alfred realized he needed to organize the food items so he can easily locate the items.


## Even though the first sets of classifications (produce/frozen/canned/packaged foods) are a good start, there were still so many subsections within that which are considered to be more objects in javascript. Objects hold more objects that are specific to it. For instance, produce(object) can be subdivided into fruits and vegetables. Fruits can be subdivided into dehiscent (fruits that readily release their seeds like peas) and indehiscent types (fruits that decay to release their seeds like peaches). Objects can have properties(key); in this case an apple, which is a fruit, would have a property such as the color red. Objects can also have methods(key and a function), this allows our object to do a physical task.

## There is a clean way to implement our code when referencing objects

## In this case let's use our fruit(object) analogy.

## There are four pillars in object - oriented JavaScript: encapsulation, abstraction, inheritance and polymorphism. Let's look at these four terms in terms of things Alfred would do at Walmart.


## Encapsulation achieves the concept of data hiding, providing security to data, by making the variable as private, and expose the property to access the private data which would be public. Alfred decides he is bored of  looking at fruit and he heads over to the mini aquarium section at Walmart. The fish are encapsulated in the fish tanks. The fish are also grouped together by similar characteristics. So goldfish are in the same tank just like catfish are grouped together, and blowfish are together. Alfred wants to touch the fish, but he is unable to because the glass barrier blocks his hands and the fishes are protected.

## Alfred decides he is bored of the fish since he can’t physically touch them. He walks back to the produce section. Abstraction is taking data and grouping them together and writing it into a real life model and a great way to do this is through classes. So when Alfred classifies his produce into fruits and vegetables and then places fruits into dehiscent vs indehiscent types, he’s abstracting attributes and grouping similar characteristics.

## Inheritance is enabling new objects to take on the properties of existing objects. Alfred notices that the GMO fruit are able to take on characteristics of the organic fruit thus being able to be classified the same way.

## Polymorphism is the final pilar. It provides an ability to call the same method (function) on different JavaScript objects. Even though the zombie apocalypse occured, Alfred feels a moral obligation to pay for his produce. He goes to the self-checkout and wants to purchase his fuji apple. He didn’t know the serial number for it, so he hits “look up item” and then hits “produce.” Here all the produce displays in alphabetical order. This is an example of calling a function; every possible product is shown.

## Constructor Functions are functions that hold properties for prototypes. For instance, since there are many aisles in Walmart, we would create a constructor function that has the properties of items that we want.

## Global object is an object that always exists in the global scope. When Alfred goes to checkout his Bananas, the scanner categorizes it as produce. The global object is the cash register since it can scan any object within Walmart and categorize it. The computer already has an algorithm coded to be able to calculate the sum of the price, sales tax, and any discounts; this is known as method. This equation is the exact same but can be applied to the checking out process at Walmart. If Alfred were to check out 3 items or 8 items - the machine will still produce the final amount owed.

## The function signature consists of the method name and the number of arguments the function required. The parameters of a function don't need to be declared within the body of the function because they are already declared inside the function header. When Alfred scans his foot cream, he doesn’t need to type in how much it costs, the machine already holds that information and the scanned barcode calls that information to display on the screen.

## Alfred is thoroughly depressed about the zombie apocalypse. He feels bummed out that he has to spend the next year living his best life at good ol’ Walmart. Nevertheless, he feels proud of his organization and ability to locate items he needs in an easy manner.








# Object Oriented JavaScript (OOP):

# Object-oriented programming
## Uses self-contained code to make applications
## Used to make code dry
## Follows prototype-based model opposed to classes
## Global based -- can put it wherever you want vs just putting it one spot
## Writing computer programs that are using the idea of "objects" to represent data and methods. Usually, computer programs were just a list of instructions to the ## computer, telling the computer to do certain things in a certain way, which is called procedural programming.
## The basic idea of OOP is that we use objects to model real-world things that we want to represent inside our programs, and/or provide a simple way to access ## functionality that would otherwise be hard or impossible to make use of.



# 2.Data Types

## Primitive
### 5 types
#### Boolean - returns true or false
#### Number - 5
#### String - ‘this is a string’
#### Null - value is unknown
#### Undefined - object that has been declared but not initialized or defined
### Boolean, number and string are the same literal; null and undefined are the same literal
## Reference
### Two types: object and arrays
#### Object
##### Used for literal values
##### This is known as an abstraction — creating a simple model of a more complex thing, which represents its most important aspects in a way that is easy to work with for our program's purposes.

####Arrays
##### Collections of data / variables



# Four Pillars

## Abstraction
### The Data or Hiding of Information
### creating a simple model of a more complex thing, which represents its most important aspects in a way that is easy to work with for our program's purposes.
## Encapsulation
### Binding of Data and Functions (that manipulate the data) together and keep both safes from outside interference and misuse is called Encapsulation.
### Data can be grouped together with functionality that operates on that data; also the definition of an object

## Inheritance
### Enables new objects to take on the properties of existing objects.
### When an object instance is created from a class, the class's constructor function is run to create it. This process of creating an object instance from a class is called instantiation — the object instance is instantiated from the class.

## Polymorphism.
### It is the ability to redefine methods for derived classes. or we can say that objects that can behave in different forms are called Polymorphism.
### Classes within classes
### Provides a way to perform a single action in different forms.
### It provides an ability to call the same method on different JavaScript objects.


### Methods Inherited from Object.prototype: Several of the methods used in the past couple of chapters are actually defined on Object.prototype and are therefore inherited by all other objects. Those methods are:

#### hasOwnProperty() -Determines whether an own property with the given name exists
#### propertyIsEnumerable() -Determines whether an own property is enumerable
#### isPrototypeOf() - Determines whether the object is the prototype of another
#### valueOf() - Returns the value representation of the object
#### toString() Returns a string representation of the object.

## These five methods appear on all objects through inheritance. The last two are important when you need to make objects work consistently in JavaScript, and sometimes you might want to define them yourself.

# 4.Call Functions

## The call() method calls a function with a given this value and arguments provided individually.

## Different types of call functions
### Constructor functions
#### define and initialize objects and their features. They are useful because you'll often come across situations in which you don't know how many objects you will be creating; constructors provide the means to create as many objects as you need in an effective way, attaching data and functions to them as required.
#### constructors provide the means to create as many objects as you need in an effective way, attaching data and functions to them as required.
### Object instances
#### objects that contain the data and functionality defined in the class. From our Person class, we can now create some actual people:
### Create () method
#### create object instances without first creating constructors, especially if they are creating only a few instances of an object.

# 5a/What OOP is used for with examples
## A simple way to access functionality
## An example of this: 1000 strings with 1 object encapsulating the same thing


# 5b/How to use OOP / Best Practices
## Write dry code
## Organize your objects and references

# 6.A summary for non-OOP users
## Programming model organized around objects rather than actions
## Focuses on objects that you want to manipulate, their relationships, and the logic required to manipulate them
