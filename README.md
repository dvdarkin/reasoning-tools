# Reasoning Tools Knowledge Base

A comprehensive, structured library of transferable reasoning tools extracted from 32 high-value domains.

## What This Is

This is a collection of **reasoning primitives** - mental operations that transfer across domains. Not facts, not theories, but thinking tools that remain useful even when specific models are wrong.

Each tool includes:
- **What**: The core concept
- **Why it matters**: What problem it solves
- **The key move**: The actual mental operation
- **Classic application**: Where it originated
- **Surprising application**: Evidence it transfers
- **Failure modes**: When it misleads
- **Go deeper**: Citations to serious literature

## How to Navigate

### By Problem Type
Browse [domains/](domains/README.md) organized by what you're trying to do:
- [Decision Under Uncertainty](domains/01-decision-under-uncertainty/README.md) - Making choices with incomplete information
- [Persuasion & Influence](domains/02-persuasion-influence/README.md) - Changing minds and shaping behavior
- [Creative Generation](domains/03-creative-generation/README.md) - Producing novel ideas and solutions
- [Complex System Analysis](domains/04-complex-systems/README.md) - Understanding interconnected systems
- [Skill Acquisition & Mastery](domains/05-skill-mastery/README.md) - Learning and developing expertise
- [Coordination & Cooperation](domains/06-coordination-cooperation/README.md) - Organizing groups and aligning incentives
- [Truth-Seeking & Verification](domains/07-truth-seeking/README.md) - Finding and validating claims
- [Conflict & Competition](domains/08-conflict-competition/README.md) - Strategic interaction and adversarial reasoning
- [Resource Allocation](domains/09-resource-allocation/README.md) - Distributing limited resources optimally
- [Pattern Recognition](domains/10-pattern-recognition/README.md) - Identifying structures and making predictions

### Glossary
See [tools/glossary.md](tools/glossary.md) for a complete alphabetical index of all 516 tools with direct links to their source domains.

### By Tool Name
See [tools/by-tool-name/](tools/by-tool-name/README.md) for cross-domain tools showing how the same concept appears in different fields.

### By Application
See [tools/by-application/](tools/by-application/README.md) for problem-oriented guides (e.g., "How to make predictions", "How to diagnose problems").

### Visual Map
See [matrix.md](matrix.md) for the full hybrid matrix showing problem domains × disciplinary approaches.

## What's Included (32 Domains)

**Decision Under Uncertainty (4):**
- Bayesian Statistics - Rigorous framework for updating beliefs with evidence
- Meteorology - Ensemble forecasting, confidence intervals, model averaging
- Intelligence Analysis - Structured analytic techniques, red teaming, hypothesis testing
- Emergency Medicine - Triage protocols, rapid assessment under pressure

**Persuasion & Influence (3):**
- Game Theory (Signaling) - Costly signals, credible commitments, information revelation
- Social Psychology - Cognitive biases, attitude change, group dynamics
- Classical Rhetoric - Persuasive argumentation, audience analysis, rhetorical appeals

**Creative Generation (2):**
- Design Thinking - Human-centered problem solving, prototyping, iteration
- Evolutionary Biology - Variation, selection, adaptation, convergent evolution

**Complex System Analysis (4):**
- System Dynamics - Stock-flow thinking, feedback loops, delays
- Network Science - Graph structure, centrality, clustering, cascades
- Ecology - Niche construction, trophic levels, succession, resilience
- Accident Investigation - Root cause analysis, Swiss cheese model, contributing factors

**Skill Acquisition & Mastery (3):**
- Learning Theory (Cognitive Science) - Spaced repetition, retrieval practice, transfer
- Sports Science - Deliberate practice, periodization, skill acquisition
- Expertise Studies - Pattern recognition, chunking, mental models

**Coordination & Cooperation (3):**
- Mechanism Design - Incentive compatibility, revelation principle, implementation
- Organizational Behavior - Team dynamics, culture, motivation, structure
- Constitutional Design - Separation of powers, checks and balances, amendment rules

**Truth-Seeking & Verification (4):**
- Formal Verification - Proofs, invariants, model checking, specification
- Experimental Design - Controls, randomization, blinding, replication
- Investigative Journalism - Source verification, documentary evidence, corroboration
- Logic & Critical Thinking - Valid inference, fallacy detection, argument analysis

**Conflict & Competition (3):**
- Military Strategy - Force concentration, interior lines, maneuver warfare
- Competitive Game Theory - Nash equilibrium, minimax, backward induction
- Litigation Strategy - Discovery, burden of proof, adversarial system

**Resource Allocation (4):**
- Economics - Opportunity cost, marginal analysis, comparative advantage
- Operations Research - Optimization, queuing theory, linear programming
- Portfolio Management - Diversification, risk-adjusted returns, rebalancing
- Distributive Justice - Fairness principles, allocation criteria, trade-offs

**Pattern Recognition (2):**
- Machine Learning - Bias-variance tradeoff, regularization, cross-validation
- Medical Diagnostics - Differential diagnosis, base rates, likelihood ratios

## Cross-Domain Tools

