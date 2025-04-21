# ✊✋✌️ Rock Paper Scissors Game (Java Console App)

This is a simple Java console game that lets you play **Rock, Paper, Scissors** against the computer. It's a fun beginner project for learning user input, conditionals, and basic logic in Java.

## 🎮 How It Works

1. The user is prompted to enter a number:
   - `0` for Rock
   - `1` for Paper
   - `2` for Scissors

2. The computer randomly selects one of the three options.

3. The program compares both choices and declares the winner:
   - Rock beats Scissors
   - Paper beats Rock
   - Scissors beats Paper
   - If both choose the same, it’s a tie

## 🧪 Example Gameplay

```text
Welcome to the rock paper scissors game!
Enter your choice
0: Rock, 1: Paper, 2: Scissors
1
Computer chose: 0
You win! - Congratulations!!
🧠 Logic Summary
if (userChoice == computerChoice)
    → Tie
else if (
    (user == Rock && computer == Scissors) ||
    (user == Paper && computer == Rock) ||
    (user == Scissors && computer == Paper)
)
    → User wins
else
    → Computer wins
📌 Requirements
Java 8 or higher

Eclipse IDE (or any Java IDE)

JDK properly set up in your environment

🚀 How to Run (In Eclipse)
Open Eclipse and create a Java project

Inside src/day5/, add the file: RockPaperScissorsGame.java

Right-click the file → Run As > Java Application

Enter your choice in the console when prompted

📂 Project Structure
src/
└── day5/
    └── RockPaperScissorsGame.java
💡 Future Enhancements
Allow multiple rounds

Track and display score

Use string inputs instead of numbers (e.g., "rock" instead of 0)

Add input validation for non-integer inputs

👤 Author
This Java project was created as a beginner-friendly programming exercise to practice:

Scanner for user input

Math.random() for computer decisions

if-else and conditional logic

Basic game development logic

Have fun playing! 🎉
