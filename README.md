# Hangman Game

The Hangman Game is a classic word guessing game where the player tries to guess a hidden word by suggesting letters. The player has a limited number of attempts to guess the word correctly before losing the game.

This project implements the Hangman Game as a web application using Flask, HTML, CSS, and JavaScript. It allows users to play the game in their web browser.

# Deployed game link 
http://hangmman.pythonanywhere.com/

# Connect with us on
www.linkedin.com/in/glory-ogbondah 
https://www.linkedin.com/in/solomon-addo-antiri-1015b8238/

Read more on https://medium.com/@glory.ogbondah/9a9c9e42b842?source=friends_link&sk=297897665562cd95da74bde983595db7

# Collaborators
# Glory Ada Ogbondah: Backend developer
I am a backend developer as at the time of this publishing, an ALXSE student, I am an enthusiastic and motivated individual eager to learn and grow in the field of backend development. I have a solid foundation in programming concepts and a strong desire to gain practical experience in designing and building server-side applications. I am continuously expanding my knowledge of backend technologies, frameworks, and best practices, and I am dedicated to honing my skills in areas such as API development, database management, and system integration. With a passion for problem-solving and a commitment to delivering efficient and reliable solutions, I am excited to contribute to backend development projects and further enhance my abilities in this dynamic field.
# Solomon Addo Antiri: Frontend Developer

## Features

- Randomly selects a word from a predefined word list.
- Displays the word as a series of underscores representing the letters to be guessed.
- Allows the player to submit letter guesses.
- Tracks the number of remaining lives.
- Provides feedback on whether the guess is correct or incorrect.
- Updates the display to reveal correctly guessed letters.
- Displays a hangman image that changes as incorrect guesses are made.
- Notifies the player when they win or lose the game.
- Allows the player to restart the game.

## Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript

## Getting Started

To run the Hangman Game locally on your machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start the Flask development server:

   ```bash
   python flask_app.py
   ```

4. Open your web browser and visit `http://localhost:5000` to play the game.

## Project Structure

The project directory contains the following files:

- `flask_app.py`: The Flask application file that defines the routes and game logic.
- `hangman_words.py`: A Python module that provides a list of words for the game.
- `hangman_art.py`: A Python module that defines ASCII art for the hangman image.
- `templates/index.html`: The HTML template file for the game interface.
- `static/styles.css`: The CSS file for styling the game interface.
- `static/main.js`: The JavaScript file for handling game interactions.

## Contributing

Contributions to the Hangman Game project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

The Hangman Game project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This project is inspired by the classic Hangman game and is developed as a learning exercise.

- ASCII art hangman images adapted from [ASCII Art Archive](http://www.asciiartfarts.com/hangman.html).

## Conclusion

The Hangman Game project provides an interactive and entertaining way to play the classic word guessing game in a web browser. It demonstrates the use of Flask, HTML, CSS, and JavaScript to create a dynamic and responsive user interface. Enjoy playing and have fun guessing the words!
