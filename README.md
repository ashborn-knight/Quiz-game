# Quiz Game 🎮

A simple JavaScript quiz game that randomly selects questions from different categories and lets the computer attempt an answer. The game then checks whether the computer’s choice is correct or wrong.

---

## 📋 Features
- Multiple categories: Math, Science, History, Geography, Literature.
- Each question has multiple choices and one correct answer.
- Random question selection.
- Random computer choice from the available options.
- Result check with feedback:
  - ✅ Correct answer
  - ❌ Wrong answer (shows the correct one)

---

## 🛠️ How It Works
1. A random question is selected from the `questions` array.
2. The computer randomly picks one of the choices.
3. The program compares the computer’s choice with the correct answer.
4. The result is displayed in the console.

---

## 📂 Project Structure
- `questions` → Array of question objects (category, question, choices, answer).
- `getRandomQuestion()` → Picks a random question.
- `getRandomComputerChoice()` → Picks a random choice for the computer.
- `getResults()` → Compares the computer’s choice with the correct answer.

---

## ▶️ Example Run
```bash
Question: What is 2 + 2?
Computer chose: 3
The computer's choice is wrong. The correct answer is: 4
