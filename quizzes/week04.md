# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
asynchronous code doesn't stop other code from executing. It can run in the background while the code continues to run or wait to run until it needs to. Try and catch methods are examples of asynchronous code.

synchronous code is a stricter model. It means that the code will run one line after another and until the line is finished then the next cannot begin. It is more sequential.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a piece of code that waits for a change in an element then it performs a block of code in response to that change. It will do this every time that element is changed so that way it creates a more responsive code.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The 'o' stands for "Open closed principle". It means that we can expand on our code without modifying the old code. 
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is is something that takes time to complete. It is stored code that will initiate after something takes more time to complete to be done later. This is so that the code doesnt need to stop to wait for the long process to complete. a higher order function is a function that accepts other functions.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
a promise is a a proxy that exists in one of 3 states. Pending, fulfilled, and rejected. An exmple of this is a try/catch method. The promise is where the method is pending, and it catches if it fails and is in a rejected state. 
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Get, post, and put. The get request is used to pull information from a server. A post request will send new information to a server. and a put request replaces information with updated information.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
API stands for application programming interface. 
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service which handles the business logic is responsible for making calls to APIs.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
encapsulation is the bundling of data to keep it seperate from other data and stores it privately. It keeps the code cleaner and prevents too much memory from being used at the same time. It allows for you to make small changes without necessarily having to change large pieces of code. 
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
ok 200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
It is a catch all response, that says that the server met an unexpected condition. Its what happens when the server cannot find a better error.
```