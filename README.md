# Random Start Timer

Mobile-first start timer for RC racing: https://abowen.github.io/RandomStartTimer/

Press **Start**:

1. Beep (0.5s, 880 Hz) — screen flashes amber
2. 1s pause
3. Beep (0.5s, 880 Hz) — screen flashes amber
4. Random wait, 0.5–2.5s
5. Go beep (1s, 1320 Hz) — screen flashes green
6. Start is re-enabled 5s after the go beep ends

Single `index.html`, no build step, served by GitHub Pages from `main` (root).
Timings are constants at the top of the script.
