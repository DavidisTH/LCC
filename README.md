# Live Closed Captions

This project provides a web-based `live captioning` tool (based on the `Web Speech API`) that utilizes `speech recognition` to transcribe spoken language into text in real-time. The interface is designed to be user-friendly, with customizable settings for `language selection`, `font size`, `text alignment`, `caption colors`, and `real-time translation capabilities`.

## Features
- **Real-Time Speech Recognition**: Captions are generated in real-time using the browser's `speech recognition` capabilities.
- **Language Selection**: Choose from a wide range of `languages` and `dialects`.
- **Real-Time Translation**: Toggle live translation of captions to your preferred language using the `unofficial Google Translate API`.
- **Customizable Interface**: 
  - Adjust `font size`, `text alignment`, and `caption colors`.
  - Separate color settings for original captions and translations.
  - Display both `language name` and `code` (e.g., `Slovak (sk-SK)`) for better clarity.
- **Persistent Settings**: User preferences for `language`, `font size`, `alignment`, `colors`, and `translation settings` are saved in local storage.
- **Dual Caption Display**: View both original speech and translated text simultaneously when translation is enabled.

## Usage
1. Open the HTML File: Simply open the `LCC.html` (or the webpage https://davidisth.github.io/LCC/LCC.html) file in a modern web browser that supports `speech recognition` (e.g., `Google Chrome`) (see specifications here: `Web Speech API`).
2. Start Captions: The application will automatically start listening and displaying captions.
3. Customize Settings:
   - Press the `Spacebar` to switch between selected languages.
   - Use the `+` and `-` keys to increase or decrease the font size.
   - Press `M` to toggle the language selection menu.
   - Press `C` to change the original caption color.
   - Press `T` to toggle translation mode.
   - Press `X` to change the translated caption color.
   - Use the buttons in the menu to align text (left, center, right, top, middle, bottom).

## Customization
- Languages: Modify the `languages` array in the script to add or remove languages.
- Font Size: Adjust the default `font size` by changing the `fontSize` variable.
- Text Alignment: Set default `text alignment` by modifying the `horizontalAlignment` and `verticalAlignment` variables.
- Caption Colors: Change the default `caption colors` by modifying the `captionColors` array.
- Translation Settings: Configure default `translation language` and delay timing.

## Requirements
- A modern web browser with support for the `Web Speech API` (e.g., `Google Chrome`).
- Internet connection for translation features.

## License
This project is open-source and available under the `MIT License`.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## Acknowledgments
- This project uses the `Web Speech API` for speech recognition.
- Translation powered by the `unofficial Google Translate API`.

## Future Improvements
- To add an option to automatically recognize spoken language when 'D' key is pressed (Unofficial Google Speech engine ???). This would be super perfect.
- Enhance translation stability and performance.
- Add support for more translation services.

Made with love ❤️ for those who need it.
