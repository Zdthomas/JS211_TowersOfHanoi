How to program Towers of Hanoi plan.


Start with the Node.js.

-movePiece

First is to make so the pieces are movable.
    The code is probably a getElementById to pick up an item and have a removeChild to delete it from a row.

    Then the next part should probably be an appendChild to move it to the next row.

    printStack() seems to help with function in terms of putting the block on the screen.

need eventListeners (click, (e) => onmouseup)-to pick up, to stop double click feature.

also need to stop the ability to pick up multiple at the same time

and need to make sure to only move it onto rows and nowhere else on the page.

Find out how to manage the stack code to make sure it's proper - need for checkwin and legal move
Need to make it recognize row a and row c are victory conditions. 

-isLegal

Next should be to check to see if the move is legal and then to prevent illegal moves from happening.
    I think a normal === function should be able to accomplish this, smaller === bigger return false, etc

    I think using function similar Rock Paper Scissors will work.

-checkWin

    after a stone is set, then check for win. If no win - continue. TicTacToe may have code to help with this.


-towerOfHanoi

    combine all this into the function... somehow.


Move all this to the other js file after these pass the tests.

Complete some of the stone functions in the js file 
    get rid of the stone = null



Go into CSS to adjust size of stones to make it easier for me.

The adjust the HTML as needed.

add reset button.
-reset after win as well.
