# Interactive-MineSweeper
Interactive MineSweeper is a dynamic and visually engaging redesign of the classic Minesweeper game, developed using JavaFX. The project focuses on creating an interactive, animated, and user-friendly experience, integrating playful visual feedback, intuitive animations, and multiple gameplay modes to enhance user engagement.

Key Features & Interactions
🏁 StartFrame

The entry screen introduces players with a lively interface.

· The mouse cursor is animated as a small man detecting mines. When the left mouse button is clicked, the animation changes to a detection action.<br>
<img width="137" height="143" alt="image" src="https://github.com/user-attachments/assets/801bb7b2-4573-44db-a607-8a886cfaa550" />

· The Start button features a zooming and color-lightening animation when clicked.

· The background includes rotating, zooming, and blurring effects, making the scene visually appealing.<br>
<img width="134" height="144" alt="image" src="https://github.com/user-attachments/assets/421b2a2c-cee7-40e9-b3fe-a73ab2740bc2" />

· Clicking the Start button transitions smoothly to the SelectionFrame.

⚙️ SelectionFrame

Players can choose between four gameplay modes — Easy, Medium, Advanced, and Custom.

· Hovering over a button triggers a shaking animation, indicating interactivity.<br>
<img width="135" height="141" alt="image" src="https://github.com/user-attachments/assets/26cec8aa-3c01-4a03-ba2b-0b94a0b8c6d1" />

· The background uses gradient and color overlay animations.<br>
<img width="136" height="143" alt="image" src="https://github.com/user-attachments/assets/38a6c88f-5cd0-4e91-8e01-4fd91ba35458" />

· Easy Mode: 10×10 square grid

· Medium Mode: 20×20 square grid

· Advanced Mode: 20×20 hexagonal grid

· Selecting a mode (e.g., Medium) opens the GameFrame with corresponding grid settings.

💣 GameFrame

This is the main gameplay interface, featuring a breathing gradient background for visual depth.
At the top are functional elements: logo, mine counter, timer, pause/restart buttons, and mode menu.

Top Area Interactions:

· Hovering over the mine counter displays a tooltip (e.g., “Current unopened squares: 99”), which updates dynamically.

· Clicking Pause triggers different pop-ups depending on the game state, each appearing with a zoom animation.

· Hovering over Reset shows a tooltip: “Click to restart the game.”

· The Mode Menu allows switching between modes, confirmed by an animated pop-up.

Gameplay Area:

· Hovering over a cell triggers a zoom animation, showing cursor position.

· Left-click reveals a cell (blank, number, or mine).

   · If a mine is clicked, a pop-up announces game over, and the restart button icon turns into a crying face.

   · If the player wins, a victory pop-up displays total playtime.

· Right-click or drag the flag icon to mark a cell. The cursor changes into a flag-carrying animation.

· Repeated right-clicks toggle through flag → question mark → blank states.

· After 20 seconds of inactivity, a pop-up reminder appears.

Bottom Area:

· Contains the flag icon, hint button, and remaining hint counter.

· Clicking the hint button decreases the hint count and briefly flashes a flag on a hidden bomb cell.

🧩 CustomizeFrame

Players can customize their own game layout with animated feedback for each action.

· Hovering over text fields or buttons triggers a jitter animation.

· The background features color gradients and overlays for visual continuity.

· Input validation ensures logical settings:

   · If rows exceed 20, a shaking warning animation appears.

   · If an invalid bomb number is entered, a zooming warning pop-up alerts the player.

· Once valid settings are entered (e.g., a 15×20 hexagonal grid with 23 bombs), the custom game starts smoothly.

Design Highlights

· Rich interactive animations enhance player feedback.

· Multi-level difficulty modes, including both square and hexagonal grids.

· Dynamic hints and customizable gameplay encourage replayability.

· Designed for smooth transitions, visual appeal, and intuitive control flow.
