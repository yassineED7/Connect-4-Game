# 🎮 Connect Four - Interactive Console Game

[![C++](https://img.shields.io/badge/C++-17-blue.svg)](https://isocpp.org/)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Interactive C++ Connect Four console game with colored ASCII interface, Player vs Player/AI modes, cross-platform support, win detection algorithms, input validation, and replay functionality. Demonstrates OOP principles, 2D vectors, game loops, and AI basics in an engaging strategy game experience.

## 🎯 Features

- 🎨 **Colorful ASCII Interface** - Beautiful game board with red and yellow tokens
- 👥 **Dual Game Modes** - Player vs Player or Player vs Computer
- 🖥️ **Cross-Platform** - Works on Windows, Linux, and macOS
- 🧠 **Smart AI Opponent** - Random move selection with expandable architecture
- ✅ **Input Validation** - Handles invalid inputs and full columns gracefully
- 🔄 **Replay System** - Play multiple rounds with reset functionality
- 🏆 **Win Detection** - Checks horizontal, vertical, and diagonal connections

## 🚀 Getting Started

### Prerequisites

- C++ compiler (GCC, Clang, or MSVC)
- C++11 or higher support

### Compilation

```bash
# Using g++
g++ -std=c++11 -o connect_four main.cpp

# Using clang++
clang++ -std=c++11 -o connect_four main.cpp

# On Windows with MSVC
cl /EHsc main.cpp /Fe:connect_four.exe
```

### Running the Game

```bash
# Linux/macOS
./connect_four

# Windows
connect_four.exe
```

## 🎮 How to Play

1. **Start the Game** - Run the executable to see the welcome screen
2. **Enter Names** - Input player names for personalization
3. **Choose Mode** - Select Player vs Player or Player vs Computer
4. **Make Moves** - Enter column numbers (0-6) to drop tokens
5. **Win or Draw** - Get four in a row to win, or fill the board for a draw
6. **Play Again** - Choose to replay or exit after each game

### Game Controls

- **Column Selection**: Enter numbers 0-6 to choose columns
- **Replay**: Press 'y' to play again, 'n' to exit
- **Quit**: Close the terminal window to exit

## 🏗️ Project Structure

```
connect-four/
├── main.cpp          # Complete game implementation
├── README.md          # This file
└── LICENSE           # MIT License
```

## 🛠️ Technical Details

### Core Components

- **ConnectFour Class** - Main game logic and state management
- **Board Management** - 2D vector for game grid (6x7 default)
- **Win Detection** - Algorithms for checking victory conditions
- **AI System** - Random move selection with modular design
- **Cross-Platform UI** - Windows API and ANSI color support

### Key Methods

```cpp
void initBoard()              // Initialize/reset game board
void displayBoard()           // Render colored ASCII board
bool insertToken(int, char)   // Drop token in column
bool checkWin(char)          // Check for four in a row
int getAIMove()              // AI move selection
```

## 🎨 Screenshots

```
╔══════════════════════════════════════╗
║          🎮 CONNECT FOUR 🎮         ║
║     Interactive Console Edition      ║
╚══════════════════════════════════════╝

   0   1   2   3   4   5   6  
 ╔═══╤═══╤═══╤═══╤═══╤═══╤═══╗
 ║   │   │   │   │   │   │   ║
 ╟───┼───┼───┼───┼───┼───┼───╢
 ║   │   │   │ ● │   │   │   ║
 ╟───┼───┼───┼───┼───┼───┼───╢
 ║   │   │   │ ● │   │   │   ║
 ╟───┼───┼───┼───┼───┼───┼───╢
 ║   │   │ ● │ ● │   │   │   ║
 ╟───┼───┼───┼───┼───┼───┼───╢
 ║   │   │ ● │ ● │   │   │   ║
 ╟───┼───┼───┼───┼───┼───┼───╢
 ║ ● │ ● │ ● │ ● │   │   │   ║
 ╚═══╧═══╧═══╧═══╧═══╧═══╧═══╝
```

## 🚀 Future Enhancements

- [ ] **Advanced AI** - Implement Minimax algorithm with difficulty levels
- [ ] **GUI Version** - Create graphical interface using SFML/SDL
- [ ] **Network Play** - Add online multiplayer functionality  
- [ ] **Statistics** - Track player wins, losses, and game history
- [ ] **Custom Boards** - Variable board sizes (4x4, 8x8, etc.)
- [ ] **Save/Load** - Game state persistence
- [ ] **Timer Mode** - Add turn time limits
- [ ] **Themes** - Multiple visual themes and color schemes

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for Contribution

- AI improvements (Minimax, Alpha-Beta pruning)
- Additional game modes
- Performance optimizations
- Code documentation
- Bug fixes and testing

## 📚 Learning Outcomes

This project demonstrates:

- **Object-Oriented Programming** - Class design and encapsulation
- **Data Structures** - 2D vectors and arrays
- **Algorithms** - Win detection and AI logic
- **Input/Output** - Console interaction and validation
- **Cross-Platform Development** - Windows/Unix compatibility
- **Game Development** - Game loops and state management

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created as a comprehensive C++ learning project demonstrating console game development, OOP principles, and cross-platform programming.

## 🙏 Acknowledgments

- Classic Connect Four game mechanics
- ASCII art and console styling inspiration
- Cross-platform C++ development community

---

⭐ **Star this repository if you found it helpful!** ⭐
