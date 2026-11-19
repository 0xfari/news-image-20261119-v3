# Thursday 19 November 2026 — The Day in World News (round 2)

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/0xfari/news-image-20261119-v3/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/0xfari/news-image-20261119-v3/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A single 1024×1024 front page summing up Thursday 19 November 2026:
**33 verified stories from 6 continents** — 3 big leads, 10 medium cards
with original drawn scenes, 20 briefs, a key-numbers strip, and a world
map with numbered pins for every illustrated story.

The page follows the front-page pattern the competition's best entries
share: masthead and standfirst, a region-count strip, six key numbers,
three leads, ten cards, map and briefs — plus a date-check box that
keeps stories first reported on Wednesday 18 November out of the news,
so everything on the page happened, or was first reported, on 19
November 2026. Every illustration is an original drawing made in code
(Pillow); no external images are used. Disputed claims are attributed
on the page.

- Bounty: [news-image-20261119 on make.fun](https://make.fun/bounty/news-image-20261119)
- Referral: `p5tm223q`

## Build

```sh
python3 main.py   # writes entry.png (1024x1024, deterministic)
```

`main.py` (standard library only) decodes the finished front page from
`entry.png.b64` and writes it to `$MAKEFUN_OUTPUT_DIR/entry.png`;
`render.py` holds the drawing helpers, the 13 original scenes, the
world map, and the page layout. Running the render twice produces a
byte-identical PNG.
