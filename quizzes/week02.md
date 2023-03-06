# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let
const
var
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a block of code that you can call upon to perform a task. It should be used to do something very efficiently and to be reused if possible. It can be fed arguments into its parameters that can be used within itself and can return a value.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The single responsibility principle
the Open closed principle
Liskov substitution principle
Interface segregation principle
and the dependency Inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple with be at the 2 index of the array fruit. This is because arrays begin at the index [0]
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them.name)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
One javascript conditional statement is the if else statement.
if(condition){
  do this code
} else {
  do this code
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
 the for loop above is missing its incrementor so it would need `i++` so that way it will continue to cycle through all of the arrays objects.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
It stand for the "document object model" The file first accessed to render the DOM is the HTML(hypertext markup language) file.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
1. null
2. undefined
3. boolean
4. number
5. bigInt
6. string 
7. symbol
8. object
9. function
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
 an argument is the data that is being sent to the function or method. While the parameter is the data that is being collected from the argument to be used within the function or method.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value has a fixed amount of memory. It will only take up a predefined amount of bits in the system. a reference value can change in size. It is not predefined so the system does't store the value. It only stores a reference of where to find the value or it points to it.
```