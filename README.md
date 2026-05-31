# ATM System - C++

A console-based ATM simulation system built in C++.

> This project is based on lessons from the **Programming Advice** website by **Dr. Mohammed Abu-Hadhoud**.

---

## Features

- Secure login with account number and PIN code
- Quick withdraw with preset amounts
- Normal withdraw with custom multiples of 5
- Deposit funds to account
- Check account balance
- Persistent client data stored in a text file

---

## How It Works

Client records are stored in `Clients.txt` using a custom `#//#` separator format. On login, the system searches for a matching account number and PIN. Once authenticated, the user can perform transactions which are saved back to the file immediately.

---

## Requirements

- C++ compiler (C++11 or later)
- Windows OS (uses `system("cls")` and `system("pause")`)

---

## How to Run

1. Clone the repository
2. Compile the source file using any C++ compiler
3. Make sure `Clients.txt` exists in the same directory as the executable
4. Run the executable and log in with a valid account number and PIN

---

## Project Structure

```
ATM-System-CPP/
├── main.cpp        # Main source file
└── Clients.txt     # Client data file (required at runtime)
```

---

## Source

Based on course material from [Programming Advice](https://www.programmingadvices.com) by Dr. Mohammed Abu-Hadhoud.
