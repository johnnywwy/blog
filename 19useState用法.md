```javascript
import React, {useState} from 'react'

function App() {
  const [n, setN] = useState(0)
  const onclick = () => {
    setN(i => i + 1)
  }


  return (
    <div>
      <h1>n: {n}</h1>
      <button onClick={onclick}>点击</button>
    </div>
  )
}


export default App
```