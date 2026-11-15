# Sudoku

A single-file Sudoku game with four difficulty levels, pencil marks, a built-in solving guide, and short codes that let friends solve the same puzzle at the same time. It runs in any modern browser on phones, tablets, and computers, with no account, install, or tracking.

## Features and benefits

**Four difficulty levels.** Every puzzle is generated fresh and has exactly one solution. Levels are graded by the techniques they need: Easy needs only naked singles, Medium adds hidden singles, and Hard and Expert need techniques beyond singles. You can step up at your own pace.

**Pencil marks that work the way you think.** Switch between pen and pencil, or hold Shift while typing a number to add a mark for just that entry. Fill marks adds every valid candidate in one tap, and matching marks clear automatically when you place a number (you can turn that off).

**Play together with a short code.** One player reads a 10-digit code aloud, and the others type it in. Everyone gets the same puzzle and the same game settings, so you can race or compare notes without accounts or a network connection. A check digit catches mistyped or swapped digits before a wrong puzzle loads.

**A ready screen for a fair start.** Joining a puzzle opens a hidden board, and everyone taps Start on the same count. The host can restart the same puzzle on the ready screen too.

**Settings to make it harder or easier.**
- Game over after 1, 3, or 5 wrong numbers
- Hide how many of each number remain on the number pad
- Turn off highlighting for the row, column, and box, for matching numbers, or for conflicts

**Number-first entry.** Pick a number on the pad, then tap any cells to fill them. It works with pencil mode too, so you can stamp the same candidate across the board quickly.

**A built-in guide to solving techniques.** Twelve techniques run from easiest to hardest, from the last digit in a unit to X-Wing, XY-Wing, and Swordfish. Each has a plain-language "use it when" line, numbered steps, and a diagram. The timer pauses while you read.

**Helpful without taking over.**
- Undo and redo
- Hints that place a correct number
- A Check button that marks incorrect numbers
- A timer with pause
- A mistake counter
- Conflict highlighting for repeated numbers
- A short celebration when you solve it

**Light, dark, or system theme.** Match your device or pick a side. Digits for given clues, your own entries, and pencil marks look clearly different.

**Private and light.** Everything lives in one HTML file with no external libraries, fonts, or network calls. Nothing is collected or sent anywhere.

## How to play

1. Choose a difficulty at the top, or just start with Easy.
2. Tap a cell, then tap a number on the pad. Numbers must appear once in every row, column, and 3 by 3 box.
3. Use Pencil to jot candidate numbers in a cell when you are not sure yet.
4. Stuck? Open the Guide for techniques to try, or use Hint.

### Keyboard shortcuts

| Key | Action |
| --- | --- |
| 1 to 9 | Place a number (or select it in number-first mode) |
| Shift + 1 to 9 | Add or remove a pencil mark |
| Backspace, Delete, or 0 | Erase the selected cell |
| Arrow keys | Move between cells |
| N | Toggle pencil mode |
| H | Hint |
| P | Pause or resume |
| Ctrl or Cmd + Z | Undo |
| Ctrl or Cmd + Shift + Z, or Ctrl or Cmd + Y | Redo |

## Play together

1. Host: open **Play together**. The code shows the puzzle, level, and the shared game settings.
2. Read the code aloud, in groups of three, three, and four digits.
3. Other players: open **Play together**, type the code under **Join a puzzle**, and tap **Start puzzle**.
4. Everyone taps **Start** on the ready screen together. The host can use **Restart and wait for players** to get the same ready screen.

The code carries the puzzle, the level, the game over limit, remaining counts on or off, the three highlight options, and automatic pencil mark removal. Theme and number-first entry stay personal on each device.

## Host your own copy on GitHub Pages

Opening the file directly on an iPhone or iPad won't work, because the Files app preview doesn't run JavaScript. Hosting it as a web page fixes that and gives everyone the same link.

1. Name the game file `index.html`.
2. Create a public repository and upload `index.html` to the top level.
3. Go to **Settings**, then **Pages**. Set Source to **Deploy from a branch**, choose **main** and **/ (root)**, then save.
4. After a minute or two, your game is live at `https://yourusername.github.io/reponame/`.

On a phone, use Share, then **Add to Home Screen** for an app-style icon.

## Good to know

- Progress, settings, and theme reset when you reload the page.
- Play together does not sync live. Each player solves on their own device, and you compare times yourselves.
- Difficulty is graded by solving techniques and clue count. Hard and Expert are separated mainly by clue count.
- The guide diagrams are hand-built examples, not taken from real puzzles.
