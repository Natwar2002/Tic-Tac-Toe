**Tic Tac Toe**

A simple Tic Tac Toe game implemented using HTML, CSS, and JavaScript. The game allows two players to play 
alternately, with the loser of the last game getting the first turn in the next game.

**Understanding Event Handling Concepts**

*Event Bubbling* : Event bubbling is a concept in which, if we trigger an event on any child, then that event is also
tracked by ancestors of the corresponding child. 
For example:
        "In the game, `gameBoard.addEventListener('click', handleCellClick)` sets an event listener on the `game-board`. If you click on 
        any `cell` the event is also tracked by the `game-board`."