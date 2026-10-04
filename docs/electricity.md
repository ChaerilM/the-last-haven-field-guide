# Electricity

The electricity system includes:

- Windmill
- Thermal power plant
- Transformer
- Electric pole
- Gravity accumulator
- Building electrical upgrades / panels

## Current working model

Current player testing shows that a Transformer is **not mandatory** for a
basic connection.

Confirmed working topology:

`Windmill -> electrically upgraded building`

A Transformer is therefore best treated as a distribution/splitting device
rather than a required part of every electrical connection.

### Windmill

Generates electricity.

Player-tested behavior:

- A Windmill can connect **directly to an electrically upgraded Factory**
- A Gravity accumulator is **not required** for that direct Windmill-to-building
  connection

The exact electricity output has not yet been found in the UI and remains
unknown.

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

A current player observation suggests the Thermal power plant may only allow
**one outgoing cable**. This is not yet verified and should be retested.

### Transformer

Player-tested network behavior:

- One Transformer can connect to **3 downstream buildings**
- Counting the incoming connection from the power source, this appears to be
  **4 total cable connections/ports**
- A Transformer is **not required** for a direct Windmill-to-building
  connection

An earlier `Windmill -> Transformer -> building` test did not cause the target
building to use electricity, while `Windmill -> Factory` worked directly.
This may indicate a wiring/port issue, a Transformer behavior quirk, or a bug;
the failed Transformer topology should be retested before drawing a stronger
conclusion.

### Cable removal

There does not appear to be a convenient direct "delete cable" control in the
tested UI.

A player-tested workaround is to **dismantle the Transformer repeatedly** to
remove its connected cables. This behavior is awkward and may be an interface
quirk or bug, so save before rewiring a large network.

### Electric pole

Used to route/extend electrical connections over distance.

### Gravity accumulator

The construction tooltip describes it as:

> Potential energy storage device  
> Necessary research: Electricity

Current testing shows that it is **not required** for a direct
`Windmill -> Factory` connection. Its exact storage capacity and
charge/discharge behavior remain unknown.

### Building electrical upgrades

Current screenshots confirm that an electrical upgrade can replace a
building's displayed fuel consumption with electricity:

- **Greenhouse II, unupgraded:** 1 coal shown
- **Greenhouse II, electrically upgraded:** 10 electricity shown
- **Factory I, unupgraded:** 2 coal shown
- **Factory I, electrically upgraded:** 20 electricity shown
- **Factory II, unupgraded:** 3 coal shown

For Factory I, the production window simultaneously showed **150% efficiency**
while producing Armor III. This is recorded as an observation only; more
testing is needed before attributing the 150% efficiency specifically to the
electrical upgrade.

## Open tests

- Windmill electricity output
- Thermal power plant electricity output
- Thermal power plant fuel-consumption time basis
- Verify whether the Thermal power plant is limited to one outgoing cable
- Whether the coal-to-wood fallback changes output or efficiency
- Whether power output changes with worker count
- Why `Windmill -> Transformer -> building` failed while
  `Windmill -> building` worked
- Verify Transformer port/connection limits in different topologies
- Exact wire distance limits
- Gravity accumulator capacity and charge/discharge behavior
- Factory II electricity consumption after electrical upgrade
- Electricity consumption by additional buildings
- Whether electrification changes production speed/efficiency on each building
