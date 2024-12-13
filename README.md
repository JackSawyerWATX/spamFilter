# Spam Filter

A responsive web application that analyzes a given message and determines whether it is likely to be 
flagged as spam. This project uses JavaScript for spam detection logic and Bootstrap for styling and 
responsiveness.

---

## Features

- **Spam Detection:** 
  - Detects messages containing:
    - Requests like "please help" or "assist me"
    - Monetary mentions such as "100 dollars" or "million dollars"
    - Phrases like "free money" and leetspeak variations (e.g., "fr33 m0n3y")
    - Alerts like "stock alert" or "st0ck al3rt"
    - Greeting patterns such as "dear friend" or "de4r fr13nd"
- **Responsive Design:** 
  - Styled using Bootstrap for consistent and visually appealing UI components.
- **Dynamic Feedback:**
  - Provides real-time analysis of input messages and displays results.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spam-filter.git

    Navigate to the project directory:

    cd spam-filter

    Open the index.html file in your preferred web browser.

## Usage

    Open the project in your browser.
    Enter a phrase or message into the provided text area.
    Click the "Check Message" button.
    View the results displayed below the button:
        Spam: If the message matches any of the predefined spam patterns.
        Not Spam: If the message does not match any spam patterns.

## File Structure

spam-filter/
├── index.html       # Main HTML file
├── script.js        # JavaScript file for spam detection logic
└── README.md        # Project documentation

## Spam Patterns

## Technologies Used

    HTML: Structure of the web application.
    Bootstrap: For responsive and consistent UI styling.
    JavaScript: Core logic for spam detection using regex patterns.

## License

This project is licensed under the MIT License. You are free to use and modify it.
Author

### Developed by Jonathan Fausset

    Website: jonathanfausset.com
    GitHub: github.com/jacksawyerwatx


This updated `README.md` reflects the spam patterns, Bootstrap usage, and the functionality defined 
in your JavaScript code. You can further customize it if necessary.

