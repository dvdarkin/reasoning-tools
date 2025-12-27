# Allocating Resources

How to distribute scarce resources efficiently and fairly.

## Overview

Resource allocation requires balancing efficiency (maximizing total value), equity (fairness), and practical constraints. The tools below help you make allocation decisions that are both effective and defensible.

## Relevant Tools

### From Economics

- **Opportunity Cost**: For every allocation, identify the value of the next-best alternative forgone
  - Link: [domains/09-resource-allocation/economics.md](../../domains/09-resource-allocation/economics.md)

- **Marginal Analysis**: Allocate resources where marginal benefit per unit cost is highest
  - Link: [domains/09-resource-allocation/economics.md](../../domains/09-resource-allocation/economics.md)

- **Diminishing Returns**: Recognize that additional units typically yield decreasing incremental value
  - Link: [domains/09-resource-allocation/economics.md](../../domains/09-resource-allocation/economics.md)

- **Price Mechanisms**: Use prices or price-like signals to aggregate distributed information
  - Link: [domains/09-resource-allocation/economics.md](../../domains/09-resource-allocation/economics.md)

### From Operations Research

- **Linear Programming**: Optimize allocation subject to multiple constraints
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md)

- **Constraint Theory**: Identify and relax the binding constraint to improve overall performance
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md)

- **Queueing Theory**: Manage arrival rates and service capacity to minimize wait times
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md)

### From Portfolio Management

- **Diversification**: Spread resources across uncorrelated options to reduce risk
  - Link: [domains/09-resource-allocation/portfolio-management.md](../../domains/09-resource-allocation/portfolio-management.md)

- **Risk-Return Tradeoff**: Accept higher uncertainty only when compensated by higher expected return
  - Link: [domains/09-resource-allocation/portfolio-management.md](../../domains/09-resource-allocation/portfolio-management.md)

- **Rebalancing**: Periodically adjust allocations back to target ratios
  - Link: [domains/09-resource-allocation/portfolio-management.md](../../domains/09-resource-allocation/portfolio-management.md)

### From Distributive Justice

- **Equity vs Equality**: Choose between proportional allocation (based on contribution/need) vs equal shares
  - Link: [domains/09-resource-allocation/distributive-justice.md](../../domains/09-resource-allocation/distributive-justice.md)

- **Maximin Principle**: Prioritize improving the worst-off position
  - Link: [domains/09-resource-allocation/distributive-justice.md](../../domains/09-resource-allocation/distributive-justice.md)

- **Veil of Ignorance**: Design allocation rules without knowing your position in the distribution
  - Link: [domains/09-resource-allocation/distributive-justice.md](../../domains/09-resource-allocation/distributive-justice.md)

### From Mechanism Design

- **Incentive Compatibility**: Design allocation mechanisms where honest reporting is individually rational
  - Link: [domains/06-coordination-cooperation/mechanism-design.md](../../domains/06-coordination-cooperation/mechanism-design.md)

- **Vickrey Auction**: Allocate to highest-value users while eliminating strategic bidding
  - Link: [domains/06-coordination-cooperation/mechanism-design.md](../../domains/06-coordination-cooperation/mechanism-design.md)

### From System Dynamics

- **Stock-Flow Management**: Balance inflows and outflows to maintain sustainable stocks
  - Link: [domains/04-complex-systems/system-dynamics.md](../../domains/04-complex-systems/system-dynamics.md)

## Recommended Workflow

1. **Quantify scarcity**: How much resource is available? Over what time period?
2. **Identify competing uses**: What are the alternative allocations?
3. **Assess opportunity costs**: What value is forgone by each allocation choice?
4. **Calculate marginal returns**: Which uses have highest value per unit allocated?
5. **Apply constraints**: What limits exist (indivisibility, timing, fairness)?
6. **Choose allocation principle**: Efficiency, equity, equality, or need-based?
7. **Design incentive-compatible mechanism**: Ensure honest revelation of value/need
8. **Diversify if appropriate**: Spread across uncorrelated uses to manage risk
9. **Plan rebalancing**: When and how to adjust allocations?
10. **Monitor and adjust**: Track outcomes and reallocate as conditions change

## Example Application

**Scenario**: Allocating $1M engineering budget across 5 proposed projects.

1. **Scarcity**: $1M available for next fiscal year, $2.5M total requested
2. **Competing uses**:
   - Project A (infrastructure): $600K requested
   - Project B (feature X): $500K requested
   - Project C (feature Y): $400K requested
   - Project D (technical debt): $500K requested
   - Project E (research): $500K requested
3. **Opportunity costs**:
   - Funding A means forgoing B+C or D+E
   - Each allocation excludes others
4. **Marginal returns**:
   - A: High value but lumpy (all-or-nothing)
   - B: Expected $2M revenue, high confidence
   - C: Expected $1M revenue, moderate confidence
   - D: Prevents future slowdown (hard to quantify)
   - E: Option value, very uncertain
5. **Constraints**:
   - A is indivisible (needs full $600K)
   - Team capacity limits parallel projects
   - Fairness: all teams deserve some investment
6. **Allocation principle**:
   - Primary: Maximize expected value (efficiency)
   - Secondary: Ensure no team gets zero (equality floor)
7. **Mechanism**: Teams submit business cases with expected ROI; executive team evaluates
8. **Diversification**: Mix high-certainty (B) with high-upside (E)
9. **Rebalancing**: Quarterly review, can reallocate if projects fail/succeed early
10. **Monitoring**: Track actual ROI vs projected; adjust future allocation criteria

**Outcome**: Fund B ($500K) + C ($400K) + partial D ($100K), revisit A and E next quarter

## Common Pitfalls

- **Ignoring opportunity cost**: Evaluating projects in isolation rather than relative to alternatives
- **Sunk cost fallacy**: Continuing to allocate based on past investment rather than future returns
- **Equal distribution default**: Splitting resources equally when marginal returns differ dramatically
- **Ignoring constraints**: Optimizing without accounting for indivisibilities, timing, or fairness
- **Static allocation**: Set-and-forget approach that doesn't adapt to changing conditions
- **No diversification**: Concentrating all resources in single option
- **Incentive incompatibility**: Rewarding exaggerated requests or sandbagging
- **False precision**: Pretending to calculate exact optimal allocation with uncertain inputs
- **Efficiency-equity confusion**: Conflating "best total outcome" with "fairest distribution"
