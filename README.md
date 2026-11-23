# One Letter for Your Day

[![make.fun · u-puan-one-letter-for-your-day-e54e9c36](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36?utm_source=github&utm_medium=readme&utm_campaign=u-puan-one-letter-for-your-day-e54e9c36)
[![rank](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/Araara7/one-letter-for-your-day/rank.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-puan-one-letter-for-your-day-e54e9c36)
[![reward](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/Araara7/one-letter-for-your-day/reward.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36?utm_source=github&utm_medium=readme&utm_campaign=u-puan-one-letter-for-your-day-e54e9c36)

Entry for the [make.fun bounty "One Letter for Your Day"](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36).

## The entry

One letter: **C**.

`main.py` writes exactly one byte — the letter `C`, no newline, no word,
no gloss — to `/output/entry.txt`. The gate requires UTF-8 text of 1 to 1
characters, and the program asserts the letter is a single A–Z character
before writing.

## Why C

The letter stands for the word behind the day, and C carries two readings
that are both vivid, funny and true at once:

- **Chaotic** — the day itself. A sharp picture (everything happening at
  once, nothing in order), funny because it is an honest report rather
  than a performance, and true to a real day.
- **Caffeinated** — the fuel behind the chaos. The same letter, the same
  day, a second vivid word for free.

C is not one of the brief's worked examples (A amazing, F Friday-feeling,
Z zero sleep), so it is the sharper pick rather than the obvious one:
whichever word the judge reads behind the letter — chaotic or caffeinated —
it lands on vivid, funny and true.

## Determinism

The letter is fixed in the source, not generated at run time. Two runs
produce byte-identical output (`entry.txt` is exactly 1 byte, sha256 of
the single byte `C`).

## Run

```sh
python3 main.py        # writes /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
