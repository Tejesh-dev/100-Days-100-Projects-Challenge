# Day 40: Number Guessing Game
Welcome to my 100 Days of Projects challenge! This is my project for Day 40: a classic, interactive Number Guessing Game.

# This project was built to demonstrate and solidify several foundational JavaScript concepts. It's a simple, yet powerful, example of how to build a dynamic web application using vanilla HTML, CSS, and JavaScript.

🧠 Core JavaScript Concepts
This project is more than just a game; it's a practical guide to the following essential JavaScript concepts:

DOM Manipulation: The "Document Object Model" is the interface that allows JavaScript to interact with the HTML structure. In this game, we use DOM manipulation to:

Get a reference to HTML elements: document.getElementById()

Update the content of those elements: element.textContent = "New Message"

Change element visibility and style: element.style.color, classList.add('hidden')

Purpose: This is how we make our game "alive," displaying hints, updating the score, and showing the final result directly on the page.

Event Handling: This concept allows our code to respond to user actions. The game relies on event listeners to:

Detect a click on the "Submit Guess" button: submitBtn.addEventListener('click', checkGuess)

Detect when the user presses the "Enter" key in the input field: guessInput.addEventListener('keypress', ...)

Purpose: Event handling is the bridge between the user and our application's logic. Without it, the game would be static and unresponsive.

Conditional Logic: The game's core logic is powered by if/else if/else statements. These conditions allow us to:

Compare the user's guess with the secret number.

Determine if the guess is "Too High," "Too Low," or correct.

Change the game state and display a different message based on the outcome.

Purpose: This is the "brain" of the game, enabling it to make decisions and provide meaningful feedback.

Randomization: To ensure every game is unique, we use JavaScript's Math object to generate a random number.

Math.random() generates a floating-point number between 0 and 1.

We scale and round this number to get a whole number within our desired range (1 to 100).

Purpose: Randomization is what makes the game challenging and replayable.

**Functions:** We've organized our code into reusable functions like newGame(), checkGuess(), and endGame().

**Purpose:** This modular approach keeps the code clean, readable, and easy to maintain. Each function has a single responsibility, which is a key principle of good software design.

