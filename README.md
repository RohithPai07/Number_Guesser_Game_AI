# Number Guessing Game AI  
**Version 0.1**  

## Overview  
The **Number Guessing Game AI** is an advanced iteration of the classic Number Guessing Game. 

In this version, the program simulates an AI player that plays the game autonomously. 

The AI leverages a random selection strategy and systematically narrows down its guesses based on feedback. 

The code retains developer options, comprehensive error handling, and modular design for *future updates*.

---

## Features  

### Core Functionality:  
- **Autonomous Gameplay:**  
  The AI guesses numbers in a range of 0-100 until it finds the correct answer, refining its range based on whether the guess is too high or low.  

- **Feedback Mechanism:**  
  The AI narrows its range of guesses using real-time feedback (`Try Going Higher` or `Try Going Lower`).  

- **Game Metrics:**  
  Tracks the number of tries and calculates the average tries per game.  

---

### Developer Options:  
Currently Not Accessible

Expected Availability in the future updates so stay tuned ;)

---

## How It Works  
1. **Initialization:**  
   The game sets a random target number between 0-100.  

2. **AI Strategy:**  
   - The AI makes a guess within the current range.  
   - Adjusts the range (`low` or `high`) based on feedback.  
   - Repeats until the correct number is found.  

3. **Game Flow:**  
   - Upon guessing correctly, the AI displays the number of attempts and the average tries.  
   - Users can choose to start a new game or end the session.  

---

## Update Log  
- **v0.1:** Initial Release.  
  - Autonomous AI gameplay.  
  - Retained metrics (number of tries, average tries).
  - Comprehensive input validation and feedback mechanism.

---

## Future Updates
- **Accessibility of developer mode**
  - Currently the developer mode options are not accessible without any modification in the code...
  - Future Updates will bring about a change in this issue.
  - Expected arrival at `v0.5`
 
- **User vs AI**
  - A Mode Where You Can Play Against AI To See Wether Human Brains Are More Powerful Than AI or not.
  - Expected arrival at `v1.0`
