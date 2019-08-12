# LIGHTS OUT GAME

A game where the objective is to clear the game board of all the colored lights.

## Installation

NPM START
YARN START

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
  constructor(props) {
    super(props);
//set inital state
    this.state = {
      hasWon: false,
      board: this.createBoard()
    };
  }
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

##Examples

![Example of play](2019-08-12 16.02.58.gif)

## License
