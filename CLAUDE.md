# ALL-STAR ANYWHERE

A cross-sport arcade game designed by **Colson**. Colson is a kid — keep all
content kid-appropriate: no profanity, violence beyond cartoon slapstick,
innuendo, or dark themes, in code, copy, character designs, or commit messages.

## The two universes

The game world is built on two deliberately separated universes:

- **Real League** — fictional pro athletes (football, basketball, golf) whose
  real-world skills translate into grounded stats. No powers, no magic —
  this universe stays believable.
- **Legends** — original characters with arcade power moves (activated with X).
  These are all original creations. **Never use copyrighted characters** or
  thinly-disguised versions of existing IP (no Mario-likes, no renamed
  superheroes, no real athletes' names or likenesses).

Keep the universes distinct in tone and visuals. They only mix where the game
intentionally mixes them:

- **Crossover Cup** — unlocked by winning a game in each universe; both pools
  draft from one shared list.
- **Season Mode** — a 4-game schedule across hockey, basketball, soccer, and
  football, with playoffs and championship banners.

## Tech

- **Single file**: the entire game lives in `index.html` — markup, CSS, and
  vanilla JavaScript rendering to an HTML5 canvas.
- **No build step, no dependencies, no frameworks.** Don't introduce npm,
  bundlers, or external libraries. Open `index.html` in a browser to run it.
- Audio is synthesized with the Web Audio API (no audio files). Progress is
  saved with localStorage. Touch and keyboard controls are both supported.

## Design decisions

**Colson is the design owner.** When a design question comes up — new
characters, abilities, balance changes, modes, visual style, names, rules —
ask Colson rather than assuming. Implement what's asked; propose ideas as
questions, not as silent changes.
