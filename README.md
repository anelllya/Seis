# Seis

Mini sudoku, 1 to 6, in the same look as [Picón](https://anelllya.github.io/picon/).

- Three sequences of 100 levels: easy, medium and hard, each ordered easiest first
- Graded by the logic a level needs, not just clue count: easy falls to scanning alone, medium needs candidates, hard needs pointing pairs or subsets
- Every puzzle is checked to have exactly one solution
- Past level 100 each sequence keeps going with reshuffled grids of the same grade
- Notes, unlimited undo, clash highlighting, a clock, and a saved game per sequence you can resume
- Keyboard: 1 to 6, arrows, N for notes, Z for undo, Backspace to erase
- Progress is saved in the browser

Plain `index.html` + `styles.css` + `app.js`, no build step. Served with GitHub Pages.
