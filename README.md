[toc]
# Conway's Game Of Life 
Javascript implementation.

## Why?
Why not?

I wanted a good ts/js front-end implementation to use for another project.

## Use
Compile all Typescript files with `tsc <filename>`, or with WebStorm.

## Conway's Game Of Life
The Game of Life, also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves. It is Turing complete and can simulate a universal constructor or any other Turing machine. 

### Rules
Clarification: A new generation will be generated when there are 0 cells alive in the end of a tick.
Each new generation will spawn with 6 to 13 cells in the starting 8x8 grid.
1. Any live cell with two or three live neighbours survives.
2. Any dead cell with three live neighbours becomes a live cell.
3. All other live cells die in the next generation. Similarly, all other dead cells stay dead.
4. **extra rule: ** two new cells will randomly spawn in the starting 8x8 grid, every 15 to 30 ticks.
5. **extra rule: ** every user interaction (any event by the keyboard or mouse) will randomly kill, or spawn a new cell.

[Source](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
