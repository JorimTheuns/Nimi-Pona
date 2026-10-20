# nimi pona

Flashcards for the 137 core [toki pona](https://tokipona.org) words: the 120 from *pu* plus the 17 *ku suli* words. Each card shows the word in sitelen pona with its cluster of meanings and example sentences written three ways: glyphs, transliteration, translation.

**Use it:** https://jorimtheuns.github.io/nimi-pona/

## How it works

- Tap a card to flip it, then swipe right (**sona**, knew it) or left (**sona ala**, didn't).
- Three directions: toki pona to English, English to toki pona, or mixed.
- Each round shows every word once. Misses lead the next round, then the words you've gone longest without seeing.
- Streaks: swipe one card on a day to count it. One skipped day is forgiven; two in a row ends the streak.
- Add it to your home screen and it runs offline.

## Privacy

All progress lives in your browser's `localStorage`. There is no account, cookie, analytics or server, and every font is bundled, so after the page loads the app makes no network requests. Clearing site data resets it.

## Structure

One `index.html` (word list, logic and an embedded glyph-font subset), bundled text fonts, a web app manifest, icons and a small service worker for offline use. No build step. To edit a definition, search for the word in `index.html`; entries look like `["kili","p","fruit, vegetable","any produce; …","mi moku e kili loje.=I eat a red fruit.=…"]` with example fields in the form `latin=english=sitelen-pona-source`.

## Credits and licences

- Code, definitions and examples: MIT, see `LICENSE`.
- Text fonts: [Lexend](https://github.com/googlefonts/lexend) and [Atkinson Hyperlegible](https://www.brailleinstitute.org/freefont/), SIL Open Font License 1.1, see `fonts/`.
- Glyphs: a subset of [nasin nanpa](https://github.com/ETBCOR/nasin-nanpa) by jan Itan, MIT, see `fonts/nasin-nanpa-LICENSE.txt`.
- toki pona was created by Sonja Lang.
