# ⚓ Sailing Trainer

**Flashcard and quiz app for sailing certifications.** Covers the Danish
**Duelighedsbevis**, the **RYA Day Skipper** and **Competent Crew** syllabi,
and **KDY ISS**. 500+ cards across COLREGs, IALA buoyage, points of sail,
boat anatomy, weather, navigation, knots, and Danish-specific rules.

> **🌐 Live app:** https://test992-09.github.io/sailing-trainer/

---

## ⚠️ Disclaimer — read first

**This is a personal study aid only. It is NOT:**

- approved courseware,
- official guidance,
- a substitute for proper instruction, certified instructors, official
  charts, or current published regulations.

**Do NOT use this for navigation, decision-making at sea, or in any
safety-critical situation.** Always consult official charts, the current
edition of the *Søvejsregler* / COLREGs, almanacs, pilot books, weather
forecasts from authoritative sources (DMI, Met Office, NOAA, etc.), and
qualified instructors.

Content may contain errors, may be outdated, and may misrepresent the
regulations or local rules. Card answers were drafted with AI assistance
against the published syllabi; individual cards have not all been reviewed
by a certified instructor. Where in doubt, always trust the cited primary
source over the card.

**Software provided "as is", without warranty of any kind. By using this
material you accept all risk. The authors accept no liability for any
loss, damage, injury, examination failure, or other consequence arising
from use of this material.**

See [LICENSE](./LICENSE) for the full MIT licence and the extended content
disclaimer.

---

## Use it

The app is a single static HTML page hosted on GitHub Pages. No server,
no install, no account needed. Just open the URL.

To pin it to your phone's home screen as an app-like icon:

1. Open the live URL in **Safari** (iPhone) or **Chrome** (Android)
2. Tap the share button → **Add to Home Screen**

Progress is saved per-profile in your browser's `localStorage`. Multiple
people can share the same device using separate profiles. The in-app
**About** tab has Export and Restore buttons — use them periodically to
back up your progress (localStorage is wiped if you clear site data or
switch devices).

## Features

- **Flashcards** with a simplified spaced-repetition rating system
  (Forgot it / Struggled / Got it / Easy)
- **Multiple-choice quiz** mode that auto-flags weak cards
- **Browse mode** to read through cards as a reference
- **Progress tracking** by category and overall
- **Multiple profiles** so several people can study on one device
- **Inline SVG diagrams** for cardinal marks, points of sail, and boat
  anatomy with labelled parts
- **Mobile-responsive**, works as a home-screen pinned web app
- **Offline-capable** once loaded (single-file app)

## Update workflow (for the author)

The whole app lives in `index.html`. To ship a new version:

1. Generate a new version of the file
2. Rename to `index.html`
3. Replace the old `index.html` in this repo (Add file → Upload files →
   drag, or use `git`)
4. Commit. GitHub Pages auto-deploys within ~1 minute
5. Home-screen icons on existing users' devices automatically serve the
   new version — and their saved progress is preserved, because
   localStorage is keyed to the URL, which hasn't changed

## Licence

MIT. See [LICENSE](./LICENSE) for the full text. The MIT licence covers
the code — use it, fork it, modify it. The "no warranty / no liability"
clauses apply in all cases, including to the educational content.
