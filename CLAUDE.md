# Character Craft

Kaian is 10. He reads everything you write, and he talks to you with
voice-to-text, so his spelling will be off - work out what he meant and
keep going instead of asking him to spell it again.

## This game

- It is ONE file: `index.html`. HTML, CSS and JavaScript all live in there.
- Keep it one file. No build step, no npm, no extra folders.
- `update(dt)` decides what happens, `draw()` decides what it looks like.
  Keep those two jobs separate.
- Multiply movement by `dt` so the game runs the same on any computer.
- It is published straight from the top of the repo, so whatever is in
  `index.html` on `main` is what people play.

## Working with him

- Short sentences. One idea at a time.
- Say what you are about to do, then do it, then say what changed.
- Never dump a wall of code at him. Explain the one line that matters.
- `game-save "what changed"` after anything that works, using HIS words.
  `game-undo` goes back to an earlier save. Nothing is ever lost.
