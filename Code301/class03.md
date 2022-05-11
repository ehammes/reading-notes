# Read: 03 - Passing Functions as Props

## Reading

### [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

1. **What does .map() return?** Creates a new array with the results of calling a provided function on every element in the original array.
2. **If I want to loop through an array and display each value in JSX, how do I do that in React?** Using curly braces {}
3. **Each list item needs a unique ____.** Key, a special string attribute needed for list items.
4. **What is the purpose of a key?** Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity. Use a string that uniquely identifies a list item among its siblings (ie `key={x.id}`) or index can be used as well (`key={index}`)

### [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. **What is the spread operator?** Spread Operator is the use of an ellipsis of three dots `(…)` to expand an iterable object into the list of arguments
2. **List 4 things that the spread operator can do**.
    1. Array - spreads into separate arguments
    2. Copying an array
    3. Using Math functions
    4. Adding an item to a list
3. **Give an example of using the spread operator to combine two arrays.**

    ```
    const fruits = ['🍏','🍊','🍌','🍉','🍍']
    const moreFruits = [...fruits];
    console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
    fruits[0] = '🍑'
    console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
    ```

4. **Give an example of using the spread operator to add a new item to an array.**

    ```
    const fewFruit = ['🍏','🍊','🍌']
    const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
    console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
    ```

5. **Give an example of using the spread operator to combine two objects into one.**

    ```
    const objectOne = {hello: "🤪"}
    const objectTwo = {world: "🐻"}
    const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
    console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
    const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
    objectFour.laugh() // 😂😂😂😂😂
    ```

### Videos

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. **In the video, what is the first step that the developer does to pass functions between components?** Create the function where the state is and pass in the object.
2. **In your own words, what does the increment function do?** It is looping through the object and increasing the count for a given name if the name matches
3. **How can you pass a method from a parent component into a child component?** Within the object, call the method (ie `increment={this.increment}`)
4. **How does the child component invoke a method that was passed to it from a parent component?** Call the method and pass this.props

#### **Bookmark and Review**

- [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
- [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

##### Things I want to know more about

Practice using the spread operator