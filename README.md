# Word Master

## Overview
Word Master is an engaging word game that challenges players to form words using letters from a given "center word." The game combines vocabulary skills with quick thinking as players race against the clock to find as many valid words as possible.

## How to Play

### Game Rules
1. A random "center word" will be displayed, typically 7-9 letters long
2. Form words using the letters in the center word
3. Words must be at least 3 letters long
4. You can use each letter in the center word as many times as it appears
5. Every word must contain the highlighted "required letter"
6. Score points based on the length of each valid word (1 point per letter)
7. Find as many words as possible before the 60-second timer runs out!

### Game Flow
1. Enter your word in the input field
2. Click "Submit" or press Enter to check if your word is valid
3. Valid words will be added to your "Found Words" list and increase your score
4. Continue finding words until time expires
5. After the game ends, view your final score and start a new game

## Features

- **Real-time Validation**: Words are checked against an online dictionary to ensure they are valid English words
- **Required Letter**: Each game features a "required letter" that must be included in every word you submit
- **Word Definitions**: Click the "?" icon next to found words to see their definitions
- **Score Tracking**: Earn points based on word length (longer words are worth more)
- **Time Limit**: 60-second countdown adds excitement and challenge
- **Responsive Design**: Works on desktop and mobile devices

## Technical Details

### Dependencies
- No external libraries required - pure HTML, CSS, and JavaScript
- Uses the Free Dictionary API (https://dictionaryapi.dev/) for word validation and definitions

### File Structure
- Single HTML file containing all code (HTML, CSS, JavaScript)
- Includes a predefined list of 200 possible center words

### Browser Compatibility
- Works with all modern browsers (Chrome, Firefox, Safari, Edge)
- Requires JavaScript to be enabled

## Installation and Setup

1. Download the `wordmaster.html` file
2. Open the file in any modern web browser
3. No additional installation or setup required!

## Customization

### Changing Game Duration
Edit the `timeLeft = 60;` variable in the JavaScript to adjust the game timer.

### Adding More Center Words
Expand the `possibleCenterWords` array in the JavaScript to add additional words.

### Styling
The game uses CSS for styling and can be customized by modifying the CSS rules in the `<style>` section.

## Development Notes

- The game uses asynchronous JavaScript to check word validity
- Word definitions are fetched and stored for later access
- The Free Dictionary API has rate limitations, so excessive usage may be throttled

## Troubleshooting

- **Word not recognized**: The game uses an external dictionary API. Some valid words might not be recognized if they're not in the API's dictionary
- **Slow word validation**: Network issues may cause delays in word validation
- **API errors**: If the dictionary API is unavailable, word validation may fail

## License

This game is provided as open-source software. Feel free to modify and distribute it as needed.

---

Enjoy playing Word Master! Challenge yourself to improve your score with each game.
