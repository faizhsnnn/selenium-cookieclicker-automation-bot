# Selenium Cookie Clicker Automation Bot

## Overview

This project implements a browser automation bot using Selenium WebDriver that plays the Cookie Clicker game automatically.

The bot continuously clicks the primary cookie while periodically evaluating available upgrades and purchasing the most expensive affordable item.

Built as part of #90DaysOfCode to demonstrate strategy-based automation and dynamic DOM interaction.

---

## Technologies Used

- Python
- Selenium WebDriver
- ChromeDriver

---

## Key Concepts Demonstrated

- WebDriver configuration and session management
- Timed execution using system clock
- Dynamic DOM state inspection
- CSS selector-based element discovery
- Conditional decision logic for upgrade strategy
- Exception handling for runtime stability
- Automation loop control with execution limits

---

## Automation Logic

1. Launch browser and navigate to Cookie Clicker.
2. Select English language.
3. Continuously click the main cookie.
4. Every 5 seconds:
   - Extract current cookie count.
   - Identify available upgrades.
   - Purchase the most expensive enabled upgrade.
5. Run for a fixed duration (5 minutes).
6. Print final cookie count.

---

## Installation

```bash
pip install selenium
```

---
Ensure ChromeDriver version matches installed Chrome browser and is available in PATH.

---
Run
```
python main.py

```

---
# Why This Project Matters

This project demonstrates more than simple automation.

It showcases:

Stateful browser automation

Real-time decision-making logic

DOM-driven strategy execution

Controlled long-running automation tasks

These concepts are foundational in:

End-to-end test automation

Workflow bots

Performance testing

Intelligent UI automation systems

---
# Author

Faiz Hasan

Python Automation & Backend Developer
