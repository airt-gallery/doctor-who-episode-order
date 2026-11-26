# Doctor Who episode-order tracker

A simple on-device viewing tracker for families starting Doctor Who. It lists a family-friendly starter watch order of 27 episodes from the modern series (2005 to 2025), grouped by Doctor in the order they first aired, and lets you tick off what you've seen, with your progress and what's up next.

Built by MSTR BLDR on **AiRT Official**. An unofficial fan reference, made for fun and written in our own words. Episode titles and first UK air dates are listed as facts. Doctor Who is a trade mark of the British Broadcasting Corporation (BBC). Not affiliated with or endorsed by the BBC.

## What it does

- **A starter watch order:** 27 episodes, three or four for each Doctor from the Ninth to the Fifteenth, in first-aired order. Each shows its title, series and first UK air date, with a one-line note in our own words. No quotes from the show, stills, logos, official artwork, police-box pictures or trademarked fonts.
- **Tick off an episode:** tap an episode (or its tick box) to mark it watched; tap again to untick.
- **Progress:** watched out of 27, a percentage, a progress bar, a count for each Doctor, and the next episode to watch.
- **Still to watch:** one tap hides what you've seen.
- **Start again:** tap once, then tap again to clear every tick.
- **A note for parents:** most episodes suit family viewing, but some have scary moments.
- Saved in this browser only (key `doctor-who-episode-order-tracker-data`). Works offline. One file, plain HTML, CSS and JavaScript. No libraries, web fonts, images, trackers or Ai features.

## How it was tested

Checked in headless Chrome with the internet switched off (34 automated checks, all pass). All 27 titles and first air dates match Wikipedia's list of Doctor Who episodes (see [SOURCES.md](SOURCES.md)), and the list is in first-aired order. Progress worked out by hand: 3 of 27 = 11%, 7 of 27 = 26%, 8 of 27 = 30%, 27 of 27 = 100%. Also checked: counts for each Doctor, up next moves on, Still to watch hides watched episodes, ticks and the filter are kept after a reload, reset needs two taps and clears everything, keyboard ticking, bad saved data falls back safely, no sideways scroll on a phone (320 and 390 px wide), works at desktop width, no network requests and no console errors.

## How to run

**Use it free:** https://airt-gallery.github.io/doctor-who-episode-order/

Or run it locally:

1. Download `index.html`.
2. Open it in any modern browser, on your phone or computer.
3. On a phone, use the browser's "Add to Home Screen" so it opens like an app.

## The ASTARR prompt used

PROBLEM: My family wants to start watching Doctor Who, but with hundreds of episodes we don't know where to begin, and we keep forgetting which ones we've already seen.

ASTARR PROMPT

ACT AS: A long-time Doctor Who fan and family TV guide who builds simple phone apps.

SPECIFIC TOPIC: A family-friendly watch order for the modern Doctor Who series since 2005, picking a few fun episodes for each Doctor in the order they first aired. Use episode titles and air dates only, checked against a trusted episode list, with a one-line note for each in your own words. No quotes from the show, and no stills, logos, official artwork, police-box pictures or official fonts.

ACTIONS: List the episodes grouped by Doctor, with a big tick box for each and a count for each Doctor. Show how many we've watched, a progress bar and which episode is up next. Add a Still to watch filter and a reset that asks before it clears. Test the titles and dates against the list, and check the progress by hand.

RESULT&RULES: I want a mobile app with big buttons and a calm, clean look, saved on this phone only. No connections to the internet or Ai tools. Family-friendly, and marked as an unofficial fan reference.

ASTARR = Act As, Specific Topic, Actions, Result, Rules.

## Licence

Code: MIT. See [LICENSE](LICENSE). Doctor Who and everything from the show belong to the BBC; the licence covers only our code and wording.

---
Sponsored by BizWithAi.ai, your Ai solutions partner.
