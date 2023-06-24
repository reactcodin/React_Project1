
# React js



## Functional Component

Functional component is just a simple javascript function; it accepts the data in the form of props and returns the react element. 



## Example



```bash
  import React from 'react'

export default function Function() {
  return (
    <div>
      <h1>Hello welcome</h1>
    </div>
  )
}

```


## Class Component

Class component is called statefull component. React lifecycle methods can be used inside class components. 
## 
## Example



```bash
import React,{Component} from "react";

class ClassComp extends Component{
    render(){
        return(
            <>
            <h1>welcome to class component</h1>
            </>
        )
    }
}
export default ClassComp;


```



