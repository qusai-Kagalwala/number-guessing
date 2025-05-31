# 🎯 Number Guessing Game

![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![100 Days of Code](https://img.shields.io/badge/100%20Days%20of%20Code-Day%2011-orange.svg)

A classic console-based number guessing game built in Python! 🐍 Try to guess the secret number between 1-100 with limited attempts based on your chosen difficulty level.

## 🎮 Game Features

- 🎲 **Random Number Generation**: Each game generates a unique number between 1-100
- 🎚️ **Two Difficulty Modes**: 
  - 🟢 **Easy Mode**: 10 attempts to guess
  - 🔴 **Hard Mode**: 5 attempts to guess
- 💬 **Interactive Feedback**: Get "Too high" or "Too low" hints after each guess
- 🎨 **ASCII Art**: Beautiful game logo display
- 📊 **Turn Counter**: Track remaining attempts

## 🚀 How to Play

1. **Start the Game**: Run the Python script
2. **Choose Difficulty**: Select 'easy' for 10 attempts or 'hard' for 5 attempts
3. **Make Your Guess**: Enter a number between 1-100
4. **Follow the Hints**: Use "too high" or "too low" feedback to adjust your next guess
5. **Win or Lose**: Guess correctly to win, or run out of attempts to lose!

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.6 or higher 🐍
- `art` library for ASCII graphics

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/qusai-Kagalwala/number-guessing.git
   cd number-guessing
   ```

2. **Install required dependencies**
   ```bash
   pip install art
   ```

3. **Run the game**
   ```bash
   python main.py
   ```

## 📸 Screenshot

```
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.
Choose a difficulty. Type 'easy' or 'hard': easy
You have 10 attempts remaining to guess the number.
Make a guess: 50
Too high.
Guess again.
You have 9 attempts remaining to guess the number.
Make a guess: 25
Too low.
...
```

## 🏗️ Code Structure

```
number-guessing/
│
├── main.py           # Main game file with all functions
├── README.md         # This file
└── requirements.txt  # Dependencies (optional)
```

### 🔧 Key Functions

- `game()` - Main game loop and setup
- `set_difficulty()` - Handles difficulty selection
- `check_answer()` - Compares guess with answer and provides feedback

## 🎯 Learning Objectives

This project demonstrates:
- ✅ **Random number generation** with `randint()`
- ✅ **User input handling** and validation
- ✅ **Conditional logic** and control flow
- ✅ **Function creation** and parameter passing
- ✅ **Game loop implementation**
- ✅ **Constants usage** for configuration

## 🚧 Future Enhancements

- [ ] 🏆 High score tracking
- [ ] 🔢 Custom number range selection
- [ ] 📈 Game statistics and analytics
- [ ] 🎵 Sound effects
- [ ] 🌐 Web-based GUI version
- [ ] 👥 Multiplayer mode

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest new features
- 🔀 Submit pull requests
- ⭐ Star the repository if you found it helpful!

## 📚 Part of 100 Days of Code

This project is **Day 11** of Angela Yu's 100 Days of Code Python Bootcamp. It focuses on:
- Functions with inputs and outputs
- Code organization and structure
- Game development fundamentals

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Qusai Kagalwala**
- GitHub: [@qusai-Kagalwala](https://github.com/qusai-Kagalwala)

## 🌟 Acknowledgments

- 🙏 Angela Yu for the amazing Python course
- 🎨 `art` library for ASCII graphics
- 💻 Python community for inspiration

---

⭐ **Star this repo if you enjoyed the game!** ⭐

![Made with Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg)
