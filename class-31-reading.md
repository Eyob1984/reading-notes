
# Reading-Notes

                        ** Class- 31- Combined Reducers**
                       
 ### Combined Reducers:-
 
  * As your app grows more complex, you'll want to split your reducing function into separate functions, each managing independent parts of the state.
  
  * The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.
  
  * Any reducer passed to combineReducers must satisfy these rules:

        * For any action that is not recognized, it must return the state given to it as the first argument.

        * It must never return undefined. It is too easy to do this by mistake via an early return statement, so combineReducers throws if you do that instead of letting the error           manifest itself somewhere else.

        * If the state given to it is undefined, it must return the initial state for this specific reducer. According to the previous rule, the initial state must not be                   undefined either. It is handy to specify it with ES6 optional arguments syntax, but you can also explicitly check the first argument for being undefined.
 
  
  
[reference](https://redux.js.org/api/combinereducers/)
[home](https://eyob1984.github.io/reading-notes/)
