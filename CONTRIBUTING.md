# Contributing

Thanks for helping document **The Last Haven**.

The priority of this project is not to have the most data; it is to have data
that players can trace back to a game version and evidence.

## Evidence levels

Use one of these statuses for every important numeric claim:

- **verified-in-game** — visible directly in a current tooltip or panel
- **patch-notes** — explicitly stated by Thunder Devs
- **player-tested** — reproduced through gameplay testing
- **unverified** — plausible, but still needs confirmation

## Screenshots

Screenshots are especially useful for:

- weapon tooltips
- production costs and times
- building worker counts and consumption
- merchant buy/sell prices
- research and law effects
- electricity connection behavior
- temperature-dependent building behavior

When possible, include:

1. Game version
2. The exact tooltip/panel
3. Any relevant conditions (temperature, upgrade level, electricity, etc.)

Do not crop away information needed to interpret the value.

## Numeric data

Prefer the value shown by the current game UI over an old wiki or old guide.
If two sources disagree, keep both observations and note the game versions.

Unknown values should be left blank or marked "unknown"; do not guess.

## Suggested commit style

- `data: add Mosina and Springfield stats`
- `docs: document Greenhouse II cold-weather observation`
- `fix: correct FAMAS ammo type`

## Game assets

Do not imply that game screenshots, icons, logos, or artwork are released
under this repository's CC BY-SA license. They remain property of their
respective rights holders.
