# Typing Test

A simple web-based typing test built with vanilla JavaScript, HTML, and CSS.

## Features

- Random word selection for each test
- Real-time feedback on correct/incorrect letters
- Visual caret and word marking
- Keyboard-only navigation

## Getting Started

1. **Clone or Download the Repository**

2. **Add a `data.js` file**  
   Make sure you have a `data.js` file in the project root exporting a `words` array, e.g.:

   ```js
   // data.js
   export const words = ["example", "words", "for", "typing", "test", ...];
   ```

3. **Open `index.html` in your browser**

## Usage

- Start typing the displayed words.
- Correct letters are highlighted in green, incorrect in red.
- Press `Space` to move to the next word.
- The test restarts after the last word.

## Customization

- Edit the `words` array in `data.js` to change the word pool.
- Adjust styles in the `<style>` section of `index.html`.

## License

MIT
