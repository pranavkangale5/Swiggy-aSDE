# Magic Arena

A simple game where two players fight in an arena using dice rolls to determine attack and defense outcomes.

## Tech Stack

**Client:** NodeJS , Typescipt , Javascript

**Package:** readline : Node.js's module for reading user input.

## Installation

1. Install all related dependencies with npm

```bash
    cd <project directory>
    npm install
```

2. Run the Program and follow the CLI to interact with Arena

```bash
    ts-node index.ts
```

If Typescript `ts-node` is not installed , install Typescript globally using

```bash
    npm install -g ts-node typescript '@types/node
```

## Running Tests

To run tests, run the following command

```bash
  npx jest
```

## Files

    - `Player.ts`           : Defines the Player class
    - `Arena.ts`            : Defines the Arena class
    - `index.ts`            : Defines the main function and runs the program
    - `arena.test.ts`       : Contains the tests for the Arena
    - `util.common.test.ts` : Contains the tests for logic of the game

## Author

- [@pranavkangale5](https://www.github.com/pranavkngale5)
