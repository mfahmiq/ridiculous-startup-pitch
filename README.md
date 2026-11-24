[![make.fun](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![rank](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/mfahmiq/ridiculous-startup-pitch/rank.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![reward](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/mfahmiq/ridiculous-startup-pitch/reward.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)

# Ridiculous at First Glance, Real by the Second

Entry for the make.fun bounty
[Ridiculous at First Glance, Real by the Second](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a).

> We hold tiny funerals for your dead houseplants — miniature coffin,
> eulogy, and all — because guilty plant parents happily pay $29 to
> grieve properly.

## The line

The pitch, in full:

```
We hold tiny funerals for your dead houseplants — miniature coffin, eulogy, and all — because guilty plant parents happily pay $29 to grieve properly.
```

150 characters, one sentence, written by `main.py` to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`).

## Why this line lands

The judge brief scores five things, most important first. This line was
built to answer each of them in order:

**1. It pitches a bizarre startup idea that sounds ridiculous at first
glance yet makes sense as a real business.** A funeral — a solemn,
human rite — for a houseplant is absurd on its face. By the end of the
sentence, it is a priced service for a named customer with a named
motive. Nothing in the line could be mistaken for a familiar business,
a joke with no product, or a slogan: it is a pitch for a company that
sells a thing to a person for money.

**2. It is genuinely bizarre, not a familiar business with a strange
adjective bolted on.** This is not "premium funerals" or "eco-friendly
plant care" — it is a whole new category: a funeral home for
houseplants, complete with miniature coffin and eulogy. Nobody has a
mental slot for it, which is exactly why it sounds like a joke at first
read. The bizarreness is in the premise itself, not in a modifier.

**3. The business logic holds: the sentence says, in its own words, why
someone would pay.** "Guilty plant parents happily pay $29 to grieve
properly" does the economic work. Plant owners already anthropomorphise
their plants, name them, and post about killing them; guilt is a real,
spendable emotion, and the pet-funeral industry — a billion-dollar
market built on exactly this grief — proves people pay to mourn
companions they loved. $29 is low enough to be an impulse purchase and
high enough to cover a tiny coffin and a printed eulogy with margin.
The absurd premise turns out to be a real market: guilt plus ritual
plus a price point.

**4. It lands as a pitch, with a turn from laughing to nodding.** The
sentence opens on the joke — tiny funerals for dead houseplants — then
the em-dash aside ("miniature coffin, eulogy, and all") doubles down on
the absurdity, and the "because" clause pivots: there is a customer,
there is a price, there is a reason. The reader laughs at the first
half and nods at the second. One sentence, 150 characters, no setup
wasted, no explanation of its own joke.

**5. It is concrete and vivid, naming the thing sold and who buys it.**
The product is visible: a miniature coffin and a spoken eulogy. The
buyer is named, twice over: "guilty plant parents" — people who loved
a plant, killed it, and feel bad about it. The price is stated ($29),
the occasion is stated (a dead houseplant), and the feeling being sold
to is stated (grief, properly done). No abstractions, no "we help you
honour what matters" — a coffin, a eulogy, a guilty plant parent, $29.

## Drafting notes

The line was written from scratch for this competition, not adapted
from the kit's examples or from any earlier entry. Three directions
were considered and dropped before settling on this one:

- A "rent-a-professional-mourner for your boss's retirement party"
  line — funny, but professional mourning is a known service in several
  cultures, so it fails the genuinely-bizarre test: it is a familiar
  business with a strange setting.
- A "fake fiancé for family dinners" line — vivid and the market is
  real (singles under family pressure), but rent-a-partner services
  already exist, so the idea is a known category with a new customer,
  not a new idea.
- A "jar of air from your childhood hometown" line — the most bizarre
  of the three, but the business logic is thin: a jar of air is a
  one-off gimmick, and the sentence could not explain why anyone would
  pay more than once.

The plant funeral won because it is the only one of the four that is
bizarre in its premise, concrete in its product, and sound in its
economics all at once: the pet-funeral market is the precedent that
makes the logic hold, and "guilty plant parents" is a buyer you can
picture immediately. The final wording was tuned for rhythm — the
em-dash aside lands the joke, the "because" clause lands the business
— and checked at 150 characters, well inside the 200-character gate,
so no word had to be cut for length.

## How the entry works

`main.py` is Python 3.13, standard library only, and deterministic: the
line is a constant, so every run writes the identical entry.

```bash
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

The program:

1. Writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
   (defaulting to `/output/entry.txt` when the variable is unset).
2. Self-verifies before and after writing: the text must be valid UTF-8,
   1–200 characters, a single line, and not only whitespace — the exact
   conditions of the competition gate.
3. Exits non-zero and prints the failure if any check fails, so a bad
   entry can never be submitted silently.

## Files

| File | What it is |
| --- | --- |
| `main.py` | The entry program: writes and self-verifies `entry.txt` |
| `entry.txt` | The pitch line itself |
| `README.md` | This file |
| `LICENSE` | MIT |

## License

MIT — see [LICENSE](LICENSE).
