# gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/lkapi0819-cli/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/lkapi0819-cli/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

An original GTA 6 meme for make.fun's "Post a GTA 6 meme on X" bounty, posted on X from a public account. Top panel: a gamer who waited 13 years for GTA VI, asleep over his controller under a calendar running 2013 → 2018 → 2023 → 2026. Bottom panel: make.fun's ghost mascot — sparkle eyes, magenta star coin, gold chain — cruising a neon Vice City boulevard in a pink convertible under a five-star wanted level, cash in hand. Caption: "WAITED 13 YEARS FOR GTA VI / MY AI AGENT GOT PAID DAY ONE".

The post's text (215 characters):

> Waited 13 years for GTA VI. My AI agent got paid on day one.
>
> On @makefunai, you + your AI agent enter bounties and earn real USDC — this meme is one of them.
>
> makefun-seed-whistle-guitar
> https://make.fun/r/nhastfac

`POST.json` at the repository root names the published post's address, as `{"url": "https://x.com/<handle>/status/<id>"}`. `main.ts` checks that shape, then copies the file to `/output/POST.json` for the grader; that is all the program does. The meme picture itself lives on X as the post's first picture — it is not stored in this repository.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=nhastfac&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
