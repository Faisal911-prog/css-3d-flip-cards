# Scorch & Sons – CSS 3D clickable flip cards

Internship Task 1: my own version of the CSS 3D clickable flip cards, used to advertise a (fictional) small-batch hot sauce brand.

**Live site:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

## How it works
- Each card has a hidden checkbox. Clicking the "Details" label ticks it, and `:checked ~ .content` rotates the card 180° with `transform: rotateY(180deg)`.
- `perspective` on the card and `transform-style: preserve-3d` on the content give the 3D depth.
- `backface-visibility: hidden` hides whichever side faces away, so the back side shows up after the flip.
- The bottles are drawn with CSS only, no images needed.

## Files
- `index.html` – structure
- `style.css` – styling
