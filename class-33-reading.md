# Reading-Notes

                        ** Class- 33- Redux Additional Topics**
                       
 ### Redux Core Concepts
 
  * Let us assume our application’s state is described by a plain object called initialState which is as follows −
  
  `
   const initialState = {
   isLoading: false,
   items: [],
   hasError: false
};
 `
 
  Every piece of code in your application cannot change this state. To change the state, you need to dispatch an action.
  
  
  * What is an action?
  
      An action is a plain object that describes the intention to cause change with a type property. It must have a type property which tells what type of action is being 
      
      performed. The command for action is as follows −
      
  `
  return {
   type: 'ITEMS_REQUEST', //action type
   isLoading: true //payload information
}
`
  Actions and states are held together by a function called Reducer. An action is dispatched with an intention to cause change. This change is performed by the reducer. Reducer 
  
  is the only way to change states in Redux, making it more predictable, centralised and debuggable.
  
  
 
 
 
[reference](https://www.tutorialspoint.com/redux/redux_quick_guide.htm)
[home](https://eyob1984.github.io/reading-notes/)
