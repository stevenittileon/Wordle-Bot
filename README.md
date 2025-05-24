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
- Prompt Engineering
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

Copyright (c) 2025 Steven Itti Leon

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in allcopies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
