# Random Movie Quotes

A simple interactive webpage that displays a random iconic movie quote whenever the user clicks the **"Say The Line!"** button.

This project was created as a weekly programming assignment to practice JavaScript, JSON, and working with external files.

## Features

- Displays randomly selected movie quotes.
- Loads quotes from an external JSON file.
- Updates the displayed quote without refreshing the page.
- Simple cinema-inspired design with a dark background and red button.

## Technologies Used

- **HTML5:** Page structure and content.
- **CSS3:** Styling and layout.
- **JavaScript:** Button interactions and random quote selection.
- **JSON:** Stores the collection of movie quotes.

## How It Works

1. JavaScript uses `fetch()` to load `movie-quotes.json`.
2. `response.json()` converts the JSON response into JavaScript data.
3. The quotes are stored in an array.
4. Clicking **"Say The Line!"** generates a random array index using `Math.random()` and `Math.floor()`.
5. The selected quote appears underneath the button.

## How to Run

1. Download or clone the repository.
2. Open the project folder in Visual Studio Code.
3. Run `index.html` using a local server, such as the Live Server extension.
4. Click **"Say The Line!"** to generate a random movie quote.

## Project Structure

```text
movie-quotes/
├── index.html
├── movie-quotes.json
└── README.md
```

## Learning Objectives

- Understand JSON objects and arrays.
- Fetch and parse external JSON files.
- Practice asynchronous JavaScript with `async` and `await`.
- Generate random array indices.
- Use DOM manipulation and event listeners.
- Debug JavaScript using the browser console.

## Future Improvements

- Display the movie title alongside each quote.
- Add a button to copy quotes.
- Prevent the same quote from appearing twice in a row.
- Add subtle animations when quotes change.

## Project Status

Completed as a weekly JavaScript and JSON programming exercise.
