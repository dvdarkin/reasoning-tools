# Bottleneck Identification

**Appears in:** Operations Research, Network Science, System Dynamics, Military Strategy

## Core Concept

System throughput is determined by its tightest constraint. Improving non-bottlenecks doesn't improve system performance - it just creates inventory buildup. Finding the true bottleneck focuses improvement effort where it actually matters.

## Domain-Specific Variations

### In Operations Research
- **Context:** Theory of Constraints in manufacturing and process optimization
- **Key operation:** Trace flow through the system - where does work pile up? The queue forms before the bottleneck
- **Link:** domains/09-resource-allocation/operations-research.md#bottleneck-identification

### In Network Science
- **Context:** Flow capacity analysis and minimum cut identification
- **Key operation:** Calculate maximum flow - edges at full capacity are bottlenecks
- **Link:** domains/04-complex-systems/network-science.md#bottleneck-and-flow-capacity-analysis

### In System Dynamics
- **Context:** Dominant loop analysis - which constraint currently limits system behavior
- **Key operation:** Identify which feedback loop or resource constraint is currently binding
- **Link:** domains/04-complex-systems/system-dynamics.md#dominant-loop-analysis

### In Military Strategy
- **Context:** Center of gravity analysis and logistics planning
- **Key operation:** Identify the critical vulnerability or resource that enables enemy operations
- **Link:** domains/08-conflict-competition/military-strategy.md#center-of-gravity

## When to Use This Tool

Use bottleneck analysis when:
- System performance isn't improving despite optimization efforts
- You need to prioritize which improvements will actually increase throughput
- Resources are limited and you must focus investment
- Diagnosing why systems are slower/less productive than expected
- Planning capacity expansions or process improvements

The key insight: the bottleneck shifts once relieved. After you fix the current constraint, a new one becomes binding. This is iterative work, not one-time optimization.
