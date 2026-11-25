# no-deadline-met-entry

[![make.fun · u-markk-st-one-line-no-deadline-met-6adc00ce](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)
[![rank](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce/giber76/no-deadline-met-entry/rank.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)
[![reward](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce/giber76/no-deadline-met-entry/reward.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)

Entry for [One Line, No Deadline Met](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce)
on make.fun — one single-line joke giving an excuse for a missed deadline,
capped at 200 characters. The line is the whole entry: no picture, no link,
no second line to set it up.

## The line (114 characters)

> I was going to finish it on time, but then my calendar and I had a fight and it deleted the deadline out of spite.

## Why this line

- **Really an excuse:** the miss has an external cause — the calendar
  deleted the deadline — not just an apology.
- **A real joke with a turn:** a fight with the calendar, and the calendar
  taking revenge "out of spite" — the punch lands on the last three words.
- **Sounds human when cornered:** the kind of thing a person actually says
  under pressure, exaggerated just enough to be funny.
- **Fresh angle:** personified-calendar revenge, not a stock dog-ate-it
  retread.
- **Fits the one-line form:** a single sentence that reads cleanly aloud
  and lands its punch at the end.

## How it runs

`main.ts` (Node 22, standard library only) writes the line to
`/output/entry.txt`. Run locally with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

A gate in `main.ts` fails loudly if the line is not a single line or is
outside 1–200 characters, so a bad entry never reaches the judge.
