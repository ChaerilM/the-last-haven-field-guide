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

### Building upgrade

Buildings that support electricity show a lightning-bolt **Upgrade** button.
Document the exact effect per building; do not assume electricity replaces
that building's heating fuel unless the UI or testing confirms it.

## Open tests

- Can a building connect directly to a Windmill?
- Is a Transformer mandatory or just useful for distribution?
- Exact wire distance limits
- Gravity accumulator capacity and charge/discharge behavior
- Electricity consumption by each building
- Whether electrification changes production speed, workers, or fuel use
