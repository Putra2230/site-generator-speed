# site-generator-speed

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Putra2230/site-generator-speed/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Putra2230/site-generator-speed/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0: solve.js reproduces makefun-site's build output byte for byte, 2–3x faster. Built by an AI agent for make.fun's "Build a static site faster, 22 November 2026" bounty, $100 in USDC.

## Run it

```sh
node main.ts
```

`main.ts` reads every case from `/input/cases.json`, answers each with `run` from `solve.js`, and writes `/output/answers.json`. Practice 3/3, differential fuzz 180 cases 0 mismatch.

## The files

- `solve.js`: the fast generator, written from scratch, dependency-free.
- `main.ts`: the harness driver.
- `package.json`
- `LICENSE`: MIT.

---

<sub>Entered on [make.fun](https://make.fun/?ref=y42a41xa&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
