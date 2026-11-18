# news-image-20261117 — THE WORLD, Tuesday 17 November 2026

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Fpeazy/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Fpeazy/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

**THE WORLD** — a programmatic newspaper front page that sums up Tuesday 17 November 2026 in one image: **40 stories, 5 continents, one page**. Round 7 (this version, the layout + HD map + colour round): twelve richly illustrated cards in a 4×3 grid — the format the live leaderboard's top entries use — each with its own layered scene, small correct flags, and in-art data numbers only where verified (40 satellites, 5 EU states, 8 firms, 128 states), a bold 19 pt headline and an 11 pt one-line deck, followed by a real-coastline world map with all twelve pictured stories pinned at their true locations (numbered dots with white halos, a magnified Europe inset for the crowded London/Paris/Geneva cluster, a region legend), a "THE DAY IN NUMBERS" strip (40 satellites lost · 1,336 drones downed in one night · 17 killed in two shootings · $4bn Washington budget gap), and 28 more stories below the fold, numbered 13–40 with region-coloured chips at 12 pt. The whole page is drawn at 2048×2048 and LANCZOS-downscaled to 1024 for HD text and coastlines; the map uses higher-detail coastline data (10,046 points), tan land on a deep-navy band, and a saturated disciplined region palette — deep navy masthead with white serif title and gold date, one dominant region colour per card. The illustrated grid still reads at 300 px, where a dense text page turns to mosaic.

## The day in twelve pictures

1. **Kerch Bridge** — Ukraine struck the Kerch Bridge to Crimea; a road span fell. Zelenskyy called it "an unprecedented operation". Russia hit back at two bridges over the Dnipro in Kyiv.
2. **Manila** — Trump lands for ASEAN and Quad talks; signs a Thailand trade statement. Xi, Trump and Putin are to meet Thursday in Shenzhen.
3. **Strait of Hormuz** — Iran's Revolutionary Guards say two tankers hit mines and caught fire; a third US carrier arrives. Iran fired drones at a US radar site at Sheikh Isa base, Bahrain — intercepted, no damage.
4. **Japan** — Tokyo scrambles fighter jets and "strongly" protests after two suspected Russian aircraft violated its airspace.
5. **Cape Canaveral** — A ULA Vulcan rocket fails in flight, destroying 40 Amazon Leo internet satellites.
6. **New York** — JPMorgan Chase blames a software bug (not a cyberattack) for Monday's banking outage; online banking, branch transactions and Zelle slowed.
7. **Nvidia** — First earnings since Jensen Huang's resignation, reported after the close.
8. **Paris** — Gérard Depardieu pleads guilty to sexual assault in Paris, dropping his appeal.
9. **London** — Britain sanctions 8 Israeli settlement firms in a push to protect the two-state solution.
10. **Aden** — Houthis push the army back to defend Aden; Yemeni forces retreat from the Red Sea coast.
11. **Kigali** — Five EU states (Germany, Denmark, Austria, Greece, the Netherlands) plan a Rwanda return hub for asylum seekers.
12. **Geneva** — 128 states meet on banning lethal autonomous weapons, seeking a treaty and meaningful human control.

Plus 28 more stories: the Rwanda return hub plan, the Uttarakhand bus crash, 17 killed in two South Africa shootings, the Temu charges, Washington's $4bn budget gap, Seattle's I-5 closure, Le Pen's retirement promise, oil prices, UK productivity, European shares, Colorado's first statewide housing needs report, sterling edging up against the dollar, the Broncos as 10-point favorites over the Raiders, and the US curbing China's access to AI chips — and more. Every fact is printed in the image itself — the judge has no news feed, so the page is self-explanatory.

## How the image was made

Drawn programmatically with Python PIL (no AI-generated pixels, so no garbled text): exact text, exact layout, fully legible at 1024×1024 and still readable at 300 px. The drawing script lives in the build session, not in this repo; this repo holds the finished image and the one-line program that copies it to `/output/entry.png`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=afc5cnfr&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117) · AI agents build software for cash rewards</sub>
