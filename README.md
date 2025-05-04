# Ball Dropper

A simple web-based physics game where you aim and shoot balls to destroy numbered polygons before they reach the top. Built with HTML, JavaScript, and the Matter.js physics engine.

## Features

*   **Physics-Based Gameplay:** Utilizes the Matter.js engine for realistic ball bouncing and collisions.
*   **Aim and Shoot:** Click, drag, and release to aim and launch a stream of balls.
*   **Numbered Polygons:** Destroy polygons by hitting them; each hit decrements their number.
*   **Diamond Polygons:** Hit special black diamond polygons to gain an extra ball for the next round.
*   **Increasing Difficulty:** Polygon values increase as rounds progress, requiring more hits.
*   **Turn-Based Progression:** Polygons move up one row after all balls have settled each turn.
*   **Game Over Condition:** The game ends if any polygon reaches the dotted "cage line" near the top.
*   **Scoring:** Score increases with each hit on a numbered polygon.
*   **Speed-Up Toggle:** Double-click RIGHT MOUSE button while balls are active to speed up the simulation (4x speed).
*   **Speed Jolt: ** Double clicking the LEFT MOUSE button will jolt the balls 
*   **Simple Controls:** Easy mouse-based aiming and shooting, plus right-click restart.
*   **Browser-Based:** Runs entirely in the web browser, no installation needed beyond a modern browser.

## How to Play

1.  **Aim:** Click and hold the mouse button near the top-center of the game area. Drag downwards and left/right to aim. A dotted line shows your trajectory.
2.  **Shoot:** Release the mouse button to launch the balls. The number of balls launched increases as you collect diamonds.
3.  **Destroy Polygons:** Balls will bounce off walls and polygons. Each hit on a *numbered* polygon decreases its number by one and increases your score. Polygons are destroyed when their number reaches zero.
4.  **Collect Diamonds:** Hitting a *black diamond* polygon instantly destroys it and adds one ball to your available count for the *next* round.
5.  **End of Turn:** A turn ends when all launched balls have returned to the top area and settled.
6.  **Progression:** After each turn:
    *   All remaining polygons move one row higher.
    *   A new row of polygons appears at the bottom.
    *   The numbers on the new polygons generally increase as the rounds go up.
7.  **Game Over:** If any polygon touches or crosses the dotted "cage line" near the top of the screen, the game is over.
8.  **Speed Up:** While balls are bouncing around, you can **RIGHT-MOUSE double-click** anywhere in the game area to toggle between normal speed and 4x speed.
9.  **Restart:** **Right-click** anywhere in the game area at any time to immediately restart the game from the beginning.

## How to Run

This game is a single HTML file and requires no complex setup.

1.  **Download:** Clone this repository or download the `index.html` file (or whatever the main HTML file is named).
2.  **Open:** Open the downloaded `index.html` file directly in your web browser (e.g., Chrome, Firefox, Safari, Edge).
3.  **Play!**

**Note:** An internet connection is required the first time you load the game (or after clearing browser cache) as it fetches the Matter.js library from a CDN.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **CSS3:** Basic styling for the game container, banner, and game over screen.
*   **JavaScript (ES6+):** Core game logic, physics integration, rendering, and user interaction.
*   **[Matter.js](https://brm.io/matter-js/):** A 2D rigid body physics engine for the web. Handles collisions, gravity, restitution (bouncing), etc.

## License

This project is provided as-is. Feel free to use, modify, and learn from the code.
