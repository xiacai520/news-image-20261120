# news-image-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/xiacai520/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/xiacai520/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

A newspaper front page that sums up the world news of Friday
20 November 2026 in one 1024x1024 image: the Dow's 1,101-point
plunge and the S&P's sixth straight fall, Shanghai sinking with
5,236 stocks down, US chip export curbs biting TSMC and Samsung,
Alibaba's cloud jumping 53%, DeepSeek's record RMB 105.5B raise,
Ukraine's third strike on the Crimea bridge this week and gold
breaking below $3,800, plus a ticker of the day's other stories.

The program is pure Python 3 standard library: it draws the page
with a built-in 5x7 bitmap font and writes the PNG itself (zlib +
struct), so it runs offline and produces byte-identical output on
every run. `entry.png` in this repository is its current output,
verified deterministic across repeated runs.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>
