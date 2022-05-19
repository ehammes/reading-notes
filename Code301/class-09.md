# Read: 09 - Functional Programming

## Reading

### [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

- **What is functional programming?** According to wikipedia, functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
- **What is a pure function and how do we know if something is a pure function?** 1. It returns the same result if given the same arguments 2. Does not cause any side effects
- **What are the benefits of a pure function?** Easier to use unit tests with pure functions.
- **What is immutability?** Its state cannot change after being created, must create a new object with a new value.
- **What is Referential transparency?** When a function has the same result for the same input. `pure functions + immutable data = referential transparency`

#### [Node JS Tutorial for Beginners #6 - Modules and require](https://www.youtube.com/watch?v=xHLd36QoS4k)

- **What is a module?** A javascript file
- **What does the word ‘require’ do?** Require function is used to refer to a module
- **How do we bring another module into the file the we are working in?** Use 'Require' function
- **What do we have to do to make a module available?** Specify what needs to be made available outside of the module using export and specifying the module. Set the require function to the variable based on the export.
