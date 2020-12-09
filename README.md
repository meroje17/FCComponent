# FPComponent
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Star](https://img.shields.io/badge/star-0-blueviolet)

<div>
  <img src="assets/1.gif" height="180" />
  <img src="assets/2.gif" height="180" />
  <img src="assets/3.gif" height="180" />
</div>

- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Color guide](#color)
- [Exemple](#exemple)
- [Contribute](#contribute)
- [License](#license)

## Installation 

```
npm i fc-component
```

## Usage

```jsx
import React from 'react';
import FlipCard from 'fc-component';

function App() {
  return <div>
    <FlipCard />
  </div>
}
```

## Documentation

| Property | Type | Description | Options |
| :---: | --- | --- | --- |
| colorFront | `String` | Background color for front card | ref. Color guide |
| colorBack | `String` | Background color for back card | ref. Color guide |
| textColorFront | `String` | Text color for front card | ref. Color guide |
| textColorBack | `String` | Text color for back card | ref. Color guide |
| textFront | `String` | Text will display on front card | Any string |
| textBack | `String` | Text will display on back card | Any String |
| height | `Number` | Height of component | [1...∞] |
| width | `Number` | Width of component | [1...∞] |
| innerPadding | `Number` | Padding of component | [1...∞] |
| fontSize | `Number` | Size of font, attribute for textFront and textBack | [1...∞] |
| rotationAxis | `String` | The axis of rotation on which the card will rotate.  | `"x"` or `"y"` |

## Color

## Exemple 

<img src="assets/exemple.gif" width="250" />

```jsx
import FlipCard from "fc-component";

function App() {
  return (
    <div className="App">
      <FlipCard
        height={400}
        width={300}
        rotationAxis="x"
        colorFront="dark-black"
        textColorFront="light-orange"
        textColorBack="purple"
        textFront="Voici un exemple de Custom Flip Card"
        textBack="ENJOY THIS !"
        innerPadding={20}
        fontSize={27}
      />
    </div>
  );
}

export default App;
```
<details><summary>CLICK HERE - For another exemples</summary>
<p>

### Exemple 2

<img src="assets/exemple2.gif" width="250" />

```jsx
import FlipCard from "fc-component";

function App() {
  return (
    <div className="App">
      <FlipCard
        height={400}
        width={300}
        rotationAxis="x"
        colorFront="light-blue"
        textColorFront="dark-black"
        textColorBack="purple"
        textFront="Bienvenue sur mon REPO !"
        textBack="ENJOY THIS !"
        innerPadding={30}
        fontSize={32}
      />
    </div>
  );
}

export default App;
```

### Exemple 3

<img src="assets/exemple3.gif" width="250" />

```jsx
import FlipCard from "fc-component";

function App() {
  return (
    <div className="App">
      <FlipCard
        height={400}
        width={300}
        rotationAxis="y"
        colorFront="light-green"
        colorBack="dark-green"
        textColorFront="dark-black"
        textColorBack="dark-black"
        textFront="You love IT ?"
        textBack="Star my repo to tell me ❤️"
        innerPadding={30}
        fontSize={40}
      />
    </div>
  );
}

export default App;
```

</p>
</details>

## Contribute

Show your ❤️ and support by giving a ⭐. Any suggestions are welcome!

## License

Licensed under MIT
