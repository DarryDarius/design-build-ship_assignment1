# Process log

Notes on each batch: what we tried, what I kept, what I dropped, and why.

## Decisions so far (mine)
- **Idea:** Claude proposed three (First Winter guide, Hyde Park dumpling supper club, sunrise run club) with a comparison. I picked First Winter Club because it's the least likely to collide with classmates, has the widest visual range ("cold" can be a weather alert, a diary, a manual...), and the visitor is very specific.
- **Primary action:** join the club + get the free First Winter Checklist.
- **Wide directions:** Claude proposed 16. I chose 12: NWS alert, expedition journal, assembly manual, civil defense, weather app, newspaper, brutalist manifesto, warm letter, 90s GeoCities, terminal, gear catalog, transit map.

## Batch 1 (v01–v04): eras and official voices
- v01 NWS alert: teletype bulletin, alert banners, live wind chill chart (real NWS formula).
- v02 Expedition journal: first-person 1910s diary, hand-drawn map, provisions list.
- v03 Assembly manual: almost wordless, parts A–F, nine line-drawn steps.
- v04 Civil defense: two-color halftone pamphlet, "Layer and Cover!", warming-shelter sign.

**My take:** _TODO: which one would make a new student from a warm city want to join? What's worth keeping?_

## Batch 2 (v05–v08): interfaces and tones
- v05 Weather app · v06 Newspaper front page · v07 Brutalist manifesto · v08 Warm single-column letter

**My take:** _TODO_

## Batch 3 (v09–v12): internet culture and systems
- v09 90s GeoCities · v10 Terminal / CLI · v11 Outdoor gear catalog · v12 Transit map

**My take:** _TODO_

## Narrowing (after v12)
Claude proposed two convergence plans with a side-by-side comparison:
- **Plan 1, "warm gear guide":** v11 catalog layout + v08 letter voice + v05/v01 wind chill tools.
- **Plan 2, "winter gazette":** v06 newspaper + v07 brutalist headlines + v12 departures board.

**I chose Plan 1 (Claude's recommendation).** The reasoning: a nervous first-winter student needs reassurance and a list they can act on. Plan 1 gives both: a senior student's voice that says "I've been there," and catalog cards that say exactly what to buy and where to get it cheap. Plan 2 is more striking, but it reads as showing off, it can feel alarming, and a multi-column newspaper is hard to use on a phone.
- **Dropped:** v09 GeoCities and v10 terminal (too noisy or too technical for this visitor), v04 civil defense and v07 brutalist (tone too alarming), v06 newspaper (too dense on mobile).
- **Guardrail so it doesn't end up generic:** keep the first-person narrator (Meera, from v08) and the "product spec card" idiom (from v11) all the way to v25.

## Batch 4 (v13–v15): three ways to combine
- v13 Catalog first: v11 layout, opened and annotated by Meera's notes.
- v14 Letter first: v08 single column, with v11 spec cards set into the letter.
- v15 Side by side: Meera's letter in a sticky left column, the catalog and the v05 wind chill tool on the right.

**My take:** _TODO_

**Chose v15 (Claude's recommendation).** "Company on the left, checklist on the right" is the clearest form of why I picked Plan 1: reassurance and something actionable, side by side. It's also the least likely to look like anyone else's page. v13 was the easiest to scan but closest to a generic product page. v14 was the warmest, but the practical info was buried in the story. v15's weak spot is mobile: the halves stack and the sync is lost. That becomes the problem for the next batch.

## Batch 5 (v16–v19): four variations on v15
- v16 Mobile fix: on phones, Meera's letter becomes a small synced "Meera says" card that follows you through the catalog.
- v17 Lead with Meera: the first screen is her, not the product cover.
- v18 Shorter page with a sticky checklist CTA: about 30% shorter, and the checklist is always one tap away.
- v19 Cold night palette: facts in cold navy and ice, and warm color only where people are (Meera, the club).

**My take:** _TODO_
