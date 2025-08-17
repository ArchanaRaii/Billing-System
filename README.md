# 🛒 Supermarket Billing System

A simple console-based C++ application for managing a basic supermarket billing system. This program allows users to:
- Add new items with their prices and quantities.
- Generate bills by purchasing available items.
- Update inventory after purchases.

---

## 📂 Features

✅ Add new items to the stock  
✅ Print and generate customer bills  
✅ Deduct item quantities after each purchase  
✅ View total bill at checkout  
✅ Simple and easy-to-use console UI

---

## 🧾 How It Works

### 1. Add Items
You can input:
- Item name
- Item rate
- Quantity in stock

These are saved in a local file (`Bill.txt`) in the format: <Item> : <Rate> : <Quantity>


### 2. Print Bill
- Enter an item name and quantity to purchase.
- The system checks availability and calculates the total cost.
- If sufficient stock exists, it deducts the purchased quantity.
- The total bill is displayed at the end of the session.

---

## 🔧 File Structure & Paths

This project **uses local file storage** to maintain inventory and billing details.

> ⚠️ Make sure directory exists before running the program, or update the file paths in the code accordingly.

---

## 💻 Requirements

- OS: Windows  
- Compiler: Any C++ compiler supporting C++11 or above (e.g., GCC, MSVC)  
- IDE (optional): Code::Blocks, Visual Studio, or any C++ IDE  
- Libraries Used:  
  - `<iostream>`, `<fstream>`, `<sstream>`, `<string>`, `<windows.h>`

---

## 🚀 How to Run

1. **Open the source code** in your C++ IDE or editor.
2. **Ensure the file path in the code** (for `Bill.txt`) matches an existing directory.
3. **Compile and run** the program.
4. Use the menu to:
   - Add items
   - Generate and print bills
   - Exit the application

---

## 📌 Notes

- The program uses `system("cls")` and `Sleep()` functions from `windows.h`. It will **only run on Windows**.
- File format parsing is simple; avoid adding items manually in the file unless they follow the exact format.

---


## 📸 ScreenRecording

https://github.com/user-attachments/assets/8ea0471c-92ae-4f15-bf6d-737943c2d04d



---



