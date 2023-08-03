# "Rock - Paper - Scissors" Game By Ivan
This is a simple console-based C# implementaion of the "Rock Paper Scissors" game

<img alt="Image" width = 300px src="https://img.freepik.com/premium-vector/hands-playing-rock-paper-scissors-game-flat-design-style-vector-illustration_540284-598.jpg?w=2000" />
Rock paper scissors is an intransitive hand game, usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. The rules are:

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock

If both players choose the same shape, the game is tied and is usually replayed to break the tie.

## Input and Output
The player enters on of the following options:

- **r** or **rock**
- **p** or **paper**
- **s** or **scissors**

The computer chooses a **random** option and then reveals the winner.

The player can play again if he likes by entering either **yes** or **no**.

## Solution

| You  | Computer | Outcome |
| ---- | -------- | --------|
| rock | paper    | You lose|
| rock | scissors | You win |
| rock | rock     | Draw    |
| paper | paper    | Draw   |
| paper | scissors | You lose |
| paper | rock     | You win    |
| scissors | paper    | You win|
| scissors | scissors | Draw |
| scissors | rock     | You lose    |

We handle all these situations with a series of checks.

## Source code
[Source Code](RockPaperScissors.cs)

## Screenshots

![image](https://github.com/Ivan-Ven-Ivanov/RockPaperScissorsByIvan/assets/141314106/bb7bf63d-e91e-4d29-ab4e-1c03b9be1f67)

## Live Demo
You can play the game directly in your web browser here:

[![Play Button](https://static.thenounproject.com/png/1703076-200.png)](https://replit.com/@Ivan-Ven-Ivanov/RockPaperScissors-Game-by-Ivan#Main.cs)
