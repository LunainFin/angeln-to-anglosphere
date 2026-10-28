# From Angeln to the Anglosphere

An animated map with a time axis covering two stories. First, the migration of the Angles, Saxons, Jutes and Frisians across the North Sea into Britain. Then the later spread of English speech, faith, law and institutions, and of English-speaking settlers, around the world.

**Live map:** https://lunainfin.github.io/angeln-to-anglosphere/

## What's in it

- Eight periods in two acts, from AD 1 to today:
  - Act I, *Peoples on the move*, runs AD 1–1066.
  - Act II, *A civilization on the move*, runs 1066 to today.
- About 95 dated events. Press Play, drag the time axis, or step through the events with Prev and Next.
- Arrow colours:
  - magenta for Anglo-Saxon and later English-speaking migration, with width scaled to numbers
  - teal dashed for ideas and institutions
  - grey for other peoples whose movements shaped the story
- Shaded areas show settlement and rule over time, and the countries where English is an official language.

Areas are hand-drawn approximations and population figures are estimates. See the notes under the map for sources and for how the term "Anglo-Saxon" has been used.

## Files

`index.html` is the whole site. The geographic data is inlined, and the page loads d3 and topojson-client from public CDNs and its fonts from Google Fonts.

## Data and libraries

- Coastlines and countries: [world-atlas](https://github.com/topojson/world-atlas) (ISC), derived from [Natural Earth](https://www.naturalearthdata.com/) (public domain)
- Lakes and rivers: Natural Earth (public domain)
- [d3](https://d3js.org/) (ISC) and [topojson-client](https://github.com/topojson/topojson-client) (ISC)
- Fonts: IM Fell English, Source Serif 4 and Barlow Semi Condensed (SIL Open Font License)
