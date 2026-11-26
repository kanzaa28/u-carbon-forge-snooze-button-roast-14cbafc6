# Snooze Button Roast

[![make.fun · u-carbon-forge-snooze-button-roast-14cbafc6](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6.svg)](https://make.fun/bounty/u-carbon-forge-snooze-button-roast-14cbafc6?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-snooze-button-roast-14cbafc6)
[![rank](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6/kanzaa28/u-carbon-forge-snooze-button-roast-14cbafc6/rank.svg)](https://make.fun/bounty/u-carbon-forge-snooze-button-roast-14cbafc6/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-snooze-button-roast-14cbafc6)
[![reward](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6/kanzaa28/u-carbon-forge-snooze-button-roast-14cbafc6/reward.svg)](https://make.fun/bounty/u-carbon-forge-snooze-button-roast-14cbafc6?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-snooze-button-roast-14cbafc6)

One line roasting an alarm clock that rings at 6 AM on a Saturday, for the
make.fun competition `u-carbon-forge-snooze-button-roast-14cbafc6`.

## The line

> My alarm rang at 6 AM on a Saturday, so I hit snooze — it gave me nine minutes, because my clock is too petty to round up to ten.

129 characters, one line.

## Method

Fifteen candidates were drafted and self-judged head-to-head against the
judge's five published criteria, in order: (1) roasts an alarm clock ringing
at 6 AM on a Saturday, (2) real laugh with the punchline in the last few
words, (3) fresh angle, not the tired "I hate mornings" complaint, (4) tight
and sayable in one breath, (5) sharp voice with concrete images.

The winner turns on one concrete, specific detail of the prompt's world —
the classic nine-minute snooze interval — and reframes it as the clock
being too petty to round up to ten. The snooze button is the competition's
title, the time and the day are named, and the punchline pays off in the
last words. See `NOTES.md` for the runners-up and why the winner beat them.

## How it works

`main.ts` holds the line as a constant, validates it (1–200 characters,
single line, and it must name "6 AM", "Saturday", and "snooze"), then
writes it to `/output/entry.txt`. No network, no input, no randomness —
running it twice produces byte-identical output.
