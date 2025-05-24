# Wordle Bot

A Python-powered bot that solves Wordle puzzles using logic, frequency analysis, and strategic guesses. This notebook demonstrates how a simple AI can effectively crack the Wordle game, often in fewer than 6 attempts.

## 📌 Features

- Solves Wordle puzzles algorithmically.
- Implements letter frequency analysis to optimize guesses.
- Adapts based on feedback (`green`, `yellow`, `grey`) like the real game.
- Easy to modify and extend with new strategies.

## 🚀 How It Works

1. The bot starts with a high-frequency English word.
2. After receiving feedback (e.g., green, yellow, gray):
   - It filters out words that don’t match constraints.
3. Chooses the next optimal word based on letter frequency among remaining candidates.
4. Repeats until the word is guessed or turns are exhausted.

## 🧪 Technologies Used

- Python 3
- Jupyter Notebook
- NLTK or custom word frequency dataset (if applicable)
- Basic NLP & pattern matching

## 📂 File Structure

```
.
├── wordle-bot.ipynb    # Jupyter notebook with implementation and explanations
└── README.md           # Project description and usage
```

## 📈 Sample Output

```
Guess 1: SLATE
Feedback: ⬜🟨🟨⬜⬜

Guess 2: POINT
Feedback: 🟩⬜⬜⬜⬜

...

Solved in 4 guesses!
```

🧰 Usage
1.	Clone the repository:
 
```
git clone https://github.com/YOUR_USERNAME/wordle-bot.git
cd wordle-bot
```


2.	Launch the notebook:
```
jupyter notebook wordle-bot.ipynb
```

3.	Run the cells step-by-step and follow the logic or modify the initial guess.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the algorithm or interface.

## 📄 License

MIT License

⸻

© 2025 Steven Itti Leon

---

Let me know if you'd like to:
- Add installation instructions for dependencies.
- Include a GUI/CLI interface in the future.
- Add the actual performance statistics of your bot over multiple games.
