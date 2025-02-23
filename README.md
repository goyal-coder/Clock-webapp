# Digital Clock with Blur Effect

## Description
This is a simple digital clock implemented using HTML, CSS, and JavaScript. It displays the current time and updates every second. The background of the clock has a blur effect to enhance readability while maintaining the aesthetics of the background image.

## Features
- Displays the current time in `HH:MM:SS` format.
- Updates automatically every second.
- Background image with a full-screen cover effect.
- Semi-transparent clock with a blur effect.
- Responsive design to adjust to different screen sizes.

## Technologies Used
- **HTML**: Structure of the webpage.
- **CSS**: Styling, including background image, blur effect, and layout.
- **JavaScript**: Updates the clock dynamically every second.

## Installation & Usage
1. Download or clone the repository.
2. Place a background image named `bg.jpeg` in the same directory as the HTML file.
3. Open the `index.html` file in any modern web browser.

## Code Breakdown
- **HTML**: Defines the clock container and clock display.
- **CSS**:
  - Sets the background image to cover the entire viewport.
  - Uses `backdrop-filter: blur(25px);` for the blur effect.
  - Centers the clock on the page.
- **JavaScript**:
  - Fetches the current time.
  - Formats the time to always show two digits.
  - Updates the clock every second using `setInterval`.

## Future Enhancements
- Add an option to toggle between 12-hour and 24-hour formats.
- Provide a settings menu for customization (background, font, colors).
- Include an option to display the date alongside the time.

## License
This project is open-source and free to use under the MIT License.
