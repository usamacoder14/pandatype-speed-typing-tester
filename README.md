# 🐼 PandaType — Speed Typing Tester

A clean and interactive speed typing tester built with **HTML5, Tailwind CSS, and Vanilla JavaScript**.

PandaType allows users to test their typing speed and accuracy through timed typing sessions, providing character-by-character visual feedback and detailed results when the test is completed.

## 🌐 Live Demo

👉 **[View Live Demo](https://usamacoder14.github.io/pandatype-speed-typing-tester/))**

## 📸 Preview

![PandaType Preview](/assets/sceenshot.png)

## ✨ Features

- ⌨️ **Character-by-Character Feedback**
  - Correctly typed characters are highlighted in yellow.
  - Incorrect characters are visually marked in red.
  - Untyped characters remain visually distinct.
  - Provides immediate feedback while typing.

- ⚡ **Accurate WPM Calculation**
  - Calculates Words Per Minute based on correctly typed characters.
  - Takes the actual elapsed typing time into account.
  - Uses the standard 5-characters-per-word calculation.

- 🎯 **Typing Accuracy Tracking**
  - Calculates typing accuracy as a percentage.
  - Tracks correct and incorrect characters during the test.
  - Displays the final accuracy when the test is completed.

- ⏱️ **Multiple Time Options**
  - Allows users to select different test durations.
  - Automatically resets the test when a new duration is selected.
  - Countdown timer tracks the remaining test time.

- 📊 **Completion Results**
  - Displays a dedicated result screen when the test ends.
  - Shows:
    - WPM
    - Accuracy
    - Errors
    - Time taken

- 🔄 **Restart Test**
  - Allows users to quickly start a fresh typing session.
  - Loads a new random paragraph for each test.

- 📝 **Random Typing Paragraphs**
  - Selects a paragraph randomly from the available typing passages.
  - Provides a different typing experience across test sessions.

- ⌫ **Backspace Support**
  - Allows users to correct previously typed characters.
  - Updates correct and incorrect character counts when characters are removed.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure, typing interface, timer, and result screen |
| Tailwind CSS | Layout, typography, styling, colors, and responsive interface |
| Vanilla JavaScript | Typing logic, character validation, WPM calculations, accuracy tracking, timer management, and DOM updates |
| Lucide Icons | Interface icons |

## ⚙️ How It Works

1. Select a typing test duration.
2. Start typing the displayed paragraph.
3. The countdown timer starts automatically with the first typed character.
4. Correct characters are highlighted in yellow.
5. Incorrect characters are marked in red.
6. Backspace can be used to correct previously typed characters.
7. The test ends when the selected time expires or the paragraph is completed.
8. PandaType calculates the final WPM and accuracy.
9. A completion screen displays the final typing statistics.
10. Restart the test to begin a new session with a randomly selected paragraph.

## 🎯 Project Highlights

This project focuses on creating a simple and interactive browser-based typing experience while implementing:

- Real-time keyboard input handling
- Character-by-character text comparison
- Accurate WPM calculations based on elapsed time
- Accuracy calculations
- Correct and incorrect character tracking
- Backspace handling
- Countdown timer management
- Random paragraph selection
- Dynamic DOM updates
- Test state management
- Multiple test duration options
- Custom completion results screen
- Tailwind CSS interface

## 📂 Project Structure

```text
pandatype/
│
├── index.html
├── assets/
│   └── screenshot.png
│
└── README.md
