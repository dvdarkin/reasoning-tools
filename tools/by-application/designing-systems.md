# Designing Systems

How to create robust, effective systems and processes.

## Overview

System design requires anticipating failure modes, managing complexity, aligning incentives, and balancing competing goals. The tools below help you create systems that work in practice, not just in theory.

## Relevant Tools

### From System Dynamics

- **Feedback Loop Design**: Architect reinforcing loops for growth and balancing loops for stability
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#positive-feedback-loops)

- **Stock-Flow Distinction**: Design for accumulation dynamics, not just instantaneous flows
  - Link: [domains/04-complex-systems/system-dynamics.md](../../domains/04-complex-systems/system-dynamics.md#stock-flow-distinction)

- **Delays and Buffering**: Build in buffers and anticipate time lags between action and effect
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#delays-and-oscillation)

### From Network Science

- **Preferential Attachment**: Understand how small initial advantages compound through network effects
  - Link: [domains/04-complex-systems/network-science.md](../../domains/04-complex-systems/network-science.md#preferential-attachment-and-growth-dynamics)

- **Small-World Architecture**: Design for high clustering with short path lengths
  - Link: [domains/04-complex-systems/network-science.md](../../domains/04-complex-systems/network-science.md#clustering-and-community-detection)

- **Robustness Through Redundancy**: Add redundant paths to prevent single-point failures
  - Link: [domains/04-complex-systems/accident-investigation.md](../../domains/04-complex-systems/accident-investigation.md#defense-independence-verification)

### From Mechanism Design

- **Incentive Compatibility**: Align individual incentives with desired collective outcomes
  - Link: [domains/06-coordination-cooperation/mechanism-design.md](../../domains/06-coordination-cooperation/mechanism-design.md#incentive-compatibility)

- **Revelation Principle**: Design mechanisms where truth-telling is individually rational
  - Link: [domains/06-coordination-cooperation/mechanism-design.md](../../domains/06-coordination-cooperation/mechanism-design.md#preference-revelation)

- **Vickrey Auction Logic**: Use second-price logic to eliminate strategic bidding
  - Link: [domains/06-coordination-cooperation/mechanism-design.md](../../domains/06-coordination-cooperation/mechanism-design.md#screening-mechanisms)

### From Accident Investigation

- **Defense in Depth**: Layer multiple independent safeguards so single failures don't cascade
  - Link: [domains/04-complex-systems/accident-investigation.md](../../domains/04-complex-systems/accident-investigation.md#swiss-cheese-model-analysis)

- **Failure Modes and Effects Analysis**: Systematically identify potential failures and their impacts
  - Link: [domains/04-complex-systems/accident-investigation.md](../../domains/04-complex-systems/accident-investigation.md#swiss-cheese-model-analysis)

- **Swiss Cheese Model**: Design assuming multiple failures will occur; prevent alignment
  - Link: [domains/04-complex-systems/accident-investigation.md](../../domains/04-complex-systems/accident-investigation.md#swiss-cheese-model-analysis)

### From Ecology

- **Niche Construction**: Design systems that create their own supporting conditions
  - Link: [domains/03-creative-generation/evolutionary-biology.md](../../domains/03-creative-generation/evolutionary-biology.md#pre-adaptation-and-niche-construction)

- **Succession Stages**: Plan for how systems evolve through predictable phases
  - Link: [domains/04-complex-systems/ecology.md](../../domains/04-complex-systems/ecology.md#succession-pattern-recognition)

### From Design Thinking

- **Rapid Prototyping**: Build quick, testable versions to learn before committing
  - Link: [domains/03-creative-generation/design-thinking.md](../../domains/03-creative-generation/design-thinking.md#rapid-prototyping)

- **User Journey Mapping**: Trace complete user experience to identify pain points
  - Link: [domains/03-creative-generation/design-thinking.md](../../domains/03-creative-generation/design-thinking.md#journey-mapping)

### From Constitutional Design

- **Separation of Powers**: Divide authority to prevent concentration and abuse
  - Link: [domains/06-coordination-cooperation/constitutional-design.md](../../domains/06-coordination-cooperation/constitutional-design.md#separation-of-powers)

- **Checks and Balances**: Create mutual veto points between system components
  - Link: [domains/06-coordination-cooperation/constitutional-design.md](../../domains/06-coordination-cooperation/constitutional-design.md#checks-and-balances)

### From Operations Research

- **Constraint Optimization**: Identify and relax the binding constraint to improve system performance
  - Link: [domains/09-resource-allocation/portfolio-management.md](../../domains/09-resource-allocation/portfolio-management.md#constraint-optimization)

- **Queueing Theory**: Design service capacity to match arrival rate and desired wait times
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#queuing-intuitions)

## Recommended Workflow

1. **Define objectives**: What outcomes should the system produce?
2. **Map user journeys**: How will people interact with the system?
3. **Identify failure modes**: What could go wrong? (FMEA)
4. **Design feedback loops**: What reinforcing/balancing loops drive behavior?
5. **Align incentives**: Make desired behavior individually rational
6. **Layer defenses**: Add redundancy and safeguards (defense in depth)
7. **Prototype rapidly**: Build testable versions early
8. **Test edge cases**: Stress-test with extreme inputs and failures
9. **Plan for evolution**: How will the system adapt over time?

## Example Application

**Scenario**: Designing a code review system for a software team.

1. **Objectives**: Catch bugs, share knowledge, maintain standards
2. **User journey**: Developer writes code → requests review → reviewer examines → discussion → approval → merge
3. **Failure modes**:
   - Reviews take too long (demotivating)
   - Reviews too shallow (miss bugs)
   - Review assignments unfair (burnout)
   - Contentious debates (interpersonal conflict)
4. **Feedback loops**:
   - Reinforcing: Good reviews improve code quality → less rework → more time for reviews
   - Balancing: Strict reviews slow merging → pressure to rubber-stamp → quality drops → bugs increase
5. **Align incentives**:
   - Track review quality (found bugs, prevented issues)
   - Rotate review assignments fairly
   - Reward both writing good code AND providing good reviews
6. **Layer defenses**:
   - Automated linting (first line)
   - Peer review (second line)
   - Integration tests (third line)
   - Manual QA (final line)
7. **Prototype**: Start with one team, gather feedback, iterate
8. **Edge cases**: What if PR is huge? Urgent hotfix? External contributor?
9. **Evolution**: As team grows, add specialized reviewers for security/performance

## Common Pitfalls

- **Optimizing for one metric**: Creating perverse incentives by focusing on single goal
- **Ignoring second-order effects**: Missing how people adapt to and game the system
- **Single points of failure**: Not adding redundancy at critical nodes
- **Assuming rational actors**: Designing for theory while ignoring actual human behavior
- **Premature scaling**: Building for 1000 users when you have 10
- **No feedback loops**: Creating open-loop systems with no self-correction
- **Ignoring delays**: Not accounting for time lags between action and effect
- **Brittle optimization**: Maximizing efficiency while eliminating resilience buffers
