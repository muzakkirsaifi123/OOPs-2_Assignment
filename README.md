
* In this Project I have define a class with name as Person and mix it with Ordered Trait to do the comparison.

* First, I have checked --

  If the name parameter of both objects is equal. If yes, then do the comparison according to age.
* Secondly --

    If name is not equal then do the comparison on the basis of name length.

Here is the test case--

Input:

personOne = new Person("Test", 24) and personTwo = new Person("Test", 25)
personOne < personOne


Output: true

Input: 
personOne = new Person("TestAgain", 24) and personTwo = new Person("Test", 25)
personOne < personOne

Output: false
