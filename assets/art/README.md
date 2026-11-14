# The Governance Deck — Art Assets

**Style decision:** the deck's identity is the night-and-gold boardroom —
institutional where the Judgement Deck is personal (brass-lamp desk) and the
Adoption Deck is organisational (sage daylight). All generated art uses the
locked **boardroom chiaroscuro** identity. Every prompt starts with this
canonical prefix:

```
moody institutional photograph, dark formal boardroom at night, deep charcoal
and walnut palette, dramatic chiaroscuro, a single warm gold glow as the only
color accent, soft film grain, dignified minimal composition, generous dark
negative space
```

Every prompt ends with:

```
no text, no letters, no words
```

Card faces stay typographic; art lives on the box, the back, the banner and
the art-edition banner zone.

## Regenerating

```sh
limn generate -s 768x1024 -o assets/art/cover.png "<prefix>, <subject>, no text, no letters, no words"
```

Provider: the default SwarmUI (`juggernautXL_v9`). Each `.png.json` sidecar
records the exact prompt and parameters.

## Files

| File | Use | Subject |
|---|---|---|
| `cover.png` | Box front, landing hero art | Long boardroom table at night, brass lamp, single report under gold light, empty high-backed chairs |
| `back.png` | Deck back when printed double-sided | Charcoal and gold linework; central emblem is a fluted column and balanced beam medallion |
| `banner.png` | Social preview, landing banner | Down the length of the boardroom table, cards in five ordered rows |

## ill/ — the concept-keyed vignette library

Five landscape vignettes, one per section, keyed by concept. The art edition
tints each in its section colour at render time (CSS hue-rotate from a sepia
base): gold The Line, navy Oversight, teal Data, slate Vendors, coral Learning.

| File | Section | Subject |
|---|---|---|
| `line.png` | The Line | Brass fountain pen on the signature fold of a document |
| `oversight.png` | Oversight | Four ascending marble steps, gold lamp at the top |
| `data.png` | Data | Brass lock and keys beside a leather document case |
| `vendors.png` | Vendors | Two chairs facing across a table, one folder between them |
| `learning.png` | Learning | Brass-framed hourglass, gold sand in low lamplight |
