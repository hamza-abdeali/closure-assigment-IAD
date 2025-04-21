# closure-assigment-IAD
The app is not complete so please do judge as such.

places i have used closuere in
navigate to the following folder and open app.js
-----SRC
      |----->app.js

Line 13 – handleClick(i):
This function forms a closure over squares, xIsnext, setSquares, and setXIsNext to manage game logic and state updates from within the Board component.

Lines 24 to 38 – Inline arrow functions in onSquareClick props:
Each arrow function (e.g., () => handleClick(0)) creates a closure that retains access to the handleClick function and the specific square index (i) passed during render.

Line 4 – onClick={onSquareClick} in Square component:
The onSquareClick prop receives a closure from the Board component, maintaining access to its associated state and event logic even when used in a separate child component.

