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

Verified in-game observations:

- Worker capacity: **4**
- Observed at **4/4** workers
- Consumption shown: **10 wood**

The UI displays the wood value as `-10`. The exact time basis for this
consumption is not yet documented, so do not label it as "per hour" until that
is verified in-game.

> Earlier documentation in this repository incorrectly identified the icon as
> coal. The clearer current screenshot shows the wood/plank icon.

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
- Thermal power plant wood-consumption time basis
- Whether power output changes with worker count
- Can a building connect directly to a Windmill?
- Is a Transformer mandatory or just useful for distribution?
- Exact wire distance limits
- Gravity accumulator capacity and charge/discharge behavior
- Electricity consumption by additional buildings
- Whether electrification changes production speed/efficiency on each building
