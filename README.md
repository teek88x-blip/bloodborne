# Bloodborne Compendium

A companion app for watching a Bloodborne playthrough. Built as a static GitHub Pages site.

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Hub — links to all sections |
| `compendium.html` | Full reference: primer, progress, NPCs, bosses, bestiary, locations, glossary, timeline, quest tracker, session log, journal |
| `connection-map.html` | Interactive node graph of all characters and factions |
| `games/quiz.html` | 20-question lore quiz, scored in Insight |
| `games/journal.html` | Branching text adventure, 3 endings |
| `games/insight.html` | Card-drafting roguelike — don't lose your mind |
| `games/gamble.html` | Blood Echo dice gamble with banking |

## Art Assets

Place art images in `assets/art/`. Each image is named `[slug]-art.png`.

Images display inside the expanded card for each entry. If the file is missing, a placeholder shows the expected filename.

### NPC Slugs
`gehrman`, `the-doll`, `gilbert`, `eileen`, `violas-daughter`, `lonely-old-woman`,
`oedon-chapel-dweller`, `alfred`, `arianna`, `sister-adella`, `djura`, `iosefka`,
`master-willem`, `annalise`, `valtr`, `simon`, `lady-maria`, `brador`

### Boss Slugs
`cleric-beast`, `father-gascoigne`, `blood-starved-beast`, `witch-of-hemwick`,
`vicar-amelia`, `darkbeast-paarl`, `shadows-of-yharnam`, `rom`, `the-one-reborn`,
`amygdala`, `celestial-emissary`, `ebrietas`, `micolash`, `mergos-wet-nurse`,
`gehrman-boss`, `moon-presence`, `ludwig`, `laurence`, `living-failures`,
`lady-maria-boss`, `orphan-of-kos`

### Enemy Slugs
`yharnam-villagers`, `werewolves`, `scourge-beasts`, `church-giants`,
`afflicted-villagers`, `bloodletting-beasts`, `church-servants`, `hemwick-grave-women`,
`snatchers`, `vileblood-servants`, `pthumerian-descendants`, `mad-ones`,
`cainhurst-ghosts`, `amygdalae`, `brainsuckers`, `brain-of-mensis`

### Location Slugs
`hunters-dream`, `central-yharnam`, `cathedral-ward`, `old-yharnam`,
`healing-church-workshop`, `hemwick-charnel-lane`, `forbidden-woods`,
`cainhurst-castle`, `hypogean-gaol`, `byrgenwerth`, `yahargul`,
`nightmare-frontier`, `lecture-building`, `upper-cathedral-ward`,
`nightmare-of-mensis`, `hunters-nightmare`, `research-hall`, `fishing-hamlet`

## Features

- **Progress gating** — lore entries unlock as you update the Progress tab
- **DLC toggle** — shows/hides all DLC content globally
- **Dark/light theme** — persists to localStorage
- **Quest tracker** — step-by-step NPC questlines with missable warnings
- **Session log** — record each viewing session
- **All state persists** — progress, quests, recaps, and journal survive page reloads

## GitHub Pages

Push to `main`. Enable GitHub Pages from repo Settings → Pages → Deploy from branch.

