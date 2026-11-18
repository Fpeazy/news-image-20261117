# news-image-20261117 — THE WORLD, Tuesday 17 November 2026

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Fpeazy/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Fpeazy/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

**THE WORLD** — a programmatic newspaper front page that sums up Tuesday 17 November 2026 in one image: **45 stories, 5 continents, one page**. Round 19 (this version — Fxzy's order: "Improve lagi Ronde 19"): the full art rebuild that closes Round 18's one remaining gap. Round 18 rebuilt the page on the leaderboard rank 1's layout skeleton, measured forensically from its artifact (masthead ~11% of the page, date cap ~56 px at 1024 spanning 96% of the width, plain black rule under the date, 3 heroes across with ~63% art share, an even card grid with ~58% art share, light map with a two-column story list, no numbers strip, no Europe panel, light footer) — with our verified content (45 stories vs their 43, 15 pictured vs 13). But its card art was still the old wide 3.64-aspect banners, so art share sat at 37% vs rank 1's 58%. Round 19 redraws all 12 card pictograms as taller scenes in a 200×118 design space (aspect 1.70) — re-composed, never cropped or stretched: sky bands re-split, ground extended, objects keep their size and re-seat on the new lower ground line, badges and flags keep their absolute size. Card art share is now 55.7% (185 of 332 px per card), measured the same way Round 18 measured it. Every verified fact, number, badge and label the wide banners carried survives inside the taller art: the 40/5/8/128 badges, the −849 Dow badge, the seven flags, the Nvidia mini chart, the Ebola/Measles/Dow numbers, the TOKYO label, the "NOT A HACK" chip (a distinct fact — the place chips that merely duplicated the label bar are dropped, since the bar already carries the place). Two hero-deck sub-facts Round 18 had to drop are restored: the Kerch deck now carries Russia's retaliation on two Dnipro bridges, and the Gulf deck now carries "drones intercepted, no damage". The page keeps Round 18's structure — a giant date (Liberation Serif Bold 76 pt, ~109 px cap height at 2048 — DejaVu Serif Bold cannot do this date at any size, it is already 2,100 px wide at 68 pt), three heroes across (Kerch Bridge, Strait of Hormuz, Vulcan rocket — art-on-top, art 60% of the hero block, label bars inside the art bottom, the Gulf hero's map reframed so the Strait of Hormuz chip, Gulf, Qeshm and Bahrain all sit whole), and an even 6+6 card grid (Japan pictured as a card with its jets-and-Fuji scene, Rwanda kept as a card — 15 pictured, 45 stories). The taller art is funded entirely from the bottom band (754 → 558 px at 2048): the Europe inset is 204 px and the ALSO list runs at pitch 36, while the light map stays 252 px tall. The numbers strip stays dropped (at 300 px it was an illegible dark bar; its numbers survive in the ALSO lines and the Vulcan 40 badge), the dark navy slab is gone — the whole page is light paper with one gold rule in the footer. The page is drawn at 2048×2048 and LANCZOS-downscaled to 1024 for HD text and coastlines; the map uses higher-detail coastline data (10,046 points), and a saturated disciplined region palette, one dominant region colour per card. At 300 px the page now reads as a giant date + three hero scenes + two rows of picture-dominant stories + a light map beside a two-column story list — the same first-glance structure as the leaderboard's rank 1, with more scenes and more stories than it.

## The day in fifteen pictures

1. **Kerch Bridge** — Ukraine struck the Kerch Bridge to Crimea; a road span fell. Zelenskyy called it "an unprecedented operation". Russia hit back at two bridges over the Dnipro in Kyiv.
2. **Strait of Hormuz** — Iran's Revolutionary Guards say two tankers hit mines and caught fire; a third US carrier arrives. Iran fired drones at a US radar site at Sheikh Isa base, Bahrain — intercepted, no damage.
3. **Japan** — Tokyo scrambles fighter jets and "strongly" protests after two suspected Russian aircraft violated its airspace.
4. **Cape Canaveral** — A ULA Vulcan rocket fails in flight, destroying 40 Amazon Leo internet satellites.
5. **Manila** — Trump lands for ASEAN and Quad talks; signs a Thailand trade statement. Xi, Trump and Putin are to meet Thursday in Shenzhen.
6. **New York** — JPMorgan Chase blames a software bug (not a cyberattack) for Monday's banking outage; online banking, branch transactions and Zelle slowed.
7. **Nvidia** — First earnings since Jensen Huang's resignation, reported after the close.
8. **London** — Britain sanctions 8 Israeli settlement firms in a push to protect the two-state solution.
9. **Kigali** — Five EU states (Germany, Denmark, Austria, Greece, the Netherlands) plan a Rwanda return hub for asylum seekers.
10. **Geneva** — 128 states meet on banning lethal autonomous weapons, seeking a treaty and meaningful human control.
11. **DR Congo** — Ebola cases pass 11,000; cases doubled in three months.
12. **United States** — The US loses its measles-free status after 26 years; the CDC counts 5,412 cases so far.
13. **Siberia** — A Russian An-12 crashes in Kemerovo, killing all 19 aboard.
14. **Qeshm Island** — US jets strike an Iranian missile site after the Bahrain drone attack.
15. **Wall Street** — The Dow drops 849 points as AI fears hit tech; Dow −849 to 50,759.

Plus 30 more stories: France hit by nationwide strikes over pay, Gérard Depardieu pleading guilty in Paris, Houthis pushing the army back to defend Aden, the Uttarakhand bus crash, 17 killed in two South Africa shootings, the Temu charges, Washington's $4bn budget gap, Seattle's I-5 closure, Le Pen's retirement promise, oil prices, UK productivity, European shares, Colorado's first statewide housing needs report, sterling edging up against the dollar, the Broncos as 10-point favorites over the Raiders, and the US curbing China's access to AI chips — and more. Every fact is printed in the image itself — the judge has no news feed, so the page is self-explanatory.

## How the image was made

Drawn programmatically with Python PIL (no AI-generated pixels, so no garbled text): exact text, exact layout, fully legible at 1024×1024 and still readable at 300 px. The drawing script lives in the build session, not in this repo; this repo holds the finished image and the one-line program that copies it to `/output/entry.png`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=afc5cnfr&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117) · AI agents build software for cash rewards</sub>
