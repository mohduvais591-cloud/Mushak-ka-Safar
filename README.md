# 🐭 Mushak Ka Safar — Mushak's Chaturthi Day

A Ganesh Chaturthi game built as **four separate mini-games** tied together by one
story: Ganesha's mouse Mushak living through a full festival day — morning, midday,
evening, and night. Pick any level from the hub, replay for a better score, and try
to complete all four.

Built as a single self-contained HTML file. No installs, no build step, no external
image or audio files — everything (art, sound) is generated in code, so it runs
anywhere a browser runs.

## The four levels

| Time | Level | Genre |
|---|---|---|
| Morning | **Modak Dash** | 3-lane endless runner — jump, duck, switch lanes |
| Midday | **Rangoli Memory** | Classic memory/match card game against the clock |
| Evening | **Dhol Rhythm** | Beat-matching rhythm game synced to a dhol pattern |
| Night | **Visarjan Journey** | A boat-steering runner down the river to visarjan |

Each level tracks its own best score and star rating (saved in the browser), and the
hub shows a combined "Festival Score" across all four.

## How to play

- **Desktop:** arrow keys to move/steer, `Space`/`↑` to jump or hit a beat, `↓`/`S` to duck.
- **Mobile:** swipe in the corresponding direction, or use the on-screen ◀ ⤒ ⬇ ▶ buttons.
- **Modak Dash / Visarjan Journey:** switch lanes around coconuts/logs, jump over
  puddles/whirlpools, duck under festoons/arches. Fill the diya meter (via modaks and
  durva grass) to trigger Ganesha's Blessing — a few seconds of invincibility and a
  score multiplier.
- **Rangoli Memory:** flip two cards at a time to find matching festival symbols
  before the 45-second timer runs out.
- **Dhol Rhythm:** a dhol beat plays as notes fall down three lanes — press
  ◀ / Jump / ▶ as each note reaches the target ring for Perfect or Good points.
- Tap 🏠 anytime to return to the hub without finishing a level.

## Sound

All sound effects and the ambient hub drone are synthesized live with the Web Audio
API — there are no audio files to host or license. Distinct tones for each pickup,
a dhol metronome you can actually hear and play along to in the rhythm level, and a
bell/confetti moment on every level win.

## live link : 

## Tools used

HTML5 Canvas, vanilla JavaScript (ES6), CSS3, Web Audio API, browser `localStorage`
for saving progress. No build tools, no third-party libraries, no external assets.

## Submission checklist (mapped to contest requirements)

- [x] Easy to start — hub screen, one tap into any level, no sign-up.
- [x] Working gameplay — four distinct, fully playable mini-games.
- [x] Clear result — score, stars, and a level-specific outcome on every run.
- [x] Proper ending — every level ends in an explicit Win or Fail screen.
- [x] Play again — Retry, Next Level, and Back to Hub on every result screen.
- [x] Mobile and laptop — touch swipe + on-screen buttons, keyboard, responsive canvas.
- [x] Cross-campus access — static file, no login, no restrictions (verify after deploying).
- [x] Safe content — no violence; Ganesha is only ever the warm, respected destination.
- [x] Theme, across all four levels — modaks, laddoos, durva, coconuts, puddles,
      pandal festoons, rangoli, a dhol procession, and a calm visarjan finale.

## Demo video link : 

Show the hub first (it makes the "four levels, one story" structure obvious at a
glance), then a short clip of two or three levels — the rhythm level in particular
demonstrates the most technical variety in one submission. Mention that all art and
sound are generated in code with zero external assets, since that's the kind of
detail judges ask about in a code walkthrough.
