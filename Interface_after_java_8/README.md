Interfaces got new features after JAVA 8
1. Static methods
2. Default methods:- A concrete method which can be overridden. Earlier interfaces used to
                     provide signatures. Now interface provide behaviour also.

Functional Interfaces:-
1. Single abstract method
2. static and default methods are allowed.
3. @FunctionalInterface annotation is used
4. The API provides over 40 functional interfaces.
   java.util.function package
- Examples	
		=> Scalable
		=> Runnable,Comparable,Comparator, Iterable
    
Pure Functional Interfaces

	- An FI intended to be implemented by stateless classes
	- Example
		=> Scalable: not pure
		=> Runnable: not pure
		=> Comparable : not pure
		=> Comparator: pure
		
	- Pure FIs respect the Functional Programming paradigm
	- They play an important role in conjunction with streams


  
