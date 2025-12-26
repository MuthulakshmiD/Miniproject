## Dungeon Generator
### AIM:
To design and develop a web-based Dungeon & Dragons dungeon generator using JavaScript that procedurally creates dungeon maps, rooms, doorways, and room descriptions as SVG graphics based on user input, without the use of third-party libraries.

### ALGORITHM:
Start the application by loading the main HTML file in a modern web browser.

Initialize the dungeon configuration parameters such as map size, complexity, number of rooms, and connection density.

Create a multi-dimensional grid array to represent the dungeon layout where each cell denotes a possible map location.

Select a random starting point on the grid to place the initial room.

Generate additional rooms by expanding from existing rooms using random directions while ensuring no overlap occurs.

Validate each new room placement based on grid boundaries and spacing constraints.

Establish doorway connections between adjacent rooms to ensure dungeon connectivity.

Apply probability-based rules to assign room properties such as room type, size, traps, and difficulty level.

Randomly generate items and treasures using predefined rarity and quantity tables.

Generate descriptive text for each room, including room purpose and special features.

Convert the finalized dungeon grid data into SVG elements for visual representation.

Render the SVG dungeon map dynamically in the browser interface.

Execute built-in unit tests to verify dungeon generation logic and rendering accuracy.

Display the final dungeon map and associated room details to the user.

### PROCEDURE
Create the project structure with separate folders for dungeon logic, room generation, items, UI components, and utilities.

Develop the main entry point (index.html) to load the application modules using native JavaScript module imports.

Write JavaScript functions to initialize dungeon parameters based on user input.

Implement a grid-based dungeon generation system using a multi-dimensional array.

Develop room generation logic that places rooms randomly while preventing overlap and invalid placements.

Implement algorithms to connect rooms using doors and corridors to maintain accessibility across the dungeon.

Define probability tables for traps, items, and room conditions to introduce randomness and replayability.

Use utility functions for random number generation and text formatting.

Generate SVG elements programmatically to visually represent rooms, walls, and doorways.

Dynamically inject generated HTML and SVG content into the browser using template literals.

Create a custom unit testing framework to validate core logic without relying on third-party libraries.

Run unit tests automatically during page load to ensure application stability.

Display the generated dungeon map along with room descriptions and item details.

Test the application across modern browsers to ensure compatibility and responsiveness.


### OUTPUT:

![WhatsApp Image 2025-12-26 at 12 22 10](https://github.com/user-attachments/assets/6a1ce530-8219-4c8d-9e54-4ce273849212)

![WhatsApp Image 2025-12-26 at 12 21 31](https://github.com/user-attachments/assets/a720a82c-fba7-47e6-bcf0-f5b0807c9b2c)



The application successfully generates a Dungeon & Dragons dungeon map based on user input. The output includes a procedurally generated dungeon layout with rooms, doorway connections, traps, and items displayed as SVG graphics. The generated dungeon and its details are rendered correctly in the browser, and the system functionality is verified using a custom unit testing framework.

### RESULT
Thus, a procedural Dungeon & Dragons dungeon generator was successfully implemented using JavaScript, demonstrating procedural content generation, modular design, and dynamic SVG rendering without relying on third-party libraries.
