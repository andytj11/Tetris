Introduction
------------
This project is a classic Tetris game built using TypeScript, HTML, and CSS. Tetris is a tile-matching puzzle game where players aim to fit falling blocks into complete horizontal rows to clear them. This version includes essential game mechanics and customizable controls.


Usage
-----
- Setup (Ensure Node.js is installed).

  1. Install dependencies:
     - npm install
  2. Run tests:
     - npm test
  3. Serve the app locally:
     - npm run dev

After running, ctrl-click the URL that appears in the console to open the
game in your browser.


Features and Modifiable Files
-----------------------------
The core game logic is located in src/main.ts. The following files are available for modification:

- src/main.ts:
    Entry point for the game. Contains the main game logic.
- src/style.css:
    Stylesheet for the game window and elements.
- index.html:
    HTML scaffold. Feel free to add elements, but avoid modifying existing      id fields.
- test/*.test.ts:
    Test files. Additional tests can be added here using Vitest.


Tetris Blocks
-------------
The Tetris game features the following blocks:

I: Vertical line block
O: Square block
T: T-shaped block
S: Zigzag block
Z: Reverse zigzag block
J: L-shaped block facing left
L: L-shaped block facing right

Each block is represented by coordinates indicating its initial shape on the grid.


Controls
--------
P: Pause
R: Restart
A: Move Left
D: Move Right
T: Rotate Block


License
-------
This project is licensed under the Apache License 2.0. 
See the LICENSE file for details.

© Andy Tjandra, 2023. All rights reserved.
