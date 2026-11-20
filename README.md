# Lunar Phases

An interactive, single-page explanation of the lunar cycle: why the Moon has phases, and how the Sun, Earth and Moon are positioned in each one.

**Live page: https://elkaszcz.github.io/lunar-phases/**

## What's inside

### Phases tab
- Top view of the Moon orbiting Earth, with sunlight coming from the left. The Moon's sunlit half always faces the Sun, and a blue arc marks the half that faces Earth (what we can see).
- The Moon as seen from Earth, with phase name, illumination, approximate rise/set times and when it's best seen.
- Northern/Southern Hemisphere view, play/pause, speed control and a slider over the 29.5-day cycle.
- A table of all eight phases and a set of key ideas (phases are not Earth's shadow, tidal locking, why there's no eclipse every month).

### Around the Sun tab (advanced)
- Earth orbiting the Sun with month labels, and the Moon orbiting Earth, seen with the stars fixed.
- **Go to date:** pick any date between 1900 and 2100 (or press *Today*) to see the real Moon phase and the real positions on that day. *Previous/Next full Moon* and *Previous/Next new Moon* jump to the first day the page labels that phase.
- A close-up showing why new Moon to new Moon takes 29.5 days (synodic month) while one turn against the stars takes only 27.3 days (sidereal month).
- A Moon-distance slider from ×1 (true scale) to ×60, showing that the Moon's real path around the Sun never loops.

### Languages
English and Polish. Switch with the flags in the top-right corner. The choice is remembered.

## Accuracy

Positions on the *Around the Sun* tab use the low-precision formulas from Jean Meeus, *Astronomical Algorithms* (ch. 25 and 48). Phase timing is accurate to within about an hour. Sizes and distances in the drawings are not to scale, as noted on the page.

## Running locally

Everything is in one self-contained file with no dependencies or build step. Open `index.html` in any modern browser.
