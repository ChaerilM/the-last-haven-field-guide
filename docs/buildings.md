# Buildings and production

This page records current in-game observations for buildings.

## Greenhouse II

Verified in-game observations:

- Worker capacity: **4**
- Unupgraded heating consumption shown: **1 coal**
- Electrically upgraded consumption shown: **10 electricity**
- Observed staffed and operating at **-21 C**

The electrical-upgrade screenshot shows electricity consumption instead of
coal, so the upgrade appears to replace the displayed coal requirement for
Greenhouse II.

The -21 C observation is important because older community material may claim
a stricter temperature cutoff. Treat current in-game behavior as the baseline
and continue testing lower temperatures.

## Kitchen

Verified in-game observations:

- Worker capacity: **4**
- Consumption shown while operating:
  - **1 coal**
  - **4 food**
- No manual recipe queue was visible in the inspected building panel.

The Kitchen appears to process food automatically while staffed and supplied.

## Thermal power plant

Current in-game observations:

- Worker capacity: **4**
- Normal consumption shown: **10 coal**
- When coal is unavailable, consumption switches to **10 wood**

Screenshots show the building displaying `-10` with the coal icon in one
state and `-10` with the wood/plank icon in another. Gameplay observation
indicates that wood is the fallback fuel when coal is unavailable.

The exact consumption period is not yet verified.

There is also an unverified player observation that the Thermal power plant
may only allow one outgoing electrical cable.

## Factory I

Verified in-game observations:

- Worker capacity: **4**
- Unupgraded consumption shown: **2 coal**
- Electrically upgraded consumption shown: **20 electricity**
- Production window showed **150% efficiency** while producing Armor III

Do not yet assume that electricity alone causes the 150% efficiency; other
research/upgrades may also contribute.

## Factory II

Verified in-game observations:

- Worker capacity: **4**
- Unupgraded consumption shown: **3 coal**

The electrically upgraded consumption value has not yet been captured.

Factory II should be tracked separately from Factory I rather than treated as
a straight replacement, because their production lists differ.

## Science Center

Once all research is completed, staffed Science Centers have little remaining
research value. Workers can be reassigned. Keep one unstaffed if desired for
future testing or game updates.

## Cemetery

Verified in-game construction tooltip:

- Construction: **70 wood, 20 stone, 10 metal**
- Capacity: **18 bodies**
- Worker capacity: **1**
- Collects corpses **across the entire map**

This is a burial building, not a repeatable Stability source when no
inhabitants are dying. The tooltip does not give a burial-to-Stability value.

## Resource Station

Verified in-game construction tooltip:

- Construction: **20 wood, 10 metal**
- Worker capacity: **4**
- Collectors gather **almost all types of resources** within the station's
  local area
- Placement is restricted to locations near collectible resources

The tooltip does not establish which specific resources are collectible.
Exact stone-gathering/depletion behavior remains an open test.

## Stone Crusher

Dedicated stone/rock production building. Record deposit behavior, output
rate, workers, and resource exhaustion separately from Resource Stations.
