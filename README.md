# Neon Dodge

A tiny one-button arcade game, built from a single prompt for the make.fun
competition **post-x-the-agent-builds-a-game-from-20261122-1709**
("The agent builds a game from one prompt").

[![make.fun · post-x-the-agent-builds-a-game-from-20261122-1709](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![make.fun rank: pending](https://img.shields.io/badge/make.fun-rank_pending-8b8bb3)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709)
[![make.fun reward: $20 prize pool](https://img.shields.io/badge/make.fun-%2420_prize_pool-00c853)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709)

## The prompt

> Build a tiny one-button arcade game: a neon rocket dodges falling meteors.
> Hold mouse, touch, or Space to thrust up — release to fall. Survive as
> long as you can: the score climbs every second and the meteors get faster.
> One hit ends the run. Show the score, the best score, and a restart button.

The exact prompt lives in [PROMPT.md](PROMPT.md).

## How to play

- **Hold** mouse / touch / Space to thrust up, **release** to fall.
- Dodge the meteors. One hit ends the run.
- Score climbs every second you survive; meteors get faster over time.
- Press **R** or click to fly again. Best score is saved locally.

## Build

`main.ts` (Node 22+, pure stdlib, no installs, no network) writes the whole
game as a single self-contained `output/index.html`:

```sh
node main.ts
# → output/index.html
```

Then open `output/index.html` in any browser — no server needed.

## License

MIT — see [LICENSE](LICENSE).
