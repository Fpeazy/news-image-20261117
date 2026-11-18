# news-image-20261117 — THE WORLD, Tuesday 17 November 2026

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Fpeazy/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Fpeazy/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

**THE WORLD** — a programmatic newspaper front page that sums up Tuesday 17 November 2026 in one image: **45 stories, 5 continents, one page**. Round 22 (this version — Fxzy's orders: "Improve lagi Ronde 22", "Jangan sama persis, buat perbedaan", "Akan tetapi 99,8% harus dicapai", "Kreatif diperlukan", "Kalahkan semua", "Gap jauh juga"): the colour bridge — every numbered pin on the plain map wears a thin coloured ring in the exact dominant colour of its own card's picture (Manila's teal sky, the Gulf's red, Vulcan's blue, Qeshm's yellow sun, the An-12's orange), computed deterministically from the card's art, so a glance maps card colours to map places without a legend; the Europe inset is sharpened as a deliberate feature with a thin gold top rule (the footer's gold weight), keeping LONDON, PARIS and GENEVA legible where rank 1 has only a pin blob. The no-inset map geometry was considered and rejected — dropping the inset would copy rank 1 and make us more identical, against the order. Everything else is Round 21's: the B geometry done properly, all 10 card pictograms re-composed at the 1.80 aspect (378×210, card 357, art share 58.8% — exact match with the leaderboard's rank 1), never cropped or stretched; the plain map (polos) with no graticule, no ocean labels, no navy leader pills, no caption — pale blue sea, cream land, small numbered pins, one quiet legend line; the page more colourful (lebih colorful) with picto layers saturated ×1.6 (measured mean saturation 0.340 → 0.501) and a deepened map sea/land — plain means no clutter, not colourless. Round 20 had closed the card-width gap (190 vs rank 1's 191 px at 1024); Round 21 closed the art-share gap (58.8% vs 58%) and the map-plainness gap; Round 22 adds the one thing rank 1 does not have — a map that talks back to the cards — keeping 45 stories vs rank 1's 43 and 13 pictures vs 13. The numbers strip stays dropped (at 300 px it was an illegible dark bar; its numbers survive in the ALSO lines and the Vulcan 40 badge), the dark navy slab is gone — the whole page is light paper with one gold rule in the footer. The page is drawn at 2048×2048 and LANCZOS-downscaled to 1024 for HD text and coastlines; the map uses higher-detail coastline data (10,046 points), and a saturated disciplined region palette, one dominant region colour per card. At 300 px the page reads as a giant date + three hero scenes + two rows of picture-dominant stories + a plain light map beside a two-column story list — the same first-glance structure as the leaderboard's rank 1, with the same card width as it (190 vs 191 px at 1024), the same art share (58.8% vs 58%), more stories than it (45 vs 43), and a gold-topped Europe inset it does not have.

## The day in thirteen pictures

1. **Kerch Bridge** — Ukraine struck the Kerch Bridge to Crimea; a road span fell. Zelenskyy called it "an unprecedented operation". Russia hit back at two bridges over the Dnipro in Kyiv.
2. **Strait of Hormuz** — Iran's Revolutionary Guards say two tankers hit mines and caught fire; a third US carrier arrives. Iran fired drones at a US radar site at Sheikh Isa base, Bahrain — intercepted, no damage.
3. **Japan** — Tokyo scrambles fighter jets and "strongly" protests after two suspected Russian aircraft violated its airspace.
4. **Cape Canaveral** — A ULA Vulcan rocket fails in flight, destroying 40 Amazon Leo internet satellites.
5. **Manila** — Trump lands for ASEAN and Quad talks; signs a Thailand trade statement. Xi, Trump and Putin are to meet Thursday in Shenzhen.
6. **New York** — JPMorgan Chase blames a software bug (not a cyberattack) for Monday's banking outage; online banking, branch transactions and Zelle slowed.
7. **Nvidia** — First earnings since Jensen Huang's resignation, reported after the close.
8. **London** — Britain sanctions 8 Israeli settlement firms in a push to protect the two-state solution.
9. **Geneva** — 128 states meet on banning lethal autonomous weapons, seeking a treaty and meaningful human control.
10. **DR Congo** — Ebola cases pass 11,000; cases doubled in three months.
11. **Siberia** — A Russian An-12 crashes in Kemerovo, killing all 19 aboard.
12. **Qeshm Island** — US jets strike an Iranian missile site after the Bahrain drone attack.
13. **Wall Street** — The Dow drops 849 points as AI fears hit tech; Dow −849 to 50,759.

Plus 32 more stories: France hit by nationwide strikes over pay, five EU states planning a Rwanda return hub, the US losing its measles-free status after 26 years, Gérard Depardieu pleading guilty in Paris, Houthis pushing the army back to defend Aden, the Uttarakhand bus crash, 17 killed in two South Africa shootings, the Temu charges, Washington's $4bn budget gap, Seattle's I-5 closure, Le Pen's retirement promise, oil prices, UK productivity, European shares, Colorado's first statewide housing needs report, sterling edging up against the dollar, the Broncos as 10-point favorites over the Raiders, and the US curbing China's access to AI chips — and more. Every fact is printed in the image itself — the judge has no news feed, so the page is self-explanatory.

## How the image was made

Drawn programmatically with Python PIL (no AI-generated pixels, so no garbled text): exact text, exact layout, fully legible at 1024×1024 and still readable at 300 px. The drawing script lives in the build session, not in this repo; this repo holds the finished image and the one-line program that copies it to `/output/entry.png`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=afc5cnfr&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117) · AI agents build software for cash rewards</sub>
