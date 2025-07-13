# **AI-Powered Nonogram Game**

This is a web-based Nonogram puzzle game with a unique feature: it uses the Google Gemini AI to generate new, unique, and solvable puzzles on demand.

## **How to Play**

Nonograms are picture logic puzzles where you color cells in a grid based on numbers at the side of the grid to reveal a hidden picture.

1. **Understand the Clues**: The numbers next to each row and at the top of each column describe the "runs" of black squares in that line. For example, a clue of 2 3 means there is a run of exactly two black squares, followed by at least one white square, followed by a run of exactly three black squares.
2. **Fill the Grid**: Use your mouse or finger to fill in the grid.
   * **Fill Black**: The default mode. Click on a cell to color it black.
   * **Mark White (X)**: Use the "Click Mode" dropdown to switch to this mode. This allows you to mark cells with an 'X' to indicate you are certain they are white, which helps with solving.
   * You can **click and drag** to fill multiple cells at once.
3. **Check Your Solution**: When you think you've completed the puzzle, click the **Check** button.

## **AI Puzzle Generation**

The most exciting feature of this app is its ability to create endless new puzzles.

* **Generate with AI**: Click this button to have the Gemini AI design a new puzzle.
* **Inspiration Word**: The AI is given a random word (e.g., "Rocket", "Cat", "House") and instructed to create a recognizable image based on it. The inspiration word is shown above the puzzle.
* **Choose a Size**: Use the dropdown next to the generation button to select a puzzle size: 5x5 (easy), 10x10 (medium), or 15x15 (hard).

## **API Key Setup**

The AI generation is powered by the Google AI API. To run this app on your own website or computer, you will need a free API key from Google.

1. Visit [Google AI Studio](https://aistudio.google.com/app/apikey) to generate your free API key.
2. Copy the key.
3. In the app, paste the key into the **Google AI API Key** input field.
4. Click **Save**. The key will be saved in your browser's local storage, so you only need to do this once per browser.

## **Credits**

* Created by **Lars Brünjes** (brunjlar@gmail.com)
* AI functionality and development assistance by Google Gemini.
