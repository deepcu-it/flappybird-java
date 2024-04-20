/**
 * Flappy Bird Game
 * 
 * This project implements the classic Flappy Bird game using Java and Swing.
 * The game features a bird controlled by the player, which needs to navigate
 * through openings between pipes by jumping. The goal is to achieve the highest
 * score possible by passing through as many pipes as possible without colliding
 * with them or hitting the ground.
 * 
 * Approach:
 * - The game is built using Java's Swing library for graphics rendering and event handling.
 * - The game logic includes classes for the bird and pipes, as well as methods for collision detection,
 *   movement, and rendering.
 * - The main game loop is managed by a Swing Timer, updating the game state and rendering the scene
 *   at a consistent frame rate.
 * - Pipes are dynamically generated and moved from right to left to create the illusion of the bird
 *   flying through a scrolling landscape.
 * - Player input is handled through keyboard events, allowing the bird to jump in response to the
 *   spacebar key.
 * - The game keeps track of the player's score based on the number of pipes successfully passed.
 * - When the bird collides with a pipe or the ground, the game ends, displaying the final score
 *   and allowing the player to restart.
 * 
 * How to Play:
 * - Press the spacebar key to make the bird jump.
 * - Navigate the bird through openings between pipes by timing your jumps.
 * - Try to pass through as many pipes as possible to increase your score.
 * - Avoid collisions with pipes or the ground to keep the game going.
 * - If the bird collides, the game ends, and you can restart by pressing spacebar.
 * 
 * Author: Deep Ghosal
 * GitHub: https://github.com/deepcu-it/flappybird-java
 */