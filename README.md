# Verilog-Based Digital Password Lock

## Overview

This project implements a digital password authentication system using Verilog HDL. The entered password is compared with a predefined password. If the password is correct, access is granted. After three consecutive incorrect attempts, the system enters a locked state and denies access until it is reset.

---

## Features

- 4-bit password authentication
- Three incorrect attempt lock mechanism
- Synchronous clock-based operation
- Asynchronous reset
- Verilog HDL implementation
- Functional verification using a testbench
- Simulated using EDA Playground

---

## Tools Used

- Verilog HDL
- EDA Playground

---

## Repository Structure

```
Verilog-Based-Digital-Password-Lock
│
├── password_lock.v
├── password_lock_tb.v
├── Output.png
└── README.md
```

---

## Working

1. User enters a 4-bit password.
2. The system compares it with the stored password.
3. If correct, access is granted.
4. If incorrect, the failed-attempt counter increases.
5. After three incorrect attempts, the system locks.
6. A reset signal unlocks the system.

---

## Author

Divya Madhuri
