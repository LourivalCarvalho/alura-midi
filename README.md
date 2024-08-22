# Alura MIDI 🎵

## Overview 🎹

This project is a simple web-based drum machine created using HTML, CSS, and JavaScript. It allows users to play different drum sounds by clicking on buttons or pressing specific keys on the keyboard.

## Project Structure 📂

- **`index.html`**: The main HTML file that contains the structure of the web page, including buttons for drum sounds and audio elements.
- **`main.js`**: The JavaScript file that handles the interaction between the user and the drum sounds.
- **`css/reset.css`**: A CSS file to reset default browser styles.
- **`css/estilos.css`**: A CSS file for custom styling of the drum machine.

## How It Works 🚀

### HTML 📝

The `index.html` file sets up the layout of the drum machine:
- Nine buttons are used to trigger different drum sounds.
- Nine `<audio>` elements are linked to these buttons, each containing a different sound file.

### JavaScript 🔧

The `main.js` file adds interactivity:
- **`tocaSom(seletorAudio)`**: This function plays the sound associated with the provided audio element selector.
- **Button Clicks**: Each button has an `onclick` event that plays the corresponding drum sound.
- **Keyboard Interaction**: Buttons can also be activated using the Space or Enter keys. When pressed, the button's visual state changes to indicate it is active. The visual state is reset when the key is released.

## Getting Started 🏁

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/alura-midi.git
    ```

2. Open `index.html` in your web browser.

3. Click on the buttons or press Space/Enter keys to play drum sounds!

## Notes 📝

- Make sure all sound files are correctly placed in the `sounds` directory.
- Customize the CSS in `estilos.css` to change the appearance of the drum machine.

## Contributing 🤝

Feel free to open issues or submit pull requests to enhance this project. Contributions are welcome!

## Acknowledgements 🙌

Thanks to Alura.

---

Enjoy making music with Alura MIDI! 🎶