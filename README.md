# SCORECARD

# React Scoreboard Application

This is a simple React-based scoreboard application for a cricket game. The project tracks the score, wickets, and ball-to-ball commentary with a user-friendly interface using React and JSX. The application is directly rendered in the browser using React's UMD bundle and Babel for JSX support.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Components](#components)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project provides a basic score-tracking system for a cricket match. You can input runs scored, track wickets, and add comments for each ball. The application displays the total score, number of wickets, and keeps a detailed record of every ball bowled, including "overs" after every 6 balls.

## Technologies Used
- **HTML**
- **React (via CDN)**
- **ReactDOM (via CDN)**
- **Babel (for JSX support via CDN)**

## Features
- **Score Tracking**: Update the score by selecting runs scored on each ball.
- **Wicket Count**: Track the number of wickets lost.
- **Ball Commentary**: Add comments for each ball, which will be displayed in a list.
- **Over Display**: Automatically adds a label for each over after 6 balls.

## Setup
To run the application, simply create an `index.html` file with the code provided above. No server or build tools are required because it uses CDN links for React and Babel.

1. **Copy the code above into an HTML file** (e.g., `index.html`).
2. **Open the file in a web browser** to run the scoreboard application.

## Usage
1. **Run the application** by opening `index.html` in a browser.
2. **Use the score buttons** to add runs or mark a wicket.
3. **Enter comments** for each ball using the input field and click `SUBMIT`.
4. **View the result** in the results section which shows the ball-by-ball data, including overs.

## Components

### 1. **ScoreButtons**
   - A set of buttons that allow the user to select the score for each ball.
   - Buttons include runs (0 to 6), wide, no-ball, and wicket.

### 2. **Form**
   - A form component with an input field to add a comment for the selected score.
   - Contains a `SUBMIT` button to finalize the input.

### 3. **Result**
   - Displays the ball-by-ball results.
   - Shows a line labeled "OVER" after every 6 balls.

### 4. **App**
   - The main component that renders the entire scoreboard interface, including the score, buttons, form, and results.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

1. **Fork the repository**
2. **Create a new branch** (`git checkout -b feature-branch`)
3. **Commit your changes** (`git commit -m 'Add a new feature'`)
4. **Push to the branch** (`git push origin feature-branch`)
5. **Create a Pull Request**

## License
This project is open-source and available under the MIT License.

