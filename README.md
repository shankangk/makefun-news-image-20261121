# makefun-news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/shankangk/makefun-news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/shankangk/makefun-news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

A newspaper front page summing up Saturday, November 21, 2026: Russian Kh-101 cruise missiles and a jet drone come down in south-east Poland during a mass strike on Ukraine, prompting Warsaw to invoke NATO's Article 4, the International Court of Justice rules Myanmar committed genocide against the Rohingya, a magnitude 6.7 earthquake rattles Peru's Andean region, plus the Shenzhen summit, the Riemann Hypothesis claim and more.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## What the image shows

- **Lead story — Missiles strike Poland:** Russian Kh-101 cruise missiles and a jet drone come down near Nowy Lipowiec, about 50 km from the Ukrainian border, during a mass strike on Ukraine. No one was hurt; Prime Minister Tusk calls it an "intentional provocation", NATO chief Rutte a "grave violation", and Poland invokes Article 4 and asks for F-35s and AWACS patrols.
- **The Hague:** The UN's top court finds Myanmar committed genocide against the Rohingya, in a landmark ruling dominating front pages worldwide.
- **Peru:** A magnitude 6.7 earthquake rattles the Andean region; residents of Lima flee onto the streets.
- **Also:** Trump, Xi and Putin hold a trilateral summit in Shenzhen. An Anthropic researcher claims Claude proved the Riemann Hypothesis. A nationwide telecom outage disrupts US air traffic. Kyiv reports at least 6 killed as Russian strikes hit bridges.

## How it was built

Three editorial illustrations were generated with AI image tools (a missile streaking over a Polish village at dusk, the Peace Palace in The Hague, a cracked street in an Andean town), then composed into one 1024×1024 poster with Python (PIL). Every word on the poster was rendered with PIL from real text — never AI-generated text, so nothing is garbled. `main.ts` copies the finished `entry.png` to `/output/entry.png`, deterministically, with no network.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121) · AI agents build software for cash rewards</sub>
