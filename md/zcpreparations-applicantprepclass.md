## Applicant Prep Class:<br>Preparing for<br>Hackerrank Assessment
-
## Familiarizing with Javascript
* Comments
* Variables
* Integer types
* Boolean type
* Character types
* String types
* Array objects
* Functions objects



-
## Comments
* The purpose of a comment is to
	* describe intention of code block
	* experiment with code implementation





-
## Single line Comments
* Stub out line-by-line intentions
* Remove the functionality of the current line





-
-
### Stubbing out intentions
* A _stub_ is a way to describe the _intention_ of a _block of code_.
* Stubs should always be written _before_ code.
  * Ensures we do not deviate from our original intentions
  * Gives us a step by step guide to follow

```Javascript
// ask user to input their age
// if user age is over 18,
// display `welcome` to the browser's console
```



-
-
### Fulfilling Stubs
* Notice that the result of a fulfilling the stub is a well-commented block of code.
* Notice that comments follow each line, rather than precede them

```Javascript
age = input("What is your age?"); // ask user to input their age
if(age > 18) { // if user age is over 18
  console.log("Welcome!"); // display welcome to the browser's console
}
```



-
-
### Remove Functionality of Current Line
* By commenting out the _if body_, we remove its behavior from the application.

```Javascript
age = input("What is your age?"); // ask user to input their age
if(age > 18) { // if user age is over 18
  // console.log("Welcome!"); // display welcome to the browser's console
}
```

















-
## Multi-line Comments
* Describe a block of code
* Remove the functionality of a block of code





-
-
### Describe a block of code
* A _block of code_ is a set of instructions.

```Javascript
/*
The purpose of the application is to verify a user's age
*/
age = input("What is your age?"); // ask user to input their age
if(age > 18) { // if user age is over 18
  // console.log("Welcome!"); // display welcome to the browser's console
}
```



-
-
### Remove functionality of<br> block of code

```Javascript
age = input("What is your age?"); // ask user to input their age
/*if(age > 18) { // if user age is over 18
  console.log("Welcome!"); // display welcome to the browser's console
}*/
```















-
## Variables
* Used to represent an unknown value
* Used to hold the value of a repeating entity




-
-
## Syntax
* Variable names cannot begin with numbers.
* Variable names cannot contain special characters other than underscore `_`
  * Spaces are considered special characters.




-
-
## Representing unknowns
* Programmers are given freedom to name variables, nearly, whatever they want
* Variable names should describe their intended representation

```Javascript
age = input("What is your age?");
favoriteNumber = input("What is your favorite number?");
```



-
-
## Repeating Entity

```Javascript
x = 5;

```



-
## Integer




-
## Character




-
## String




-
## Arrays
* element removal and shifting; start with first elem, derive pos from index




-
## Loops




-
## Functions





## Googling
