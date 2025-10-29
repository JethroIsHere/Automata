# The Alchemist’s Assistant

A lightweight Turing Machine–powered crafting simulator with an accompanying slide deck for presentations. Built with plain HTML/CSS/JS (Tailwind via CDN) and the Web Audio API.

## Project structure

- `index.html` — Interactive app (TM tape visualization, beginner guide, compendium, crafting flow)
- `slides.html` — Slide deck (glowing rune background, fragment reveals, music/SFX, navigation)

## Quick start

No build is required.

- Double‑click `slides.html` to open the presentation.
- Double‑click `index.html` to open the app.

Tip: Some browsers block audio until your first click/interaction. If you don’t hear SFX/music, click anywhere or use a button once.

## Slide deck controls

- Next: Right Arrow →, PageDown, or Space
- Previous: Left Arrow ←, PageUp, or Shift+Space
- First/Last: Home / End
- Fullscreen: F
- Toggle glowing runes: G
- Toggle music: M (also has an on/off and volume UI)
- Open app: O (or click the “Open App ↗” button)

## App controls

- Open slides: O (or click the “Open Slides ↗” button in the header)
- Use the built‑in buttons for crafting, saving/loading, and opening the Beginner Guide/Compendium.

## Notes

- Audio: Web Audio is used for fragment pop SFX and a subtle musical pad on slides. Volume and music on/off controls are available in the deck.
- Accessibility: Animations are designed to be lightweight. If your OS/browser prefers reduced motion, some effects may be softened.
- Best experience: Present from `slides.html`, and switch to `index.html` for live demos using the provided buttons/shortcuts.

## Contributing

This is a simple static project. PRs and issues are welcome.

## License

MIT
