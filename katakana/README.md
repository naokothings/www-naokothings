# Katakana Flashcards

An interactive katakana practice tool to view the katakana chart and personalize flashcards.

This app lets you:

- View the full katakana chart (rotated layout)
- Select individual characters, rows, or columns
- Practice with flashcards
- Track session stats (correct, incorrect, percentage)
- Automatically detect weak characters
- Re-practice weak characters with one click
- Loop selected characters indefinitely for focused drills

---

## Features

### 🎯 Smart Practice Mode
- Correct answers auto-advance (fast feedback loop)
- Incorrect answers require correction before moving on
- Previously missed characters reappear later in the deck
- Selected characters loop infinitely for extended repetition

### 📊 Session Tracking
Each session tracks:
- Correct answers
- Incorrect answers
- Total attempts
- Percentage correct

Weak characters are detected using:


Miss rate ≥ 50%
AND
Attempts ≥ max(2, ceil(totalAnswered × 0.1))


This balances short practice sessions and long study sessions.

### 🧠 Weak Character Reinforcement
After ending a session:
- Weak characters are listed
- You can add them directly to your selection
- Or clear and practice only weak characters

### ⚙️ Settings
- Strict Hepburn mode (default ON)
- Optional acceptance of alternate romaji spellings

---

## How It Works

The chart is rotated 90° clockwise:

- ン appears on the far left
- A / I / U / E / O appear vertically on the far right

Click:
- Individual characters to toggle selection
- Row headers to select entire vowel rows
- Column headers to select entire consonant groups

Press **START** to begin.

Press **END** to return to selection and review your session.

---

## File Structure


justnaokothings/
index.html (main site homepage)
katakana/
index.html (this flashcard app)
README.md


The app runs entirely client-side (no backend required).

---

## Future Ideas

- Dakuten / handakuten support (ガ, ザ, etc.)
- Small ャ / ュ / ョ combinations
- Timed mode
- Accuracy graph over time
- Hiragana version

---

Built as a focused learning tool — simple, fast, and intentionally distraction-free.
