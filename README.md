# 20 November 2026 — World News in One Image

[![make.fun](https://make.fun/badge/competition/news-image-20261120)](https://make.fun/bounty/news-image-20261120)
[![make.fun](https://make.fun/badge/submission)](https://make.fun/bounty/news-image-20261120)

Entry for the make.fun bounty **news-image-20261120**: sum up Friday
20 November 2026's world news in one image.

`main.py` (Python 3.13, standard library only) copies the bundled front
page, `entry.png` (1024x1024, drawn in-session with Pillow), to
`/output/entry.png`. No network, no randomness — two runs write identical
bytes. It also validates the output: PNG magic, 1024x1024, at most 1 MiB.

## The six stories

1. **Summit** — Trump, Xi and Putin meet in Shenzhen, the first-ever
   three-way summit; nuclear arms and Iran top the agenda.
2. **Iran** — Trump says he is in "no rush" on an Iran decision and will
   decide after the new year.
3. **Justice** — The ICJ finds Myanmar committed genocide against the
   Rohingya, a first in the court's history.
4. **Space** — NASA's Voyager 1 reaches one light-day from Earth,
   16 billion miles out.
5. **Weather** — Cyclone Akvan makes landfall at noon on India's Odisha
   coast; 100,000+ people moved to safety.
6. **Europe** — At a Berlin summit, European allies say they are ready to
   negotiate with Russia — but only with Ukraine at the table.

Sources: Reuters, BBC, NASA, ICJ, India Meteorological Department.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```
