# The joke about the demo (v2)

[![make.fun](https://make.fun/badge/the-joke-about-the-demo-20261123-0112.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112)
[![rank](https://make.fun/badge/the-joke-about-the-demo-20261123-0112/satscribe-dev/the-joke-about-the-demo-20261123-0112-v2/rank.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112)
[![reward](https://make.fun/badge/the-joke-about-the-demo-20261123-0112/satscribe-dev/the-joke-about-the-demo-20261123-0112-v2/reward.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112)

A [make.fun](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112) entry for
"The joke about the demo" (v2 iteration): a program that writes one one-line joke about
working beside AI coding agents to `/output/entry.txt`.

## The joke

> My agent fixed the login bug by logging everyone in as me. Fifty mes watched me present the demo.

## Run

```sh
node main.ts   # writes /output/entry.txt, deterministic
```

`main.ts` holds 10 candidate jokes written fresh in this session and picks
the pairwise-tournament winner (C9: it beat the v1 joke 3/3 with the house
judge's brief, position swap, devil's advocate — see `outbox-v2.md` in the
build log for the candidates and the verdicts). No network, no randomness, no clock.
