# Reading-Notes

                        ** Class- 32- Redux Async Action**
                       
 ### Async Actions
 
  * When you call an asynchronous API, there are two crucial moments in time: the moment you start the call, and the moment when you receive an answer (or a timeout).
 
 
 
 ### What is Redux thunk?
 
  * Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the body of the function once the asynchronous operations have completed.
  
[reference](https://redux.js.org/advanced/async-actions/)
[home](https://eyob1984.github.io/reading-notes/)
