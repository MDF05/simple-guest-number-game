# Tebak Angka Game 🎯

A simple number guessing game built with **JavaScript**, designed to **practice and improve JavaScript skills**. This game runs directly in the browser using `prompt` and `alert` for interaction, making it lightweight and easy to play.

---

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [How to Play](#how-to-play)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Demo

You can try the game online here:  
- [Play Tebak Angka Again](https://tebak-angka-sage.vercel.app/)  
- [Back to Home](https://dava-rho.vercel.app/)

---

## Features

- Three difficulty levels: `easy`, `medium`, `hard`
- Random number generation based on chosen difficulty
- 3 lives per round
- Clues given if guess is too high or too low
- Option to replay the game multiple times
- Simple, browser-based game using JavaScript `prompt` and `alert`

---

## How to Play

1. Open the game in your browser.
2. A welcome message will appear.
3. Choose a difficulty level by typing `easy`, `medium`, or `hard`.
   - `easy`: numbers from 1 to 10  
   - `medium`: numbers from 1 to 20  
   - `hard`: numbers from 1 to 30
4. You have **3 lives** to guess the correct number.
5. After each wrong guess, a clue will help you adjust your next guess:
   - "Too low" → guess higher  
   - "Too high" → guess lower
6. Game ends when you either guess correctly or lose all lives.
7. Option to replay the game when a round finishes.

**Note:**  
- Input must be a number within the valid range.  
- No spaces or letters allowed.

---

## Technologies Used

- **HTML5** – for page structure
- **CSS3** – for basic styling
- **JavaScript (Vanilla JS)** – for game logic and interaction

---

## Installation

To run the project locally:

1.  Clone the repository:  
```bash
git clone https://github.com/yourusername/tebak-angka.git


2.  Navigate to the project folder:
```bash
cd tebak-angka

3.  Open index.html in your favorite browser.
No additional dependencies are required.

Project Structure
```bash
tebak-angka/
│
├─ index.html        # Main HTML page
├─ index.js          # JavaScript game logic
└─ README.md         # Project documentation



Contributing

Contributions are welcome! You can:

Suggest new features (e.g., scoreboard, better UI)

Improve code readability

Fix bugs

Please fork the repository and submit a pull request.


License

This project is open-source and available under the MIT License.