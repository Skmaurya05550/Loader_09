# CSS Loader Animation

This project demonstrates a square animation loader built using HTML and CSS. The loader consists of multiple square divs that move around a defined path, creating a seamless looping animation.

## Features

- Pure CSS animation
- Responsive design
- Infinite looping with smooth transitions
- Customizable speed and color

## Demo

The loader animation consists of 7 squares, each animated in sequence to follow a predefined square path. You can view it in action by opening the `index.html` file in a browser.

## How to Use

1. Clone this repository or download the zip file.
2. Open the `index.html` file in your browser to see the loader in action.
3. To customize the loader:
    - Edit the `@keyframes square-animation` section to modify the animation behavior.
    - Change the `background` property in `.loader-square` to set a different color for the squares.
    - Adjust the `animation` property to change the speed of the animation.

## Keyframes

The animation follows a specific set of keyframes:

- The squares move in a square path, starting at the top-left and looping through each corner.
- The animation runs over a duration of 10 seconds for each square, with delays to ensure a staggered effect.
- The animation is set to repeat infinitely.

## Customization

- **Color:** You can change the color of the squares by modifying the `background` property in the `.loader-square` class.
- **Speed:** Modify the `animation` duration in the `.loader-square` class to increase or decrease the animation speed.
- **Size:** Adjust the `width` and `height` properties in both the `.loader` and `.loader-square` classes to change the size of the loader.

## License

This project is open-source and available under the [MIT License](LICENSE).



