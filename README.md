# OOPs-
Personal notes and code for Java OOPs

**Question**
// difference between abstraction and encapsulation
Key Differences:
**Encapsulation**
**Focus**	Hiding internal data (control access)	
**How**	Use of access modifiers (private, public)	
**Goal**	Protect the object	
**Exposure**	Exposes necessary methods to interact with data
**Real-world analogy**	A pill capsule hiding the powder


**Abstraction**
**Focus**	Hiding implementation complexity
**How** Use of abstract classes, interfaces
**Goal**	Simplify usage
**Exposure**	Exposes essential features, hides details
**Real-world analogy**		A car's steering system – you don't see the mechanism


**Question**
How to make attributes of a class read only?
**Answer**
With the use of final keyword


**Question**
What is the use of "this" keyword?
**Answer**
this is a keyword in Java which is used as a reference to the object of the current class, with in an instance method or a constructor. 
Using this you can refer the members of a class such as constructors, variables and methods.
Note − The keyword this is used only within instance methods or constructors


**QUESTION**
What is the use of the "finalize" keyword?
**ANSWER**
It is possible to define a method that will be called just before an object's final destruction by the garbage collector. This method is called finalize( ), and it can be used to ensure that an object terminates cleanly.
For example, you might use finalize( ) to make sure that an open file owned by that object is closed.
To add a finalizer to a class, you simply define the finalize( ) method. The Java runtime calls that method whenever it is about to recycle an object of that class.
Inside the finalize( ) method, you will specify those actions that must be performed before an object is destroyed.
