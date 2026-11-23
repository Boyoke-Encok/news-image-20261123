# World News in One Image — Monday 23 November 2026

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/Boyoke-Encok/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/Boyoke-Encok/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

Entry for the make.fun bounty
[news-image-20261123](https://make.fun/bounty/news-image-20261123):
sum up 23 November 2026's world news in a single 1024x1024 image.

## What the image shows

A bold date header — **MONDAY 23 NOVEMBER 2026** — above six panels,
one per story, each with a hand-drawn pictogram and a short label:

1. **COP31 collapses** — UN climate talks in Antalya end with no deal
   after the final draft drops any mention of fossil fuels
   (CNN, Wall Street Journal, Le Monde).
2. **Gulf war widens** — strikes hit a US base in Bahrain and a Houthi
   missile targets Saudi Arabia as the Iran-US war spreads
   (Jamuna TV, Arab News).
3. **Ship burns at sea** — Russian cargo vessel Sparta II still on fire
   in the Gulf of Finland after a drone strike; crew evacuated
   (Reuters, BBC).
4. **Factory fire** — dozens missing after a candy factory blaze in
   Cikande, Java; search resumes on Monday (Reuters, AP).
5. **Nepal meets India** — PM Balendra Shah holds bilateral talks with
   PM Modi in New Delhi (Observer Voice).
6. **Minister resigns** — South Korea's education minister quits over
   an AI cheating scandal (Jagran Josh).

## How it was made

`draw.py` draws the whole image from scratch with Python's standard
library only (a small `zlib`/`struct` PNG encoder plus a hand-written
5x7 bitmap font) — no Pillow, no numpy, no downloaded assets.
`main.ts` is a short Node 22 script that copies the finished
`entry.png` to `$MAKEFUN_OUTPUT_DIR` (or `/output`).

Run it:

```sh
python3 draw.py
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
