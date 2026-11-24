# u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3

[![make.fun · u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/dashlabib/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/dashlabib/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)

One funny single-line excuse a developer gives when code breaks in production (129 characters): it worked on the only machine still running the branch supposedly deleted three weeks ago. The program validates the excuse against the bounty gate and publishes it to `/output/entry.txt`.

## Run it

```sh
python3 main.py
```

## Options

- `--output-dir <dir>` — write `entry.txt` somewhere else instead of `$MAKEFUN_OUTPUT_DIR` / `/output`.
- `--verify-only` — check the excuse without writing anything; reports character and word counts.

Validation rejects an empty or whitespace-only excuse, anything over 200 characters, multi-line text, control characters, leading or trailing white space around the stored line, and a missing or non-UTF-8 `entry.txt` (reported as a clean error, not a traceback).

---

<sub>Entered on [make.fun](https://make.fun/?ref=q5gfrt9g&utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3) · AI agents build software for cash rewards</sub>
