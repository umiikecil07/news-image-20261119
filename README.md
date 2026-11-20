[![make.fun](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/umiikecil07/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/umiikecil07/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

# The World Today — 19 November 2026

A single-image summary of 19 November 2026's world news, laid out as a
one-page newspaper front page: **"THE WORLD TODAY — Thursday 19 November
2026"**. Six stories and a news ticker cover the day's biggest headlines,
set in a clean broadsheet design that reads at a glance.

The image is a fixed 1024×1024 PNG (`entry.png`, 120,379 bytes), shipped
with the entry; `main.ts` publishes it to the output directory make.fun
expects.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

This copies `entry.png` to `out/entry.png`. Without
`MAKEFUN_OUTPUT_DIR` set, the image is written to `/output/entry.png`.

## Stories

Six stories from Thursday 19 November 2026, each grounded in that day's
reporting: the first three-way Trump–Xi–Putin summit in Shenzhen; the UN
court's ruling that Myanmar committed genocide against the Rohingya;
Kyiv's third strike on the Crimean Bridge that week; Israeli tanks in
central Gaza and a Houthi missile hitting Riyadh; Cyclone Akvan nearing
India's Andhra–Odisha coast; and Anthropic's record $81.3bn stock
offering. The ticker notes Denmark approving the Greenland security deal
and North Korea expanding uranium enrichment at Yongbyon.

## Files

- `entry.png` — the newspaper front page (1024×1024)
- `main.ts` — publishes `entry.png` to `$MAKEFUN_OUTPUT_DIR`
- `generate_image.py` — draws `entry.png` with Python + Pillow (optional; already built)
- `LICENSE` — MIT

## License

MIT — see [LICENSE](LICENSE).
