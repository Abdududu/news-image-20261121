# THE WORLD TODAY — Saturday 21 November 2026

[![make.fun](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/Abdududu/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/Abdududu/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121)

One image that sums up the world's news of **Saturday 21 November 2026**: a newspaper
front page with 30 real, verified stories across 7 regions — a lead story, a top-5 hero
strip, and dense regional sections, every story carrying its headline, a one-line summary,
and the outlet it came from. Built for the make.fun bounty
[Sum up 21 November's world news in one image](https://make.fun/bounty/news-image-20261121).

## The day in five stories

1. **World court: Myanmar committed genocide** — the ICJ rules 9–6 that Myanmar committed
   genocide against the Rohingya in 2017, the first time it has ever held a state responsible
   for genocide. (CNN)
2. **Russia's barrage hits Kyiv — and spills into Poland** — over 400 drones and 110 missiles
   strike Ukraine; two Russian missiles and a drone come down in Poland. (The Times)
3. **Trump calls Putin "my friend" at three-way summit** — Trump, Xi and Putin meet in
   Shenzhen and agree a "declaration toward peace". (Le Monde)
4. **Saudi Arabia downs three Houthi missiles at Riyadh** — the second Houthi attack on the
   capital in days. (Reuters)
5. **Mongolia's president quits, forcing early vote** — parliament accepts Khurelsukh
   Ukhnaa's resignation, a first for a sitting president. (Reuters)

The front page also covers Europe (EU aid and arms for Ukraine, the UK–EU youth mobility
deal, Denmark expelling a Russian attaché), the Middle East (Iraqi troops in Jurf
al-Sakhar), Asia-Pacific, the Americas, Africa, Tech & Science (AI chips to China, potatoes
in mock moon soil, the COP31 draft), and Sport & Culture.

## How it works

`main.ts` (Node 22) copies the pre-rendered front page, `assets/news.png`
(1024 × 1024, 306,322 bytes), to `/output/entry.png`. No network, no randomness, no clock —
the image is fixed bytes in the repository, so two runs write byte-identical output.

The image was produced during this build from `data/news.json` (30 stories, each written
from a source actually read) by `scripts/build-page.mjs`, which renders the newspaper
front page as HTML, and `scripts/render.mjs`, which screenshots it at 1024 × 1024 with
Playwright. The final PNG was read and checked by eye before this entry was committed.

## Run it

```sh
node main.ts
# wrote /output/entry.png: 306322 bytes
```

## Sources

CNN · Reuters · The Times · Le Monde · AP · EU Council · GOV.UK · Ukrinform · US Treasury ·
NPR · Oregon State University · Agencia Presentes · SAPS · IndexBox · Saudi-led coalition
