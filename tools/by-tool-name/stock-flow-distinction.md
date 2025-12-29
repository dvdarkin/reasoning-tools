# Stock-Flow Distinction

**Appears in:** System Dynamics, Operations Research, Behavioral Economics, Ecology

## Core Concept

Stocks are accumulations at a point in time (bathtub water level, bank balance, inventory, population). Flows are rates of change (faucet flow, income/spending, production/sales, births/deaths). Stocks change only through their inflows and outflows. Confusing stocks with flows generates systematic reasoning errors.

## Domain-Specific Variations

### In System Dynamics
- **Context:** Fundamental building block for modeling change over time
- **Key operation:** Ask "is this a stock or a flow?" Force accounting to balance - stocks integrate flows over time
- **Link:** [domains/04-complex-systems/system-dynamics.md](../../domains/04-complex-systems/system-dynamics.md#stock-flow-distinction)

### In Operations Research
- **Context:** Inventory as buffer between production and demand
- **Key operation:** Inventory (stock) changes through production rate (inflow) and sales rate (outflow)
- **Link:** [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#stock-and-flow-reasoning)

### In Behavioral Economics
- **Context:** Wealth vs. income, capital vs. investment, debt vs. deficit
- **Key operation:** Distinguish accumulated quantities from flow rates to avoid confusion in policy debates
- **Link:** [domains/09-resource-allocation/behavioral-economics.md](../../domains/09-resource-allocation/behavioral-economics.md#time-discounting-and-present-bias)

### In Ecology
- **Context:** Population levels vs. birth/death rates, biomass vs. productivity
- **Key operation:** Population (stock) changes through births and immigration (inflows) minus deaths and emigration (outflows)
- **Link:** [domains/04-complex-systems/ecology.md](../../domains/04-complex-systems/ecology.md#energy-flow-tracking)

## When to Use This Tool

Use stock-flow thinking when:
- Describing change over time ("Are sales good?" - do you mean revenue stock or sales flow?)
- Diagnosing why systems aren't responding to interventions (stocks have inertia)
- Understanding accumulation and depletion dynamics
- Someone confuses rates with levels (unemployment rate vs. number unemployed)
- Planning requires understanding how long change takes

Humans chronically confuse stocks with flows, leading to errors like expecting stocks to change instantly when flows change, or trying to control stocks directly rather than through their flows.
