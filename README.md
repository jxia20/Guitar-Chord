# Extended Guitar Chord Visualizer & Chord Transition Practicer

This project consists of two HTML pages designed to help guitar players improve their chord knowledge and transitions.

- **Extended Guitar Chord Visualizer (index.html):**  
  View and explore an extended chord library that includes major, minor, dominant 7th, minor 7th, diminished, augmented, and other chord types. Use the dropdown and voicing navigation buttons to see different chord diagrams rendered as SVG.

- **Chord Transition Practicer (transition.html):**  
  Practice rapid chord transitions by switching between two randomly chosen chords. This page displays each chord’s diagram along with its name, and provides a 30‑second timer during which you alternate between the two chords. You can pause/resume the timer and skip to a new pair at any time.

## Features

- **SVG Chord Diagrams:**  
  Each chord is rendered as an SVG diagram showing finger positions, open/muted string markers, and fret numbers.
  
- **Extended Chord Library:**  
  The project includes various chord types (Major, Minor, Dominant 7th, Minor 7th, Diminished, Augmented, Major 7th, Half-diminished) with multiple voicings for many chords.

- **Practice Mode:**  
  The Chord Transition Practicer randomly selects a pair of chords, displays their diagrams and names, and challenges you to alternate between them for 30 seconds.

- **Simple Navigation:**  
  A navigation bar on every page allows you to switch easily between the Chord Visualizer and the Chord Transition Practicer.

## How to Run

1. **Download or Clone the Repository:**  
   Place all files in a folder on your computer.

2. **Run Locally:**  
   Open `index.html` or `transition.html` in your browser, or start a local server (e.g., with Python: `python -m http.server 8000`) and navigate to the file in your browser.

3. **Navigation:**  
   Use the navigation bar at the top of each page to switch between the Chord Visualizer and the Chord Transition Practicer.

## Customization

- **Chord Library:**  
  Modify the chord definitions in the `chords` object inside each HTML file to add, remove, or change chord shapes and voicings.

- **SVG Drawing:**  
  Adjust margins, fret counts, or styles in the JavaScript drawing functions to customize the chord diagrams.

- **Practice Timer:**  
  The practice round duration is set to 30 seconds by default. Change the `timeLeft` variable in `transition.html` if you need a different duration.

## License

This project is open source under the MIT License. Feel free to modify and distribute it according to the license terms.