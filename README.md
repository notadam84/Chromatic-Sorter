# CHROMATIC SORTS

```
spectral algorithm theater
```

---

A browser-based sorting visualization running continuously in a single HTML file.
No dependencies. No build step.

---

## WHAT IT DOES

Sorts a field of color columns using classic algorithms, cycling through sort keys and palette themes automatically. Each completed sort triggers a scramble and a new round begins with a fresh palette.

---

## ALGORITHMS

```
BUBBLE SORT
COCKTAIL SHAKER
INSERTION SORT
SELECTION SORT
SHELL SORT
GNOME SORT
COMB SORT
QUICKSORT
HEAP SORT
ODD-EVEN SORT
```

---

## SORT KEYS

The same palette sorted by different properties produces entirely different visual outcomes.

```
HUE
SATURATION
LIGHTNESS
RED CHANNEL
GREEN CHANNEL
BLUE CHANNEL
LUMINANCE         perceived brightness (weighted RGB)
WARMTH            red-to-blue ratio
```

---

## SCRAMBLE PATTERNS

Applied between each sort round.

```
RANDOM BURST
REVERSE
SINE WAVE         elements reordered by sin(sortKey)
INTERLEAVE        front and back halves interlaced
CHUNKS            subdivided segments shuffled independently
CENTER OUT        elements cascade from midpoint outward
```

---

## BPM SYNC

Enable BPM mode in the control panel to drive sort steps from a tempo rather than a fixed rate.

```
BPM         40 - 300
STEPS/BEAT  1  /  2  /  4  /  8  /  16  /  32
```

Tap Tempo is available for matching a live source by ear.

---

## CONTROL PANEL

Open with the tab on the right edge. Algorithm, sort key, palette theme, and scramble pattern
can each be pinned to a specific value or left on AUTO to cycle through all options.
Color and layout controls are there to explore at your own pace.

---

## USAGE

```
download  chromatic-sorts.html
open      in any modern browser
```

No server required.

---

## LICENSE

MIT
