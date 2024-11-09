# Card Swap with Rotation and Hidden Cards Reveal

An interactive **Card Swap** feature built with HTML, CSS, and JavaScript. This project allows users to swap cards with a rotation effect, and when hovering over each card, it reveals additional smaller, hidden cards for a unique visual experience.

## Features

- **Rotation on Next**: Each card rotates on click to display the next card in the sequence.
- **Hover Reveal**: Hovering over each main card reveals smaller hidden cards for a layered effect.
- **Smooth Animations**: CSS transitions for rotation and hover animations create a polished interaction.
- **Responsive Design**: Designed to work on both desktop and mobile devices.


## Technologies Used

- **HTML**: Structure and layout of the main and hidden cards.
- **CSS**: Styling, animations, and hover effects for card rotation and reveal.
- **JavaScript**: Logic for handling the rotation and "next" button functionality.

## Setup and Usage

1. **Clone the repository:**

    ```bash
    git clone https://github.com/deshanFdo/card-swap.git
    cd card-swap-rotation
    ```

2. **Open the Project**:

   Open the `index.html` file in a web browser to view and test the card swap functionality.

## File Structure

- **`index.html`**: Contains the structure for the card container, main cards, and hidden cards.
- **`styles.css`**: Includes styling for the layout, card design, rotation animations, and hover effects.
- **`script.js`**: JavaScript file managing the card rotation and "next" functionality.

## Code Overview

- **HTML**:
  - Each main card has nested hidden cards that become visible on hover.

- **CSS**:
  - Styling for the main card layout, hidden cards, and animations for smooth rotation and hover reveal.

- **JavaScript** (`script.js`):
  - **Rotation Logic**: Each click on a "next" button rotates the card to show the next item in the sequence.
  - **Hover Reveal**: JavaScript may add or modify classes to trigger the reveal effect on hover.
