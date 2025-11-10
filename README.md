-----

## ⏰ Digital Clock

A simple, functional digital clock application built using **HTML, CSS, and vanilla JavaScript**. This project displays the current time (hours, minutes, and seconds) and updates every second. It's an excellent project for practicing basic front-end development, specifically DOM manipulation and the use of the JavaScript `setInterval()` function.

### ✨ Features

  * **Real-Time Display:** The clock updates every second to show the current system time.
  * **Time Components:** Displays Hours, Minutes, and Seconds separately.
  * **Formatting:** Uses leading zeros for single-digit hours, minutes, and seconds (e.g., `09:05:01`).
  * **Modern UI:** Features a sleek design with a gradient background (`linear-gradient(to right, #0f0d18 0%, black 100%)`) and distinct labels for each time component.
  * **Component Labels:** Labels "HOURS", "MINUTES", and "SECONDS" are displayed below the respective time values using CSS pseudo-elements (`::after`).

-----

### 🛠️ Technology Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Structure of the clock container and display spans (`<span id="hrs">`, `min`, `sec`). |
| **CSS3** | Styling, gradient background, centering the clock, and adding labels using `::after`. |
| **Vanilla JavaScript** | Core application logic using `new Date()` to get the current time and `setInterval()` to update the display every 1000 milliseconds (1 second). |

-----

### 🚀 Getting Started

To run this digital clock locally, you only need a web browser.

#### Prerequisites

  * A modern web browser (Chrome, Firefox, Edge, Safari, etc.)

#### Installation and Execution

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/arjundipunath/clock.git
    ```
2.  **Navigate to the Project Directory:**
    ```bash
    cd clock
    ```
3.  **Open the File:**
    Double-click the **`index.html`** file, or right-click it and select "Open with" your preferred web browser.

The digital clock should immediately load and begin displaying the current time.

-----

### 💻 Code Logic Highlights

  * **HTML Structure (`index.html`)**: The time is displayed within a `div` with class `clock`, and individual `span` elements hold the hours, minutes, and seconds.
  * **CSS Styling (`style.css`)**: The `.hero` container uses a black-to-black gradient background. The `.container` is centered and given a shadow, while `.clock span::after` is used to create the text labels ("HOURS", "MINUTES", "SECONDS") below the numbers.
  * **JavaScript Logic (Embedded in `index.html`)**:
      * The `setInterval` function executes the update logic every 1000ms.
      * `new Date()` retrieves the current time.
      * The ternary operator `(cutime.getHours() < 10 ? "0" : "")` is used to prepend a zero if the hour, minute, or second is a single digit, ensuring uniform display.

-----

### ✍️ Author

  * **Arjun Dipunath** - (You can add your GitHub profile link here)

-----

