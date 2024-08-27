# Weapon System for Multiplayer Action Game

## Objective

Design and implement a multiplayer game component using Unreal Engine and C++ that simulates a weapon system for an action game.

## Brief

This project involves the development of a weapon system that demonstrates an understanding of gameplay systems, Unreal Engine's multiplayer framework, and the Gameplay Ability System (GAS). Additionally, the project includes implementing a simple AI for the player's character and ensuring smooth game performance.
### You can use `GASTestLevel` as environment

## Tasks

### Task 1 - Gameplay Ability System

Build a flexible Gameplay Ability System that allows a player's character to use weapons. The system should be designed for future extensibility. Implement the following weapons:

- **Rifle:** A ranged weapon that deals damage to a single enemy.
- **Medkit:** A tool that restores the player's health.
- **Shield:** A device that provides a temporary defense boost to the player.

### Task 2 - Multiplayer Framework

Ensure that the weapon system functions correctly in a multiplayer environment. Actions taken by one player with their weapon should have the intended effects on other players in the game.

### Task 3 - AI System

Create a simple AI for the player's character. The AI should be capable of taking over when the player is not in control and perform basic actions such as:

- Attacking enemies with weapons.
- Healing itself when health is low.

### Task 4 - Performance Optimization

Profile and optimize the game to ensure it runs smoothly, particularly in a multiplayer environment.

### Task 5 - Debugging

Thoroughly debug the system and resolve any gameplay issues that arise, ensuring that the game maintains a high standard of quality.

## Evaluation Criteria

- **Gameplay Ability System:** Correct implementation of the weapon system using GAS.
- **Multiplayer Functionality:** Proper use of Unreal Engine's multiplayer framework to handle weapon effects between players.
- **AI System:** The AI behaves as expected, performing actions autonomously when the player is not in control.
- **Performance:** The game runs smoothly without major performance issues.
- **Code Quality:** The code is clean, well-organized, and follows good programming practices.
