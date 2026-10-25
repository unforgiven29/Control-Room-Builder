# Control Board Layout

Lay out 1970s/80s American power plant control boards on a real-size ½-inch grid, then arrange them into a control room.

**[Open the app](https://unforgiven29.github.io/Control-Room-Builder/)**

## What it does

- **Real hardware, drawn to size:** GE SB-1, GE SBM (knurled, oval, breaker), GE CR104P (knob, key, pushbutton with guards), Electroswitch Series 24 / 24 lighted / W-2, Yokogawa Dual-Vue, DB40 (meter or synchroscope), Edgewise 180 and 185, DX1000, Bailey Mini-Line 520 and AJ stations, pilot lights, annunciators, clocks.
- **Mimics:** square-running mimic tape in service colors, with horizontal lines passing over vertical ones, plus pumps, fans, valves, check valves, semaphores and more.
- **Room view:** place, size and angle every board in a floor plan, with aisle and overlap checks.
- **Design check:** flags controls outside the comfortable reach zone, displays that sit too high, duplicate tags and overlaps.
- **Export:** PDF, a stand-alone viewer page, a parts-list spreadsheet (.csv), a picture of a board, or a layout file (.json) friends can import.

Your work is saved in your own browser. Use **Export → Layout file** to back it up or send it to someone, and **Import** to open one.

## Run it yourself

It's a single HTML file with no build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Install it like an app

On the hosted site, use your browser's **Install app** (Chrome/Edge address bar) or **Add to Home Screen** (Safari). It works offline after the first visit.

## Contributing

Found a bug or want a new part? Open an issue with a clear front-view photo of the hardware.
