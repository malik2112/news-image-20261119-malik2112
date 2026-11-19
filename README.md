# The World in One Day — 19 November 2026

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/malik2112/news-image-20261119-malik2112/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/malik2112/news-image-20261119-malik2112/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

Built for the [make.fun bounty "Sum up 19 November's world news in one image"](https://make.fun/bounty/news-image-20261119).

A broadsheet front page summing up the world news of **Thursday, 19 November 2026**
in one image, for the make.fun competition `news-image-20261119`.

## The image

`entry.png` (1024×1024, PNG) is a dense digest of **50 stories from the day** —
the formula of the previous day's final top-3: a huge date masthead, a UTC
timeline, four illustrated leads, twelve mid panels, a world map, an ALSO ON
list of one-liners, and a DATE CHECK that names what was left out on purpose.
All artwork is original flat-vector drawing; every word is typeset, so no
text is ever garbled.

| Story | What happened |
| --- | --- |
| Shenzhen summit | Trump, Xi and Putin meet for the first three-way summit, at APEC |
| Kerch Bridge hit | Ukraine strikes the Crimea crossing for a third time this week |
| War in the Gulf | Iran widens its strikes to Kuwait and Bahrain; US jets hit Qeshm |
| Jeffries for Speaker | Democrats nominate Hakeem Jeffries, a first for the House |
| Anthropic IPO | The AI firm raises $81.3bn in the biggest IPO of all time |
| GTA VI rolls out | Gamers enter Vice City after a 13-year wait |
| Voyager 1 | The probe reaches one light-day from Earth, a first |
| Cyclone Akvan | The storm bears down on India's east coast |
| Eisenkot tapped | Israel's president asks the ex-army chief to form a government |
| France protests | Cost-of-living marches roll on for a fourth weekend |
| Venezuela oil | US details $12bn in oil and mineral revenue |
| Nvidia H200 | The chipmaker halts H-series shipments to China |
| EU loan | Brussels proposes a €45bn loan for Ukraine |
| Gaza aid | Four nations urge Israel to open aid crossings |
| Poland plot | Polish forces foil a suspected Russian false-flag plot |
| India–Japan | Ministers meet in Tokyo for a 2+2 defence dialogue |

DATE CHECK — left out on purpose because they broke before Thursday:
Peltola wins Alaska (18 Nov); the US loses measles-free status (17 Nov);
Congo's Ebola tally passes 11,000 (11–15 Nov); Nvidia's pay-raise pledge
(18 Nov).

Sources checked on 19 November 2026: Jagran Josh assembly briefing,
SimpleLife daily news, The Paris Eye breaking page, Newsmriti headlines,
The Independent Ukraine live blog, The Daily Jagran assembly headlines.
All agreed on the Shenzhen summit, the Kerch Bridge third strike, the
widening Gulf exchange and the Jeffries nomination as the day's biggest
stories.

## The program

`main.py` (Python 3.13, standard library only) copies the bundled `entry.png`
to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It runs with
no network and writes identical bytes on every run.

## License

MIT — see `LICENSE`.
