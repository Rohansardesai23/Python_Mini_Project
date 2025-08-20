# 🤖 PyCal – Python Calculator

PyCal is a simple Python-based calculator with two modes:

* **Two Number Input** – Perform operations between two fixed numbers.
* **Multiple Number Input** – Enter full mathematical expressions and evaluate them.

---

## 🚀 Features

### 🔹 Option A – Two Number Input

* Input **two numbers** once and perform different operations repeatedly.
* Supported operations:

  1. Addition (`a + b`)
  2. Subtraction (`a - b`)
  3. Multiplication (`a * b`)
  4. Division (`a / b`)
  5. Modulus (`a % b`)
  6. Exponentiation (`a ** b`)
  7. Equality Check (`a == b`)

### 🔹 Option B – Multiple Number Input

* Enter full expressions like: `5 + 2 * 3 - 1`
* Supports operators: `+ - * / % ** //`
* Evaluates the expression and prints the result.

---

## 📦 Installation

Clone this repository and run the Python script:

```bash
git clone https://github.com/your-username/PyCal.git
cd PyCal
python calculator.py
```

---

## 🎮 Usage

1. Run the program.
2. Choose between:

   * **A**: Two number input mode.
   * **B**: Multiple number input mode.
3. Follow the instructions on screen.
4. Type `exit` anytime to quit.

---

## 📷 Example Run

```text
###   🤖Welcome To PyCal🤖   ###

	Menu📱

A. Two Number Input
B. Multiple Number Input

Chose option A or B: A

You Chose Two Number Inputs Option

Enter Number 1 : 10
Enter Number 2 : 5

Option You Can Perform On Above Numbers:
1. a + b
2. a - b
3. a * b
4. a / b
5. a % b
6. a ^ b
7. a = b

Enter Option From List (1-7) or 'exit': 1
You chose Addition
Result: 15
```

---

## ⚠️ Notes

* Division by zero is handled safely.
* Use valid operators only in **Option B**.
* This project is for **learning purposes** and uses Python’s `eval()` function, which should be avoided in production.

---

## 🛠️ Technologies Used

* Python 3.x

---

## 📌 Future Improvements

* Add GUI support (Tkinter/Streamlit).
* Add history of calculations.
* Add error handling for invalid expressions.

---

## 👨‍💻 Author

* **Rohan Sardesai**
* **rohansardesai04@gmail.com**
* **9022228467**
