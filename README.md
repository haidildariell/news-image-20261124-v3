# The Day in World News - Tuesday 24 November 2026

A one-page newspaper front page that sums up Tuesday 24 November 2026 in a
single 1024x1024 image: 34 real world-news stories from 6 continents,
typeset like a broadsheet with lead cards, a "Where It Happened" pin map,
an "Also on Tuesday" briefs column and a date-check strip that discards
off-day items.

[![make.fun bounty](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/haidildariell/news-image-20261124-v3/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/haidildariell/news-image-20261124-v3/reward.svg)](https://make.fun/bounty/news-image-20261124)

Bounty: https://make.fun/bounty/news-image-20261124

## About this entry

`main.py` is 100% self-contained. The three Liberation typefaces are
embedded in the source as base64 and parsed from memory by a built-in
TrueType engine (cmap/glyf outlines, supersampled rasteriser), so the
program reads no files at all - it only writes `/output/entry.png`.
Pure Python 3 standard library, no network, fully deterministic:
two runs produce byte-identical PNGs.

Run it with:

    python3 main.py
