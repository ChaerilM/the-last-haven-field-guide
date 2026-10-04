# Electricity

The electricity system includes:

- Windmill
- Thermal power plant
- Transformer
- Electric pole
- Gravity accumulator
- Building electrical upgrades / panels

## Current working model

Treat this as a testable model, not a finished specification:

`generator -> transformer/distribution -> poles/wires -> upgraded building`

### Windmill

Generates electricity.

### Thermal power plant

Current in-game observations:

- Worker capacity: **4**
- Normal consumption shown: **10 coal**
- If coal is unavailable, the plant can fall back to **10 wood**
- The UI changes the displayed consumption icon from coal to wood when using
  the fallback fuel

The screenshots show the same Thermal power plant displaying `-10` coal in
one state and `-10` wood in another. The fallback behavior was then confirmed
through gameplay observation.

The exact time basis for the displayed `10` consumption is still not
documented, so do not label it as "per hour" until verified.

### Transformer

Used as part of the electricity distribution network.

### Electric pole

Used to route/extend electrical connections over distance.

### Gravity accumulator

The construction tooltip describes it as:

> Potential energy storage device  
> Necessary research: Electricity

This suggests storage/buffering rather than being required for basic
generation.

### Building electrical upgrades

Current screenshots confirm that an electrical upgrade can replace a
building's displayed fuel consumption with electricity:

- **Greenhouse II, unupgraded:** 1 coal shown
- **Greenhouse II, electrically upgraded:** 10 electricity shown
- **Factory I, electrically upgraded:** 20 electricity shown

For Factory I, the production window simultaneously showed **150% efficiency**
while producing Armor III. This is recorded as an observation only; more
testing is needed before attributing the 150% efficiency specifically to the
electrical upgrade.

## Open tests

- Thermal power plant electricity output
- Thermal power plant fuel-consumption time basis
- Whether the coal-to-wood fallback changes output or efficiency
- Whether power output changes with worker count
- Can a building connect directly to a Windmill?
- Is a Transformer mandatory or just useful for distribution?
- Exact wire distance limits
- Gravity accumulator capacity and charge/discharge behavior
- Electricity consumption by additional buildings
- Whether electrification changes production speed/efficiency on each building
