# Password Generator

A simple password generator built with React and Tailwind CSS. This application allows users to generate random passwords based on specified criteria: length, inclusion of numbers, and inclusion of special characters. Users can easily copy the generated password to their clipboard.

## Features

* **Customizable Length:** Set the desired password length using a slider.
* **Include Numbers:** Option to include numerical digits in the password.
* **Include Special Characters:** Option to include special symbols in the password.
* **Instant Generation:** Passwords are automatically generated as you adjust the settings.
* **Copy to Clipboard:** Easily copy the generated password with a single click.


## Technologies Used

* **React:** A JavaScript library for building user interfaces.
* **Tailwind CSS:** A utility-first CSS framework for rapid UI development.
* **`useRef` Hook:** Used for direct DOM manipulation (e.g., selecting the password input for copying).
* **`useCallback` Hook:** Optimizes performance by memoizing functions.
* **`useEffect` Hook:** Manages side effects, such as generating the password when dependencies change.

