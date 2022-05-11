# Passing Functions as Props

## [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

1. *What does .map() return?* A new array.
2. *If I want to loop through an array and display each value in JSX, how do I do that in React?* Loop through the array using the .map( ) method and display the returned array by using curly brackets.
3. *Each list item needs a unique ____.* Key
4. *What is the purpose of a key?* Keys are given to elements inside an array. Their purpose is to help React know which items have been changed, added, or removed.

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. *What is the spread operator?* An ellipsis of three dots `...` used to expand an iterable  object (usually arrays, but can be used on any iterable) into the list of arguments. It will “spread” the array into separate arguments.
2. *List 4 things that the spread operator can do.*

* Use an array as arguments
* Combining objects
* Using Math functions
* Concatenating or combining arrays

3. *Give an example of using the spread operator to combine two arrays.*

```js
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
```

4. *Give an example of using the spread operator to add a new item to an array.*

```js
const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
```

5. *Give an example of using the spread operator to combine two objects into one.*

```js
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

## [How to Pass Functions Between Components](https://youtu.be/c05OL7XbwXU)

1. *In the video, what is the first step that the developer does to pass functions between components?*

Creates the function wherever the state is that will be changed.

2. *In your own words, what does the `increment` function do?*

Updates a count based on the name that is passed in.

3. *How can you pass a method from a parent component into a child component?*

By passing the method as you would a prop to the object `{this.methodName}`

4. *How does the child component invoke a method that was passed to it from a parent component?*

By using `{this.props.methodName}`

## Things I want to know more about

Understanding the use of the spread operator. The first example under “Examples of using `…`” was confusing to me.

Understanding how the function passed between components works. I had to watch the video a few times and even then I am still shaky on how it all worked.