# Scaleminator

An interactive guitar fretboard that shows where every note of a scale falls on the neck. Pick a root, a scale and a tuning, then highlight the notes you want to focus on.

It's a single HTML file with no build step and no dependencies: open `scales.html` in a browser and play.

## Features

- **97 scales, each with unique intervals.** No duplicates under different names. They're grouped into small families so the menu stays easy to browse:
  - Pentatonic (Common, Japanese, Indian, Other)
  - Blues & bebop
  - Diatonic modes, harmonic minor modes, melodic minor modes
  - Harmonic major modes, double harmonic modes
  - Hexatonic, symmetric, synthetic & Messiaen
  - European & Mediterranean, Indian & Middle Eastern
- **Every root key**, from A to G#.
- **21 tunings**, with E standard as the default:
  - Standard: E, Eb, D, C#, C, B and A
  - Drop: Drop D, C#, C, B and A
  - Open: Open G, D, E, C and A
  - Other: DADGAD, double drop D, all fourths and new standard
- **Custom tunings:** each string's letter is a dropdown, so you can change the open note of any string. If the result matches a known tuning, it takes that tuning's name.
- **24-fret neck** with open strings, fret numbers, and inlay dots both on the wood and below it.
- **Fret range picker:** show any part of the neck, from 0–24 down to a single fret.
- **Three states for each scale note.** Click a note to cycle through them:
  - **Focused:** highlighted in colour. The root is always red. Other notes take colours from a stack (yellow, pink, green, orange, purple, grey, brown) in the order you focus them. Unfocusing a note frees its colour.
  - **Showing:** a plain dark note.
  - **Hidden:** the note is removed from the neck.
- **Blue notes:** the optional ♭5 (minor pentatonic) and ♭3 (major pentatonic) can be switched on and show in blue.
- **Night mode.**
- **Responsive layout:**
  - On large screens the full 24-fret neck is shown.
  - On smaller screens and phones, a compact mode shows up to 12 frets at a time without horizontal scrolling. The controls move into a side drawer.

## Usage

1. Clone or download the repository.
2. Open `scales.html` in any modern browser.

No server or installation needed. Fonts are loaded from Google Fonts. Without a connection the page still works, using fallback fonts.

## Built with

Plain HTML, CSS and JavaScript.
