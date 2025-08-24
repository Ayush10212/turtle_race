# 🐢 Turtle Race (Python + Turtle)

A fun, beginner-friendly **Turtle graphics** mini-game where you bet on a turtle’s color and watch them race to the finish line. If your color wins, you win!

---

## 🎮 How It Works
- On launch, a prompt asks you to **enter a color** to bet on.
- Six turtles (red, orange, blue, purple, yellow, green) line up at the start.
- They move forward by **random distances** each tick.
- The first turtle to cross the finish line (x > 230) wins.
- The result prints in the terminal: whether **you won or lost** and which color won.

---

## 🧩 Features
- Simple, readable Python code using only the **standard library**.
- Color betting via Tkinter-style text input from the Turtle `Screen`.
- Randomized movement for unpredictable outcomes.
- Click the window to exit (`screen.exitonclick()`).

---

## 📦 Requirements
- Python **3.x**
- No external packages required (uses `random` and `turtle` from the standard library).

---

## ⚡ Run It
```bash
# If you have Python mapped to 'python'
python main.py

# Or, on some systems
python3 main.py

# On Windows (if 'py' launcher is available)
py main.py
