# 🧮 Simple Calculator Application

A beginner-friendly **React-based Calculator App** to perform basic arithmetic operations. Designed with simplicity and clarity, this project is perfect for learning how React handles state and component logic.

---

## 🔍 Overview

This application is a simple **React Calculator** that allows users to perform basic calculations like addition, subtraction, multiplication, and division. It focuses on building reusable components and managing state in a clear, structured way.

---

## 🚀 Features

- ➕ Addition, ➖ Subtraction, ✖️ Multiplication, ➗ Division
- 🧼 Clear button to reset the calculator
- 🎯 Instant evaluation of expressions
- 📱 Responsive and interactive interface

---

## 🧩 Component Structure

### `App.jsx`
- Handles main state and logic
- Renders `Display`, `ButtonPanel`, and manages input/output

### `Display.jsx`
- Shows the current input or result
- Receives the `value` as a prop

### `ButtonPanel.jsx`
- Renders calculator buttons in rows
- Maps button clicks to the `onButtonClick` handler

### `Button.jsx`
- Reusable component for each calculator button
- Triggers parent click event via props

---

## 🔄 State Management

- State is managed centrally in `App.jsx` using `useState`.
- All interactions (like button clicks) update the expression/result state.
- `eval()` or a custom logic is used to calculate the result based on the input.

---

## 📸 Final Output Screenshots

Add your screenshots below this section to showcase the UI and functionality.

### 🖼️ Calculator Interface
![Calculator Interface](./screenshots/calculator-interface.png)

### 🧮 Calculation in Progress
![Calculation](.screenshots/calculation.png)

### ✅ Result Display
![Result](./screenshots/result.png)

---

## ⚙️ Setup Instructions

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/calculator-app.git
   ```

2. Navigate to the project directory  
   ```bash
   cd calculator-app
   ```

3. Install dependencies  
   ```bash
   npm install
   ```

4. Run the development server  
   ```bash
   npm start
   ```

---

## 🙌 Credits

Created with ❤️ using ReactJS.  
Special thanks to the open-source community for guidance and UI inspiration.

---

## 📄 License

This project is licensed under the MIT License. Feel free to use and modify!
