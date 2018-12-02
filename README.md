<p align="center">
  <img src="https://user-images.githubusercontent.com/3059371/49334754-3c9dfe00-f5ab-11e8-8885-0192552d12a1.gif" alt="example" height="150"/>
</p>
<h3 align="center">
  💬 React Native Typing Animation
</h3>
<p align="center">
  A typing animation for your React Native chat app<br/>
  based on <a href="https://uxdesign.cc/how-you-can-use-simple-trigonometry-to-create-better-loaders-32a573577eb4" target="_blank">simple trigonometry</a> to create better loaders.
</p>
<p align="center">
  <a href="https://www.npmjs.com/package/react-native-typing-animation">
    <img alt="npm version" src="https://badge.fury.io/js/react-native-typing-animation.svg"/>
  </a>
  <a title='License' href="https://github.com/watadarkstar/react-native-typing-animation/blob/master/LICENSE" height="18">
    <img src='https://img.shields.io/badge/license-MIT-blue.svg' />
  </a>
</p>

## Installation

* Using [npm](https://www.npmjs.com/#getting-started): `npm install react-native-typing-animation --save`
* Using [Yarn](https://yarnpkg.com/): `yarn add react-native-typing-animation`

## Example

```jsx
import React from "react";
import { TypingAnimation } from 'react-native-typing-animation'

class Example extends React.Component {
  render() {
    return (
      <TypingAnimation />
    );
  }
}
```

## Advanced Example

```jsx
import React from "react";
import { TypingAnimation } from 'react-native-typing-animation'

class Example extends React.Component {
  render() {
    return (
      <TypingAnimation 
        dotColor="black"
        dotMargin={3}
        dotAmplitude={3}
        dotRadius={2.5}
        dotX={12}
        dotY={6}
      />
    );
  }
}
```

## Props

* **`style`** _(Object)_ - Container styles; default is `{}`
* **`dotColor`** _(String)_ - Dot color; default is `#000` (black)
* **`dotStyles`** _(Object)_ - Dot styles; default is `{}`
* **`dotRadius`** _(Integer)_ - Dot radius; default is `2.5`
* **`dotMargin`** _(Integer)_ - Dot margin, the space between dots; default is `3`
* **`dotAmplitude`** _(Integer)_ - Dot amplitude; default is `3`
* **`dotY`** _(Integer)_ - Dot y, the starting y coordinate; default is `6`
* **`dotX`** _(Integer)_ - Dot x, the x coordinate of the center dot; default is `12`

## License

* [MIT](LICENSE)

## Author

Feel free to ask me questions on Twitter [@icookandcode](https://www.twitter.com/icookandcode)!

## Credits

Work is based on the amazing article ["How you can use simple Trigonometry to create better loaders"](https://uxdesign.cc/how-you-can-use-simple-trigonometry-to-create-better-loaders-32a573577eb4) by Nash Vail

## Contributors

Submit a PR to contribute :)

## Roadmap

* Allow animation speed to be configurable (PRs welcome)
* Unit tests

## Release

We use `release-it` to release do the following:

```
yarn run release
```

## Changelog

TODO
