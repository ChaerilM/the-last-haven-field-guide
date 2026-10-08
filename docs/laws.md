# Laws

> Data baseline: **v5.09.13**, based on player-submitted in-game tooltips unless otherwise stated.
> Costs and effects can change with game versions.

## Verified law tooltips

| Branch | Law | Law points | Exact effect shown | Evidence |
|---|---|---:|---|---|
| Dictatorship | Carrot and stick | 100 | Reduces prisoner death chance by 50% | In-game tooltip |
| Dictatorship | Steady hand | 175 | Increases stability gain by 30% | In-game tooltip |
| Dictatorship | Military trade reputation | 200 | Reduces resource purchase price by 10% and increases military items sale price by 10% | In-game tooltip |
| Dictatorship | Church blessing | 250 | Church increases resource output by 25% | In-game tooltip |
| Authority | Sociological research | 100 | Increases law points gain by 10% | In-game tooltip |
| Authority | Eloquence | 125 | Reduces dealer prices by 10% | In-game tooltip |
| Authority | Mining trade reputation | 150 | Reduces military items purchase price by 10% and increases resource sale price by 10% | In-game tooltip |
| Authority | Negotiation | 175 | Raiders require 25% fewer resources | In-game tooltip |
| Authority | Good conditions | 200 | 15% more settlers join the settlement | In-game tooltip |
| Authority | Church doctrine | 250 | Increases stability gain from the church by 30% | In-game tooltip |

In the 5.09.13 official balance notes, **Church blessing** is listed under
**Dictatorship** and **Church doctrine** under **Authority**. Their effects
are different: Church blessing improves *resource output*, not Stability gain.

## Stability strategy

**Steady hand** is a broad gain modifier (+30% Stability gain).
**Church doctrine** is specifically a modifier to Stability gain *from Church*
(+30%). Neither tooltip says it independently produces positive Stability.

The in-game tooltips do **not** specify how these bonuses stack, or whether
Steady hand applies to Church gain. The effective combined multiplier remains
unverified.

A historical developer update confirmed that the Church could increase
Stability and that having a Ministry increased the Church's Stability gain.
The present-day base rate and the specific building/research conditions still
need an in-game test.

### Path toward Steady hand

The in-order Dictatorship sequence in v5.09.13 is:

1. Political studies — first law (already adopted in the submitted screenshot)
2. Carrot and stick — **100**
3. Betting on the police — **125** (cost from developer patch notes; exact tooltip effect not yet verified)
4. Steady hand — **175**

If Political studies is already adopted, the remaining listed cost is
**400 Law Points**. Carrot and stick on its own does not increase Stability;
it reduces prisoner death chance.

**Church doctrine** is considerably deeper in the Authority tree. The
documented early steps are Sociological research (100), Eloquence (125),
Mining trade reputation (150), Negotiation (175), and Good conditions (200),
before Church doctrine (250); this is **1,000 Law Points** across those six
laws, excluding any earlier prerequisites. Check actual unlocks in-game.

### Other practical effects

- **Sociological research:** +10% Law Point gain — a long-term progression
  investment, not an immediate Stability benefit.
- **Eloquence:** -10% dealer prices.
- **Mining trade reputation:** -10% military item purchase prices, +10%
  resource sale prices.
- **Military trade reputation:** -10% resource purchase prices, +10%
  military item sale prices.
- **Negotiation:** raiders request 25% fewer resources.
- **Good conditions:** 15% more settlers join.

## Testing still needed

- Current-version sources and rate of repeatable Church Stability gain
- Ministry effect on Church gain
- Whether Steady hand applies to Church gain and how it stacks with Church doctrine
- Prison release mechanics, sentence duration, and death chance
- Verified tooltip for Betting on the police and the unrecorded prerequisites
- All remaining law effects and game-version-specific costs

## Public patch references

- [Version 5.09.13 changes](https://steamdb.info/patchnotes/25285747/) — law prices and branch placement
- [Version 0.15.08](https://steamdb.info/patchnotes/5417437/) — historical Church/Ministry Stability behavior

