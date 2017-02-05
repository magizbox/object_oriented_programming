# SOLID Principles

In computer programming, SOLID (single responsibility, open-closed, Liskov substitution, interface segregation and dependency inversion) is a mnemonic acronym introduced by Michael Feathers for the "first five principles" named by Robert C. Martin in the early 2000s that stands for five basic principles of object-oriented programming and design. The intention is that these principles, when applied together, will make it more likely that a programmer will create a system that is easy to maintain and extend over time. The principles of SOLID are guidelines that can be applied while working on software to remove code smells by providing a framework through which the programmer may refactor the software's source code until it is both legible and extensible. It is part of an overall strategy of agile and Adaptive Software Development.

"Dependency Management is an issue that most of us have faced. Whenever we bring up on our screens a nasty batch of tangled legacy code, we are experiencing the results of poor dependency management. Poor dependency management leads to code that is hard to change, fragile, and non-reusable."

Uncle Bob talk about several different design smells in the PPP book, all relating to dependency management. On the other hand, when dependencies are well managed, the code remains flexible, robust, and reusable. So dependency management, and therefore these principles, are at the foundation of the *-ilities* that software developers desire.

##	SRP - Single Responsibility 

> A class should have one, and only one, reason to change.

A class should have only a single responsibility (i.e. only one potential change in the software's specification should be able to affect the specification of the class)

[Original Paper](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)


## OCP - Open/Closed 

> You should be able to extend a classes behavior, without modifying it.

Software entities … should be open for extension, but closed for modification.”

[Original Paper](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)

## LSP - Liskov Substitution 

>  Derived classes must be substitutable for their base classes.

Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program. See also design by contract.

[Original Paper](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)

## ISP - Interface Segregation 

>  Make fine grained interfaces that are client specific.

Many client-specific interfaces are better than one general-purpose interface.

[Original Paper](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)

## DIP - Dependency Inversion 

> Depend on abstractions, not on concretions.

One should “depend upon abstractions, **not** concretions.”

[Original Paper](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)

# References

* [The Principles of OOD](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
