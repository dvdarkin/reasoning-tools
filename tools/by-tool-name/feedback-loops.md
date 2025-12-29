# Feedback Loops

**Appears in:** System Dynamics, Operations Research, Ecology, Network Science, Organizational Behavior

## Core Concept

Feedback occurs when a system's output becomes its input, creating either reinforcing loops (amplifying change) or balancing loops (resisting change toward equilibrium). Understanding feedback structure reveals why systems resist intervention, overshoot targets, or flip behavior unexpectedly.

## Domain-Specific Variations

### In System Dynamics
- **Context:** Identifying positive (reinforcing) and negative (balancing) feedback loops in interconnected systems
- **Key operation:** Trace causal chains - does this effect eventually influence its own cause? Count negative links to determine loop polarity
- **Link:** [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#positive-feedback-loops)

### In Operations Research
- **Context:** Negative feedback for control systems, positive feedback for runaway processes
- **Key operation:** Identify setpoints, sensors, comparators, and effectors in self-regulating systems
- **Link:** [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#negative-feedback-loops)

### In Ecology
- **Context:** Population dynamics, predator-prey relationships, ecosystem regulation
- **Key operation:** Map how population changes feed back through resource availability and predation
- **Link:** [domains/04-complex-systems/ecology.md](../../domains/04-complex-systems/ecology.md#trophic-cascade-tracing)

### In Network Science
- **Context:** Preferential attachment (rich-get-richer), viral growth, cascade dynamics
- **Key operation:** Identify whether network growth mechanisms create self-amplifying or self-limiting processes
- **Link:** [domains/04-complex-systems/network-science.md](../../domains/04-complex-systems/network-science.md#cascade-and-percolation-dynamics)

### In Organizational Behavior
- **Context:** Culture reinforcement, performance spirals, organizational inertia
- **Key operation:** Trace how current behavior creates conditions that reinforce or undermine that same behavior
- **Link:** [domains/06-coordination-cooperation/organizational-behavior.md](../../domains/06-coordination-cooperation/organizational-behavior.md#psychological-safety-audit)

## When to Use This Tool

Use feedback loop analysis when:
- Systems exhibit non-linear behavior (exponential growth, oscillation, sudden shifts)
- Interventions produce unexpected or opposite effects (policy resistance)
- Behavior persists despite efforts to change it (homeostasis)
- Small initial differences lead to large divergent outcomes
- You need to identify leverage points for system intervention

The tool is less useful for:
- Simple linear cause-effect relationships without circular causation
- One-time events without ongoing dynamics
- Systems where feedback effects are negligible compared to external forcing
