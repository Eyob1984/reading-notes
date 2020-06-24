# Reading-Notes

                        ** Class-26 - Hooks API**

#### What does a component’s lifecycle refer to?

* A component’s lifecycle is broadly classified into four parts: initialization; mounting; updating, and; unmounting. 

#### Why are functional components preferred over class components?

* Functional components are saves code length and they are less complex.

#### What is wrong with the following code?

```import React, {useState, useEffect} from 'react'; 
   
function MyComponent(props) {
  const [count, setCount] = useState(0); 
     
  function changeCount(e) {
    setCount(e.target.value); 
  }
     
  let renderedItems = []
     
  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update'); 
    }, [count]); 
       
    renderedItems.push(<div key={i}>Item</div>); 
  }
     
  return (<div>
    	<input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```

* The code use `useEffect` inside a nested function and a for loop. Hooks should only be defined/called at the top level, and never inside loops, conditions or nested functions.

[home](https://eyob1984.github.io/reading-notes/)
