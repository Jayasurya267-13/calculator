# 🧮 Tkinter Calculator (Python)

Let's build a calculator using python

A simple graphical calculator built using **Python** and **Tkinter**.
This project replicates the basic functionality of a standard calculator, including arithmetic operations, percentage, sign change, and clear functionality.

---

## 📌 Features

* User-friendly graphical interface using Tkinter
* Supports basic arithmetic operations:

  * Addition (`+`)
  * Subtraction (`-`)
  * Multiplication (`×`)
  * Division (`÷`)
* Additional functions:

  * Clear All (`AC`)
  * Percentage (`%`)
  * Sign toggle (`+/-`)
  * Decimal point support (`.`)
* Automatically removes unnecessary decimal zeros (e.g., `5.0 → 5`)
* Responsive button layout
* Window is centered on the screen and non-resizable

---

## 🛠️ Technologies Used

* **Python 3**
  
* **Tkinter** (standard Python GUI library)

---

## 📂 Project Structure

```

calculator/
│
├── calculator.py   # Main Python file
└── README.md       # Project documentation

```

---

## ▶️ How to Run the Project

1. Make sure Python 3 is installed on your system

   ```bash

   python --version

   ```

2. Clone this repository:

   ```bash
   
   git clone https://github.com/your-username/tkinter-calculator.git

   ```

3. Navigate to the project directory:

   ```bash

   cd tkinter-calculator

   ```

4. Run the application:

   ```bash
   
   python calculator.py
   
   ```

---

## 🧠 How It Works

* The calculator uses a **grid-based layout** to position buttons.
* User inputs are displayed on a label acting as the screen.
* Two operands (`A` and `B`) and an operator are stored globally.
* Button clicks are handled using a single callback function.
* Arithmetic operations are performed only when the `=` button is pressed.

---

## 📸 Screenshot (Optional)

*Add a screenshot of the calculator UI here after running the app.*

---

## 🚀 Future Improvements

* Add keyboard input support
* Handle division by zero errors
* Improve UI styling and animations
* Add advanced functions (square root, power, memory buttons)

---

## 📜 License

This project is open-source and free to use for learning and personal projects.

---

## 🙌 Acknowledgements

Built as a Python learning project using Tkinter.

Happy Coding! 🐍✨

