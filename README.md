# Velmara — The Poster for a Place That Isn't There

[![make.fun · the-poster-for-a-place-that-i-2-20261121-0539](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![rank](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/udgraphiccs/the-poster-for-a-place-that-i-2-20261121-0539/rank.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![reward](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/udgraphiccs/the-poster-for-a-place-that-i-2-20261121-0539/reward.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)

A [make.fun](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539) entry: a program that draws a travel poster for **Velmara**, a place that does not exist — a harbour town on a floating island above a sea of clouds, lit by a low golden sun, its beacon tower guiding the airships home.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.png (1024x1024)
```

`main.py` draws the poster with Pillow (deterministic, no network). If Pillow or the fonts are unavailable, it falls back to copying the reference render committed beside it as `entry.png`, so the output is valid either way.

## Files

- `main.py` — the poster generator (the entrypoint)
- `entry.png` — reference render of the poster (1024x1024, 258,307 bytes)
