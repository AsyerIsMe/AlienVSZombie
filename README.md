# Alien vs. Zombie

Welcome to Alien vs Zombie (Part 1). 

This half-completed game was inspired by the mobile game called Alien Path, a 
game where an alien work its way to defeat all the zombies by overcoming 
different challenges on the battlefield.

By only using limited commands, can the alien prove its worth and defeat all the zombies?

[!Gameplay Screenshot!](ss.JPG)

[!Full Gameplay!](https://youtu.be/h8DLofLM7No)

## Compilation Instructions

MacOS

```
g++ main.cpp -o main.exe
```

Windows
```

```

## User Manual

Please provide the user manual on how to use your program.

i) How to set up game board

ii) User manual for alien

1. Alien's movement
    1. The alien will start with health 100 and attack 0. 
    2. To move the alien to the right, type in the command "right" or "Right".
    3. To move the alien to the left, type in the command "left" or "Left".
    4. To move the alien upwards, type in the command "up" or "Up".
    5. To move the alien downwards, type in the command "down" or "down".
    6. The alien will stop moving if it hits the border, hits a rock (r), or hits a zombie (‘1’, ’2’, ’3’, ’4’, ’5’, ’6’, ’7’, ’8’, ’9’).
    7. When the alien stops moving, the alien’s turn will end and the zombies will start their movements/turns.

2. Arrow's direction
    1. To change the direction of an arrow, type in "arrow" for the command.
    2. To change the direction of the arrows, type in "arrow" for the command. 
    3. Once the terminal shows "Enter row, column and direction =", the user can input the row, column and direction of the  arrow they want to change.            (Example = "6 5 up"). Press enter to save the new input. Press any key to continue entering commands for the movement of the alien.

3. To quit the game, type in ‘quit’ or ‘Quit’.

iii) User manual for zombie
    
1. Generating Zombies
    - Players can generate at least one (1) zombie and at most nine (9) zombies. 
    - The amount of zombies cannot be more than the tiles (lower than row x column).

2. Zombie’s behaviour
    - Each zombie will move after the alien's turn.
    - They can only move to one spot (up, down, left, right) during each turn granted that there is no other zombie in the spot and there is no alien in        the spot.


## Progress Log

- [Part 1](PART1.md)
- [Part 2](PART2.md)

## Contributors

- Nur Aisyah Nabila Binti Nahar
- Asyrani Syazwan Bin Yuhanis
- Luqman Hakim Bin Noorazmi




