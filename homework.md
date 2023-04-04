What does the word 'polymorphism' mean?
it means many forms


What does it mean when we apply polymorphism to OO design? Give a simple Java example.
it means we can perform an action in different ways depending on where it is used
eg fly method that returns a string but different string depending on where it's called.



What can we use to implement polymorphism in Java?
Can be implemented using interfaces

How many 'forms' can an object take when using polymorphism?
this depends on the number of classes it's called in

Give an example of when you could use polymorphism.
If you were modeling an arcade and each machine had a takeMoney function but all had a different price.

What do we mean by 'composition' in reference to object-oriented programming?
Composition refers to the objects that the object has a relationship.

When would you use composition? Provide a simple example in Java.
You would use this if you were making a parent class that was an abstract framework for children classes.
eg bird parent class for children of specific species

Give a difference between composition and aggregation?
Composition means that the object is made from a parent objects, where aggregation has a relationship between objects

What is/are the advantage(s) of using composition/aggregation?
advantages of composition if parent object is deleted child is deleted and it's also a very strong relationship.
advantages of aggregation objects exist separately and don't need to be as tightly bound

When using composition, when an object is destroyed, what happens to all the objects it is composed of?
they're also deleted

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
they're uncoupled