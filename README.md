# Happy Birthday, Kiran 🌄

A single-page birthday site. No build step, nothing to install — open
`index.html` in a browser.

It's deliberately nothing like Kriti's page. Where that one drifts through
space, this one is a **sunrise over mountains that happens as you scroll**:
the sky goes from night to full dawn, the sun climbs out from behind the
ridges, the stars wash out, and the mountain layers slide past at different
speeds. Set in Fraunces rather than the rounded type, laid out like a printed
page rather than a card deck.

## Settings (already filled in)

Near the top of `index.html` there's one small block:

```js
const DEFAULT_THEME = 'dawn';                      // or 'dusk'
const BIRTHDAY      = '1993-10-29T00:00:00+05:45'; // Nepal time
```

**`DEFAULT_THEME`** — `'dawn'` is the blue-to-gold sunrise, `'dusk'` is a
crimson and violet sunset over the same mountains. Change the word, save,
done. The switch in the top corner still works either way; this only sets
which one it opens on.

**`BIRTHDAY`** — set to 29 October 1993, Nepal time. Format is
`YYYY-MM-DDTHH:MM:SS+TZ`; `+05:45` is Nepal, `+05:30` is India.

## Add her photos

Put them in the `photos/` folder named `1.jpeg` through `6.jpeg` — lowercase,
exact names. They become a stack of cards you tap through. Any photo that's
missing just shows a placeholder, so it works fine before they're added.

## Putting it on GitHub Pages

1. Create a new repository on GitHub (**public** — Pages needs that on a free
   account).
2. Upload everything in this folder — `index.html`, the `photos/` folder and
   both `.mp3` files. Keep the structure as it is.
3. **Settings → Pages → Deploy from a branch → `main` / `root` → Save.**
4. Wait a minute, then open `https://<username>.github.io/<repo-name>/`.

If you're putting Kriti's page up too, each one needs its own repository — or
put them in one repo in separate folders, in which case the URLs end in
`/kiran/` and `/kriti/`.

## What's on the page

| Section | |
|---|---|
| Opening | tap to let the light in |
| Hero | her name and what it means |
| The letter | |
| Seven rays | her name means *ray of light* — tap each to light it, all seven ignites the sun |
| Photos | a stack of cards, tap to shuffle |
| Seven wishes | an ascent, each step lights as it comes into view |
| Since | days of first light |
| Finale | |

## Things you can change

Everything is plain text inside `index.html`:

| What | Search for |
|---|---|
| The letter | `Dear didi` |
| The seven rays | `RAYS` |
| The wishes | `WISHES` |
| Photo captions | `CAPS` |
| Closing line | `you built` |
| Opening lines | `Before anyone else` |

The letter calls her **didi**. If you'd rather it said her name, search for
`didi` — it appears twice.

## Good to know

- Built for a phone first.
- **Tap anywhere and a lantern lifts off** from that spot and floats up.
- Birds cross in a V every so often, leader out front.
- Music starts on its own where the browser allows it; otherwise tap the
  button in the bottom-right corner.
- On a laptop: `D` switches dawn/dusk, `M` music, `L` releases lanterns.
- Goes still if the device asks for reduced motion.
