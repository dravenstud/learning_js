`package.json`
```json
{  
  "dependencies": {  
    "react": "^18.3.1",  
    "react-dom": "^18.3.1"  
  }  
}
```

```js
import React from "react"
import ReactDOM from "react-dom/client"
const navbar = (
    <nav>
        <h1>Bob's Bistro</h1>
        <ul>
            <li>Menu</li>
            <li>About</li>
            <li>Contact</li>
        </ul>
    </nav>
)
const root = ReactDOM.createRoot(document.getElementById("root"))
root.render(navbar)
//React 17 : 
// ReactDOM.render(navbar, document.getElementById("root"))
//react 18 :
// ReactDOM.createRoot(document.getElementById("root")).render(navbar)
```