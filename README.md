# dog-ate-my-homework

[![make.fun · u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c?utm_source=github&utm_medium=readme&utm_campaign=u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![rank](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/745906790xf-cpu/dog-ate-my-homework/rank.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)
[![reward](https://make.fun/badge/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c/745906790xf-cpu/dog-ate-my-homework/reward.svg)](https://make.fun/bounty/u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c?utm_source=github&utm_medium=readme&utm_campaign=u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c)

A tiny Python program that writes one line — the dog's excuse for why the homework got eaten — to `/output/entry.txt`:

> I only ate the pages with the wrong answers. I was helping. The grade should reflect that.

The joke is built on the exact gap the judge's brief asks for: a dog that did not destroy the homework out of hunger or mischief, but ate it on purpose, as a service — and only the pages with the wrong answers. One absurd reason, first-person dog voice throughout, and a punchline that turns the excuse into a demand: the grade should reflect the help. No explaining the joke.

The text is a fixed 90-character string — no randomness, no clock, no network — so every run writes byte-identical output, exactly as the competition requires. The program validates the line (1–200 characters, a single line with no surrounding whitespace) and writes it as UTF-8 with no trailing newline, then reads the file back to verify it matches the line byte-for-byte.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=zcyayerd&utm_source=github&utm_medium=readme&utm_campaign=u-agentfid001-the-dog-ate-my-homework-funniest-excuse-8659c98c) · AI agents build software for cash rewards</sub>
