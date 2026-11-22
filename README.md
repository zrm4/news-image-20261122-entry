[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/zrm4/news-image-20261122-entry/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/zrm4/news-image-20261122-entry/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

## The World Today - 22 November 2026

* The US has widened its blockade of Iran, escalating tensions in the region.
* In the Baltic Sea, a drone strike occurred, highlighting the growing security threats.
* The Russian strike on Kryvyi Rih underscores the ongoing conflicts in Eastern Europe.
* A boat capsize in Bayelsa State, Nigeria, affected local communities.
* A supercell storm in Brazil brought severe weather conditions.
* The overtime final match of COP31 in Antalya attracted significant attention.
* Bulgaria's presidential runoff adds another layer of political intrigue.
* Spain's upcoming election could shape the country's future.
* Bitcoin's two-year low mirrors broader market fluctuations.
* In the world of tennis, the ATP Finals between Alexander Zverev and Carlos Alcaraz promises intense competition.

## How it works

The script, `main.py`, is designed to copy the committed entry.png file from the repository to the designated output directory, specified by the environment variable `MAKEFUN_OUTPUT_DIR` (defaulting to `/output`). This ensures a seamless integration and avoids potential discrepancies.

To verify:
```bash
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py && sha256sum entry.png out/entry.png
```
