# React Adinkra
<p>This project was made to allow easy use of the West African Adinkra symbols in a react project</p>

<p>Documentation can be found here</p>

<p>The vanilla package can be found here</p>

## How to use it
<p>To use the Adinkra in a website must include the CSS CDN link in the head of your index.html</p>

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/JacobTheEvans/adinkra/b79018a0/src/adinkra.css">
```

Then install the package using npm

`npm install react-adinkra`


<p>Then import the Adinkra component and use it your project</p>

```javascript
import React from "react";
import { Adinkra } from "react-adinkra";

class App extends React.Component {
  render() {
    return (
      <Adinkra name="asase-ye-duru"/>
    )
  }
}

export default App;
```

<p>If you would like to style the Symbol you can use className or the style attributes.</p>

```javascript
import React from "react";
import { Adinkra } from "react-adinkra";
import "./App.css";

class App extends React.Component {
  render() {
    return (
      <Adinkra className="large-icon" style={{color: "red"}} name="asase-ye-duru"/>
    )
  }
}

export default App;
```

## What is Adinkra?

<p>Adinkra are visual symbols that represent concepts or aphorisms. Adinkra are used extensively in fabrics and pottery among the Akans of Ghana and Cote d'Ivoire. Currently they are used on walls, architectural features, cloth/clothing and many other places.</p>
