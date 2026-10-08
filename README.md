# The Last Haven Field Guide

A community-maintained, versioned reference for **The Last Haven** by Thunder Devs.

The goal is to document information that is missing, outdated, or difficult to find elsewhere: exact weapon stats, ammo types, production costs and times, building costs and consumption, research unlocks, laws, electricity, food systems, and practical settlement mechanics.

> **Current data baseline:** game version **v5.09.13** unless a page says otherwise.

## What belongs here

- **Weapons** — ammo type, damage, range, accuracy, production cost/time, merchant price, role
- **Buildings** — build cost, workers, consumption, heating/electricity behavior, capacity
- **Food** — greenhouse tiers, kitchens, farms, livestock, production chains
- **Electricity** — generators, transformers, poles, accumulators, electrical upgrades
- **Research** — prerequisites, unlocks, research time
- **Laws** — branch order, cost, effects
- **Resources** — sources, consumers, storage, merchant value
- **Mechanics** — stability, radiation, prisoners, reload/rearm behavior, pathing observations
- **Layouts** — tested settlement layouts and production ratios

## Data quality

This project favors **current in-game observations** over old wiki pages.

Every numeric value should be tagged with a source status:

- **Verified in-game** — read directly from a current tooltip/panel
- **Patch notes** — stated by Thunder Devs
- **Player-tested** — reproduced in gameplay but not shown directly in UI
- **Unverified** — useful lead that still needs confirmation

When the game UI disagrees with an old guide or patch note, record the in-game value and note the version tested.

## Quick start

- [Weapon reference](docs/weapons.md)
- [Building & production notes](docs/buildings.md)
- [Electricity](docs/electricity.md)
- [Food & kitchens](docs/food.md)
- [Law reference](docs/laws.md)
- [Contributing](CONTRIBUTING.md)

Structured data lives in `data/` so it can later power tables, a static site, or tooling, including `weapons.csv`, `buildings.csv`, `building_costs.csv`, and `laws.csv`.

## Contributing

Screenshots of tooltips are especially useful. Please include the **game version** whenever possible.

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Original documentation and community-created data in this repository are licensed under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** unless otherwise noted.

Game screenshots, icons, logos, artwork, and other assets from **The Last Haven** are property of Thunder Devs and/or their respective rights holders and are **not** relicensed by this repository.

This is an unofficial community project and is not affiliated with Thunder Devs.
