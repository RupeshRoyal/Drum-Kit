# Drum-Kit

The code sets up the basic structure and content of the Drum Kit web application. The associated CSS and JavaScript files linked to provide styling and interactivity to the Drum Kit.

Here is a summary of the code snippets provided:

-->CSS Styling:

The CSS code sets various styles for the HTML elements, including text alignment, background colors, font sizes, font families, shadows, and more. It also defines styles for specific classes such as .drum, .set, .game-over, .pressed, and .gradient-animation, which are used to style elements accordingly.

-->HTML Structure:

The HTML code represents the structure of a web page for a Drum Kit application. It includes a heading (<h1>), drum buttons (<button>), a set container (<div class="set">), and a footer (<footer>).

-->JavaScript Logic:

The JavaScript code performs the following operations:
Retrieves the number of drum buttons on the page.
Sets up event listeners for both button clicks and keypress events.
Calls the makeSound() and buttonAnimation() functions when a button is clicked or a key is pressed.
The makeSound() function plays an audio file based on the button/key pressed.
The buttonAnimation() function adds and removes a "pressed" class to create a button animation effect.

These snippets collectively create a Drum Kit web application that allows users to play different sounds by clicking on drum buttons or pressing corresponding keys on the keyboard.
