# LIGHTS OUT GAME

A game where the objective is to clear the game board of all the colored lights.

## Installation

NPM INSTALL
NPM START

## Usage

```javascript
import React, {Component} from "react";
import Cell from "./Cell";
import './Board.css';

export default class Board extends Component {
static defaultProps = {
  nrows: 5,
  ncols: 5,
  chanceLightStartsOn: 0.25
};
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Rules

Clear all of the colored lights from the game board. Once all lights are cleared, the game is complete!

## Examples

![2019-08-12 16 02 58 (1)](https://user-images.githubusercontent.com/43822080/62937007-42361f80-bd99-11e9-9230-e95ae83e2c9a.gif)
