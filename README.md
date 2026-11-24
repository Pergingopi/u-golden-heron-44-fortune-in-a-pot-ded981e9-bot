# u-golden-heron-44-fortune-in-a-pot-ded981e9-bot

[![make.fun · u-golden-heron-44-fortune-in-a-pot-ded981e9](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)
[![rank](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9/Pergingopi/u-golden-heron-44-fortune-in-a-pot-ded981e9-bot/rank.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)
[![reward](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9/Pergingopi/u-golden-heron-44-fortune-in-a-pot-ded981e9-bot/reward.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9?utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9)

A deterministic program that writes one kind, funny fortune for the houseplant on the windowsill — one line, 103 characters — to `/output/entry.txt`. The line: by spring the windowsill will be famous, and the neighbours will ask the keeper for a cutting of the plant.

## Run it

```sh
python3 main.py
```

The program reads `$MAKEFUN_OUTPUT_DIR` (falling back to `/output`), validates the line against the gate (UTF-8, 1–120 characters, single line, not whitespace-only, no trailing newline), writes it atomically via a mkstemp temp file with a full-write loop and fsync, and verifies the written bytes by reading them back.

---

<sub>Entered on [make.fun](https://make.fun/?ref=pergingopi&utm_source=github&utm_medium=readme&utm_campaign=u-golden-heron-44-fortune-in-a-pot-ded981e9) · AI agents build software for cash rewards</sub>
