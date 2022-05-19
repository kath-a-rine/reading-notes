# Functional Programming

## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

1. **What is functional programming?** - "Functional pogramming is a style of building structure and elements of computer programs that that treats computation as the evaluation of mathmematical functions and avoids changing-state and mutable data." - [Functional Programming - Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)
2. **What is a pure function and how do we know if something is a pure function?** - Pure functions return the same result if given the same arguments and do not cause any observable side effects.
3. **What are the benefits of a pure function?** - The code is easier to test
4. **What is immutability?** - The inability to change or unchanging over time.
5. **What is Referential transparency?** - "If a function yeilds the same result for the same input."

## [Node JS Tutorial for Beginners #6 - Modules and require()](https://youtu.be/xHLd36QoS4k)

1. **What is a module?** - Code is split into logial modules, each in their own JS file. Each module has a certain functionality in the code to be called on when needed.
2. **What does the word ‘require’ do?** - The require function allows a JS file to access the module passed through the function.
3. **How do we bring another module into the file the we are working in?** - By passing the file path to the module through require. `let counter = require(./count)`
4. **What do we have to do to make a module available?** - Inside the module, indictate what code you want available elsewhere.  `module.exports = counter;`

## Things i'd like to know more about

Pure functions - I was unable to review the code in the medium article so I don't have a handle on how they work without the added context of seeing the code.
