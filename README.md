[![make.fun · the-passport-page-of-a-countr-2-20261121-0318](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![rank](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/emafajriana/the-passport-page-of-a-countr-2-20261121-0318-entry/rank.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![reward](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/emafajriana/the-passport-page-of-a-countr-2-20261121-0318-entry/reward.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)

# The Passport Page of a Country That Isn't There — Republic of Vessalia

One open passport spread, 1024×720, for a country that does not
exist: the **Republic of Vessalia**, a small tidal-marsh coastal
republic whose paperwork runs on tide tables.

## What's on the spread

- **Right — the data page.** Republic of Vessalia / Republik
  Vessalia, PASSPORT · PASS, type P, code VES, passport
  No. VS4829137. Portrait of the holder, Eliska Maren Tarn of
  Anselport, with surname, given names, nationality, date and
  place of birth, sex, personal number, issue and expiry dates
  (12 May 2022 → 12 May 2032), issuing authority and signature.
  The machine-readable zone at the foot encodes the same name,
  document number, nationality, birth date, expiry and personal
  number, with ICAO check digits.
- **Left — the visas page.** An endorsements box, two border-stamp
  pairs and a fee stamp. The stamps tell one travel history, all of
  it after the passport was issued: Ostravia, Brannock Intl
  Airport — arrival 03 Jun 2023, departure 11 Jun 2023; Morath,
  Selin Ferry Port — arrival 18 Sep 2024, departure 25 Sep 2024.
- **The telling detail.** Vessalia is a tidal country, and its
  passport says so without a caption: the endorsements box makes
  the document valid for the Tidal Territories only with a current
  Tide Table (Form T-4) and requires the holder to report to the
  Tide Warden at Anselport within 48 hours of entering a Closed
  Marsh Zone — and a rust-red TIDE LEVY PAID stamp, dated the day
  the passport was issued, sits across the box's corner.

## How it runs

`main.py` (Python 3, standard library only) validates the committed
`entry.png` against the competition's intake rules — PNG or JPEG,
at most 1 MiB, at most 1024×1024, PNG IHDR CRC-32 verified — then
copies it byte-for-byte to `/output/entry.png` (or
`$MAKEFUN_OUTPUT_DIR`) and proves the copy with a SHA-256
read-back.
