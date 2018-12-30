# kotlin-beginner (Functional Programing:)

Functional Programing is style of structuring your program where the focus is to transforming data with expression which should not have side affect.
Kotlin is perfect blend of Object-Orianted and functional programing paradigms. It brings both worlds closer together

FP is a style of building the structure and elements of programs—that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
 -  Each input has just one output
 -  FP, by its nature , is thread safe and immutability has a great role in making it thread safe.
 - A function that uses or return other function is Higher Order Function
 - First class Function allow to use Function as variable, Parameters, returns, generalization types and so on.
------------
Pure function:
------
  - Don’t have side effect, not memory, nor IO
 Recursive Function:
  - Function that invoke themselves, with some sort of condition to stop the execution
  - They maintains a stack but can be optimized with trailres modifier 
 Side Effect
    On computer programing, when a function modifies any object/data outside its own code , the is called side affect

- In kaitlin when you are declaring property as function, you should mention the datatypes of parameters/agruments inside braces , followed by an arrow and then the return type of function.

## Developers: Getting Started


```sh
# Install Homebrew (see https://brew.sh).
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# Install Java 8.
brew tap caskroom/versions
brew cask install java8

# Checkout the monorepo:
git clone git@github.com:springernature/oasis.git
```
### Running the Applications

- Go inside `kotlin-beginner`
- Open the project in IntelliJ IDEA
  1. Tell it to overwrite `.idea`, then revert all changes IntelliJ made to that directory
  2. You can run the test cases through IntelliJ or
   run ```gradle build``` from terminal or commandprompt 

