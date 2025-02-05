# Java-Assignment-005 - Switch it Up

## Part 1: - Tracing the Code
As a new Java developer, you will be required to familiarize yourself with existing code before beginning to develop. That's what this section is about, developing your code tracing skills and familiarizing yourself with parts you may be able to use.
* Scan through all the existing code and note what you have to work with.
    * Method names
    * Variables
* Using Java terminology, break down every piece of the method **convertF2K**.
    * What is the access modifier? - _public_
    * Is it a class or object method, how do you know? - _Class method, it's static_
    * What is its return type? - _double_
    * What parameters does it require, and what are the parameter(s) datatype(s)? - _Parameter fahrenheit with type double_
    * Describe for me how the body of the method executes (i.e. its flow of execution). - _Takes the fahrenheit input, converts it to celsius with a method call, then converts _that_ into kelvin using another method call_
* Using Java terminology, break down method **getUnitChoice**.
    * What is the access modifier? - _public_
    * Is it a class or object method, how do you know? - _Class method, it's static_
    * What is its return type? - _String_
    * What parameters does it require, and what are the parameter(s) datatype(s)? - _No parameters_
    * Describe for me how the body of the method executes (i.e. its flow of execution). - _Prints out command instructions to the user and returns the next input_
    * How do the format specifiers differ than what you've seen before and what do they do? - _We haven't used the string `%s` format specifier with additional arguments before (eg. `%40s`)._
      * _The `%40s` specifier says that if the string is less than 40 characters, then it will be padded with spaces to the left to fit that length._
      * _The `%-4s`_ specifier says that if the string is less than 4 characters, then it will be padded with spaces to the RIGHT.

## Part 2: - Implement Missing Method: convertK2F
This Part is aimed at teaching you to use methods and code you have to add new functionality to existing code. In this case you will add the missing conversion method, but you don't need to know math :-)
* Hint: You can use existing methods!

## Part 3: - Switch it Up
Part 3 is all about learning how to use the **switch** conditional statement, or the **enhanced switch** statement. You've learned about **if/else** now you will learn about **switch**.
* Using the provided method and class variables, write a program in the **while** loop of the **main** method that:
    * Requests a temperature Unit to convert from
    * Requests a temperature Unit to convert to
    * Quits the program if Q is entered for either choice
    * Requests the double temperature value to convert
    * Uses a **switch** or **enhanced switch** conditional to call the proper conversion method.
    * Prints out the result as indicated below:

          Result 40.000000°C is 104.000000°F

## Part 4: Pull Request
Part 4, as usual, is repetition of duties you will be doing in industry.
* Make sure to use the Git tab at the bottom of IntelliJ to create a Fall_2022 feature branch
* Commit and Push your running code back to your GitHub account
* Issue a Pull request back to my Java-Assignment-005 repo
* Cut and Paste the Pull request URL into your Canvas assignment to turn it in.