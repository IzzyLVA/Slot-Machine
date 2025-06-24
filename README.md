# 🎰 Python Slot Machine

This is a simple terminal-based slot machine game built with Python. Users can deposit money, place bets on up to 3 lines, and spin the reels to try their luck. The game calculates winnings based on randomly generated symbols and their assigned values.

---

## 🧩 Features

- Bet on 1 to 3 lines.
- Randomly generated slot symbols with weighted frequency.
- Symbol-based payout system.
- Balance management with deposit and bet limits.
- Interactive terminal UI.

---

## 📸 Demo

```
What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 3
What would you like to bet on each line? $5
you are betting $5 on 3 lines. Total bet is equal to $15
A | B | D
A | B | C
A | C | D
You won 15.
You won on lines: 1
```

---

## 🧠 How It Works

- Symbols (`A`, `B`, `C`, `D`) are randomly selected with different frequencies.
- Winnings are calculated based on matching symbols across horizontal lines.
- Symbol values:
  - A = 5x
  - B = 4x
  - C = 3x
  - D = 2x

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x

### Running the Game

1. Clone the repository:
   ```bash
   git clone https://github.com/IzzyLVA/Slot-Machine.git
   cd python-slot-machine
   ```

2. Run the script:
   ```bash
   python slot_machine.py
   ```

---

## 📁 File Structure

- `slot_machine.py` — main game logic, input handling, and UI.


---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
