# Funsy, Functional System Modelling Diagram

Visual design diagram for purely functional programming languages


## Motivation

* Making a practical design diagram for software in purely functional
  programming languages


## Features

("system" refers to the software you design)

* Appropriate for software in purely functional programming languages
* Separation of systems and the world which they affects
* Separation of systems' procedure and state
* Friendly with _DFD_ (_Data Flow Diagram_)

* Dubious ones
  * Easy to discriminate thread-safe functions from the others.
  * Easy to pack multiple functions into one function, or bunch nearly
    concerned functions into modules with strong cohesion.


## Usage

1. Break down the system which you design with _DFD_ to make each processes in
  it small enough to apply **Funsy**.
2. Design each processes by applying **Funsy** to them.
3. Design details of the functions in them.
4. Design the types of data transfered among each functions.
  (e.g. using _UML_)
5. Implement them in purely functional programming languages.
  (I recommend you Haskell)


## References

* Questions about design methods for software in functional programming language
  * [Is there a visual modeling language or style for the functional programming paradigm?](http://stackoverflow.com/questions/1364237/is-there-a-visual-modeling-language-or-style-for-the-functional-programming-para)
  * [How do programmers model system design when using functional programming for software implementation?](http://www.quora.com/How-do-programmers-model-system-design-when-using-functional-programming-for-software-implementation)
  * [Can UML be used to model a Functional program?](http://stackoverflow.com/questions/2457903/can-uml-be-used-to-model-a-functional-program)
  * [What do I use for a variant in a UML class diagram?](http://programmers.stackexchange.com/questions/263130/what-do-i-use-for-a-variant-in-a-uml-class-diagram) 
* _Universal Systems Model_
  * [Universal systems model - Google Slides](https://docs.google.com/presentation/d/131zyaZVb4ZW92XSlC24vFPFFh0j1jyI2upl9fHO04Lk/edit#slide=id.p18)
  * [Technology - 3.03 Universal Systems Model.pdf](http://www.wsfcs.k12.nc.us/cms/lib/NC01001395/Centricity/Domain/1555/3.03_Universal_Systems_Model.pdf)
* _Flow-based Programming_
  * [Flow-based programming - Wikipedia, the free encyclopedia](http://en.wikipedia.org/wiki/Flow-based_programming)
  * [Flow-Based Programming: General Framework for Interactive Applications](http://www.jpaulmorrison.com/fbp/scrmgr.htm)
