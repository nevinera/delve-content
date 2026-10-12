# demo-wild: world plan

A small, wilderness-only test world: three zones, no towns. For exercising the world-building
flow and the tools end to end. Quests are in `quests-plan.md`; each zone has a `zone-plan.md`.

## Forces

- **Wild creatures** in the forest: wolves, big cats, boars, bears.
- **Human camps** in the forest: a ranger outpost, trappers, woodcutters, a prospecting
  expedition. The only quest givers outside the swamp.
- **Lizardfolk** in the swamp, in two tribes: the Reedtalkers (wary, but trade and give quests)
  and the Blackscales (hostile, raiding everyone).
- **Goblins** in the caves: aggressive, raiding the surface on both sides, led by Warboss Grutt,
  who answers to the Goblin King in his hall below.

## Tiers and elevation

One tier, elvl 0-10. Each zone rises with distance from its quest hubs.

| Zone | elvl | Who |
|---|---|---|
| Thornwood | 0-4 | Wild creatures; human camps. The starting zone. |
| Brackwater Mire | 3-7 | Lizardfolk: Reedtalkers and Blackscales. |
| The Gnawdeep | 5-10 | Goblins. |
| Hall of the Goblin King (dungeon) | 10 | The Goblin King and his court. |

No parties: everything is solo or open.

## Connections

- Thornwood and Brackwater Mire connect directly, on three maps: the forest's south and east edges
  run along the mire.
- The Gnawdeep connects to both: a cave mouth in the forest's hills, and a flooded entrance in the
  mire.
- Hall of the Goblin King: a dungeon (private zone) off the Gnawdeep's deepest map.

## Size

Smaller than Valen, as a test world: 6 sizeable maps per zone (100x100 cells or larger), plus a
few small ones.

## Themes

Existing themes cover it: glade and autumn for the forest, glade with the `wet` tag for the mire,
cave for the Gnawdeep. Stamps (#164) and stamp-scenes (#168) would help the camps and the goblin
warrens, but nothing waits on them.

## Unit types and tokens needed

Gathered through planning, for the placement steps. "Exists" means a unit type in the library or
the small world; tokens for new ones come from the token packs (see the content README's
attributions).

| Unit type | Exists | Where | Notes |
|---|---|---|---|
| wolf, dire-wolf | yes | thornwood | |
| panther | yes | thornwood | the black panther (S3) is a named variant |
| boar | yes | thornwood | the boar run (L1) |
| black-bear | yes | thornwood | the bear's den (S4) |
| deer | yes | thornwood | ambient: placed neutral (no flee behavior yet) |
| giant-frog | yes | brackwater-mire | S7 |
| swamp-crocodile | yes | brackwater-mire | the Old Croc (S9) is a named variant |
| swamp-viper | yes | brackwater-mire | replaces the leech swarm (no leech tokens) |
| blackscale-warrior, -hunter, -shaman | yes | brackwater-mire | hostile lizardfolk |
| blackscale-war-shaman | yes | brackwater-mire | named boss (L2) |
| goblin, -archer, -sapper, -hexer, -shaman, -wolfrider, -cutter, -mender, -sneak | yes | thornwood (wolfriders, sneaks), gnawdeep | |
| worg | yes | gnawdeep | the wolf pens |
| goblin-boss | yes | gnawdeep | Warboss Grutt |
| cave-bat, cave-spider | yes | gnawdeep | ambient cave beasts |
| goblin-royal-guard | yes | hall-of-the-goblin-king | elite goblin |
| goblin-king | yes | hall-of-the-goblin-king | dungeon boss |

| NCU | Where | Notes |
|---|---|---|
| Ranger Hale | thornwood | human ranger |
| woodcutters, trappers | thornwood | humans |
| expedition survivors, Maren Holt | thornwood, brackwater-mire, gnawdeep | human prospectors |
| Elder Sesh, Reedtalker villagers and fishers | brackwater-mire | friendly lizardfolk |

Unit-type tokens are done (in the library, unit_types/ and tokens/unit/). Still needed, for NCUs:
humans (ranger, woodcutter, trapper, prospector) and Reedtalker lizardfolk (the green sets).
