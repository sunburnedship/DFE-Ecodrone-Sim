# EcoDrone Designer v4 — Field Conditions

A design-for-environment simulation for freshman and sophomore engineering students.
Students design a drone for a client brief with hard requirements (cost ceiling, flight time,
launch date, legal markets) while real 2025–26 supply, policy and climate disruptions hit the project.

## What's in this folder

| Path | What it is |
|---|---|
| `index.html` | The simulation. One self-contained file (≈1 MB, photos embedded). Open it in any browser. |
| `instructor/EcoDrone_v4_Instructor_Guide.docx` | 23-page instructor guide: setup, scoring math, all 14 decisions, all 10 disruptions, reference designs, debrief cheatsheet, regulatory snapshot. |
| `instructor/EcoDrone_v4_Prebrief_Instructor_Deck.pptx` | 10-slide briefing deck (≈12 min), icon- and chart-driven, all text 16 pt or larger. |
| `instructor/EcoDrone_v4_Debrief_Instructor_Deck.pptx` | 13-slide debrief deck (≈15 min). |
| `instructor/EcoDrone_v4_Whole_Instructor_Deck.pptx` | Both decks combined (23 slides, speaker notes on every slide). |
| `card_images/` | The 10 disruption-card photos as separate files, plus `PHOTO_CREDITS.txt` (Wikimedia Commons sources and licenses). Not needed to run the simulation — the photos are already embedded in `index.html`. `_originals/` holds the uncropped downloads. |

## Hosting

The simulation needs no server. Any static host works.

**GitHub Pages:** copy this whole folder into your site's repository (for example as `/v4/`) and push.
The simulation is then at `https://<your-site>/v4/` — `index.html` loads automatically, and your existing
site root (v3) keeps working. Only `index.html` is required for students; you can leave `instructor/` out of
the public repository if you don't want students to see the instructor materials.

**LMS:** upload `index.html` and link to it.

## Class codes and links

The class-code field is hidden on the sign-in screen for now. Students sign in with their name only,
and each gets a random client.

You can still assign a client, or give everyone identical disruptions, through the link:

```
https://<your-site>/v4/?brief=sun
https://<your-site>/v4/?code=TEM-FALL26&brief=sun
```

Valid `brief` values: `sky` (SkyLens, consumer), `field` (FieldScout, agriculture), `port` (PortWatch, EU ports),
`sun` (SunLine, Arizona utility).

## How choices work

Students pick from the specs printed on each option and predict the effect. The spec sheet updates only after
they click **Lock In & Next**, with a note showing what changed. They can go back and revise freely within a phase;
passing that phase's gate review locks it.

## Grades

A 84+ · A− 79 · B+ 74 · B 69 · B− 64 · C+ 59 · C 54 · C− 49 · D 40 · F below 40. A is the top grade.
The best possible design scores 85–87 on every client before disruptions; a typical first run lands C− to B.

## Before each term

The trade, FCC and EU rules modeled in v4 change quickly. Check Section 12 of the instructor guide
(regulatory snapshot, current as of October 29, 2026) before teaching.

Student names and attempt history are stored only in each student's browser.
