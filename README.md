# Leap Froggies Puzzle Game

## Description
This Python program implements the classic "Leap Froggies" puzzle game. The objective of the game is to rearrange the frogs on the left and right sides of the pond so that they switch places. Each frog can either move forward one space or leapfrog over another frog from the opposite side to move two spaces. The puzzle is solved when the frogs on the left and right sides have switched positions.

## Rules
1. The left set of frogs can only move right, and the right set of frogs can only move left.
2. Frogs can move forward one space, or move two spaces by jumping over another frog from the opposite side.
3. The puzzle is solved when the two sets of frogs have switched positions.

## Usage
1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Open a terminal or command prompt and navigate to the directory where you cloned the repository.
4. Run the `leap_froggies.py` file using Python: `week2_(sai_varma_paloji).py`.

## How to Play
1. Run the program as instructed above.
2. Follow the prompts to input your moves. You'll be asked to enter the index of the frog you want to move and the direction (right or left) you want to move it.
3. Continue making moves until the frogs have switched positions, or until you want to quit the game.

## Example Gameplay
Welcome to Leap Froggies Puzzle Game!

Initial State:
Left side: [G, G, G]
Right side: [B, B, B]

Enter the index of the frog you want to move (0-2): 0
Enter the direction you want to move (right or left): right

Updated State:
Left side: [G, G, B]
Right side: [_, B, B]

Enter the index of the frog you want to move (2-4): 2
Enter the direction you want to move (right or left): left

Updated State:
Left side: [B, B, B]
Right side: [G, G, G]

Congratulations! You solved the puzzle!

## Acknowledgements
- Special thanks to [Rushikesh Konapure] for guidance and support throughout the development process.
- Thanks to PrepInsta for providing inspiration and resources for puzzle game implementations.

## License
This project is licensed under the [MIT License](LICENSE).