| Tool | Domains |
|------|---------|
| **Base Rate Integration** | [Logic & Critical Thinking](domains/07-truth-seeking/logic-critical-thinking.md#base-rate-integration), [Medical Diagnostics](domains/10-pattern-recognition/medical-diagnostics.md#base-rate-integration) |
| **Pre-mortem Analysis** | [Intelligence Analysis](domains/01-decision-under-uncertainty/intelligence-analysis.md#pre-mortem-analysis), [Design Thinking](domains/03-creative-generation/design-thinking.md#pre-mortem-analysis), [Logic & Critical Thinking](domains/07-truth-seeking/logic-critical-thinking.md#pre-mortem-analysis) |
| **Red Team Analysis** | [Intelligence Analysis](domains/01-decision-under-uncertainty/intelligence-analysis.md#red-team-analysis), [Logic & Critical Thinking](domains/07-truth-seeking/logic-critical-thinking.md#red-team-analysis) |

These tools were extracted separately from each domain's literature, yet converged on the same core mental operation—strong evidence they represent genuine reasoning primitives rather than domain-specific techniques.

## Selection Criteria

Domains were selected using a **hybrid matrix approach** balancing:
- **Breadth**: Coverage across disciplinary approaches (formal, empirical, historical, philosophical, creative, practical, contemplative)
- **Utility**: Coverage across problem domains (decision-making, persuasion, creativity, etc.)
- **Extractability**: Explicit, documented methodologies with clear literature

Phase 1 focused on **high-extractability** domains:
- Explicit, documented methodologies
- Clear literature to draw from
- Proven track record of application
- Formalized reasoning techniques

See [meta/domain-selection-criteria.md](meta/domain-selection-criteria.md) for detailed rationale.

## Quality Standards

All extractions follow consistent quality criteria:
- **Clear mental operations** - Not just concepts, but actionable thinking moves
- **Evidence of transfer** - Surprising applications in different domains
- **Honest failure modes** - Specific scenarios where tools mislead
- **Academic citations** - Serious literature, not pop science

See [meta/quality-criteria.md](meta/quality-criteria.md) for full checklist.

## How to Use

1. **Start with a problem**: "I need to make a decision with incomplete information"
2. **Find relevant domains**: Browse [Decision Under Uncertainty](domains/01-decision-under-uncertainty/README.md)
3. **Learn the tools**: Read 1-2 domains that resonate (Bayesian Statistics, Intelligence Analysis)
4. **Try the key moves**: Apply the mental operations to your problem
5. **Watch for failure modes**: Know when the tool misleads

**Example workflow:**
- Problem: Evaluating a business opportunity with uncertain market demand
- Domains: Bayesian Statistics (base rates, updating), Intelligence Analysis (red teaming), Economics (opportunity cost)
- Key moves: Identify reference class → assign prior → gather evidence → update beliefs → consider alternatives
- Failure modes: Availability bias in selecting reference class, overconfidence after early confirming evidence

## Meta-Documentation

- [Extraction Template](meta/extraction-template.md) - The prompt used for all extractions
- [Quality Criteria](meta/quality-criteria.md) - How we evaluate extractions
- [Domain Selection](meta/domain-selection-criteria.md) - Why these fields
- [Extraction Log](meta/extraction-log.md) - Progress tracking

## Future Expansion

38 additional domains identified for Phase 2 (medium-extractability):

**Tacit knowledge traditions:**
- Jazz Improvisation - Real-time adaptation, call-and-response, constraint-based creativity
- Carpentry/Woodworking - Material properties, grain direction, tool selection
- Wilderness Tracking - Sign interpretation, inference chains, negative evidence
- Martial Arts (Internal) - Body mechanics, timing, adaptation to opponent

**Contemplative practices:**
- Buddhist Mindfulness - Attention regulation, non-judgment, impermanence
- Stoicism - Dichotomy of control, negative visualization, voluntary discomfort
- Phenomenology - Bracketing, intentionality, lived experience

**Creative domains:**
- Photography - Composition, lighting, moment selection
- Screenwriting - Three-act structure, character arcs, conflict escalation
- Film Production - Shot composition, editing rhythm, resource constraints
- Orchestra Conducting - Interpretation, timing, ensemble coordination

**Other:**
- Epistemology - Justified true belief, coherentism, foundationalism
- Pedagogy - Scaffolding, zone of proximal development, formative assessment
- Forensics - Chain of custody, trace evidence, physical reconstruction
- Sales/Negotiation - BATNA, anchoring, win-win solutions
- Construction Management - Critical path, float, resource leveling

## Known Limitations

**Link Format Compatibility:**
- Internal links use GitHub-style anchors (kebab-case slugs, e.g., `#comparative-advantage` for heading `## Comparative Advantage`)
- These anchors work on **GitHub** and most markdown renderers, but not **Obsidian**
- Obsidian uses a different anchor format - links will open the file but not scroll to the section ([known incompatibility](https://forum.obsidian.md/t/support-gfm-style-kebab-case-heading-slug-anchor-targets/30350))
- See [tools/glossary.md](tools/glossary.md) for a complete alphabetical index of all tools with verified links

## License

This work is licensed under [CC BY 4.0](LICENSE). You are free to share and adapt with attribution.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). New domain contributions welcome—follow the [extraction template](meta/extraction-template.md).

## Citation Format

If you use these reasoning tools in your work, please cite:

```
Reasoning Tools Knowledge Base (2025)
Extracted reasoning primitives across 32 domains
Available at: https://github.com/dvdarkin/reasoning-tools
```

---

**Last Updated**: 2025-12-29
**Version**: 1.2.0
**Total Domains**: 32
**Total Tools**: 516 (see [glossary](tools/glossary.md) for full list)
**Tools per Domain**: 13-28 (average ~16)
