# card of the day

a small widget that shows one tarot card each day. it was made for **the high priestess tarot guide**, a notion template, and sits on the guide's home page through a notion embed.

## what it does

- shows one card a day with its art, name and upright key ideas
- everyone sees the same card on the same day
- the card changes at midnight in each viewer's own time zone
- it goes through all 78 cards before any card repeats
- cards are always upright, no reversals

## what's in here

- `index.html` is the whole widget. the card names and key ideas live in the list near the top of the script.
- `images/` holds the 78 card images, named `00.jpg` to `77.jpg` in deck order:
  - 00 to 21: the major arcana, the fool through the world
  - 22 to 35: cups, ace through king
  - 36 to 49: wands, ace through king
  - 50 to 63: swords, ace through king
  - 64 to 77: pentacles, ace through king

## changing the text

open `index.html` and find the card's line in the list. each line is the card name, then its key ideas. keep the quote marks and the comma at the end of the line. the order of the list has to match the image numbers.

## adding it to notion

1. turn on github pages for this repo (settings, then pages, then pick the main branch).
2. copy the link github gives you.
3. in notion, type `/embed`, paste the link and press enter.
4. drag the corners to resize it. about 160 pixels tall fits well.

## credits

card images: the 1909 rider-waite-smith deck, art by pamela colman smith. these images are in the public domain.

## rights

all rights reserved. the code and the written key ideas belong to the creator of the high priestess tarot guide and aren't licensed for reuse. the card art itself is public domain.
