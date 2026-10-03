# Cyteoqz games: privacy policies

Static privacy policy pages for Cyteoqz's games, served by GitHub Pages at
https://senglaypann.github.io/games-privacy-policy/

Plain HTML and CSS. No build step, no JavaScript, no cookies, no analytics, nothing loaded from another site
(each page sets a Content-Security-Policy that blocks it).

| Game | Page |
|---|---|
| Peaks & Perils (Android) | https://senglaypann.github.io/games-privacy-policy/peaks-and-perils/ |

## Add the next game's policy

1. Make a folder named after the game in lowercase with hyphens, for example `my-next-game/`. Its address will be
   `https://senglaypann.github.io/games-privacy-policy/my-next-game/`.
2. Put an `index.html` and a `style.css` in it. Copying `peaks-and-perils/` is the quickest start: keep the page
   structure and the `<meta http-equiv="Content-Security-Policy">` line, replace the policy text, header art and
   colours with the new game's.
3. Fonts: copy the font files into the game folder (for example `my-next-game/fonts/`) with their licence file
   (`OFL.txt` for SIL Open Font License fonts) and load them with `@font-face`. Never link Google Fonts or a CDN.
4. Keep it readable: body text at least 16 px, lines about 70 characters, text contrast at least 4.5:1.
5. Add the game to the list in the root `index.html` and to the table above.
6. Commit and push to `main`. GitHub Pages republishes in a minute or two.
7. Open the new address in a private window, then enter it in the store's privacy policy field.

When a game's policy changes, edit its text and the "Last updated" date in the same commit.

## Licences

The fonts in `peaks-and-perils/fonts/` are under the SIL Open Font License; each folder keeps its `OFL.txt`.
