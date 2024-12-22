# Live Closed Captions

This project provides a web-based live captioning tool that utilizes speech recognition to transcribe spoken language into text in real-time. The interface is designed to be user-friendly, with customizable settings for language selection, font size, and text alignment.

## Features

- **Real-Time Speech Recognition**: Captions are generated in real-time using the browser's speech recognition capabilities.
- **Language Selection**: Choose from a wide range of languages and dialects.
- **Customizable Interface**: Adjust font size and text alignment to suit your preferences.
- **Persistent Settings**: User preferences for language, font size, and alignment are saved in local storage for a personalized experience.

## Usage

1. **Open the HTML File**: Simply open the `LCC.html` file in a modern web browser that supports speech recognition (e.g., Google Chrome).
2. **Start Captions**: The application will automatically start listening and displaying captions.
3. **Customize Settings**:
   - Press the **Spacebar** to switch between selected languages.
   - Use the **+** and **-** keys to increase or decrease the font size.
   - Press **M** to toggle the language selection menu.
   - Use the buttons in the menu to align text (left, center, right, top, middle, bottom).

## Customization

- **Languages**: Modify the `languages` array in the script to add or remove languages.
- **Font Size**: Adjust the default font size by changing the `fontSize` variable.
- **Text Alignment**: Set default text alignment by modifying the `horizontalAlignment` and `verticalAlignment` variables.

## Requirements

- A modern web browser with support for the Web Speech API (e.g., Google Chrome).

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## Acknowledgments

- This project uses the Web Speech API for speech recognition.
- Made with love ❤️ by David.
