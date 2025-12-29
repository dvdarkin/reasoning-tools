# Changelog

All notable changes to the Reasoning Tools Knowledge Base will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.1] - 2025-12-30

### Fixed
- **Header normalization** - Standardized tool headings from `## Tool` to `### Tool` in 7 domain files for consistency (military-strategy, mechanism-design, operations-research, intelligence-analysis, classical-rhetoric, distributive-justice, investigative-journalism)

### Changed
- **Extraction template updated** - Tool count guidance changed from "10-15 tools" to "10-15 typical, up to 25 for rich domains" with quality gate: verify 400+ words and all 7 sections if exceeding 15

## [1.3.0] - 2025-12-30

### Changed
- **Economics domain split** - Original `economics.md` (28 tools, compressed) split into 3 template-compliant domains:
  - `economics-core.md` (12 tools) - Foundational concepts: opportunity cost, marginal thinking, equilibrium, incentives
  - `information-economics.md` (12 tools) - Asymmetric information: adverse selection, signaling, moral hazard, option value
  - `behavioral-economics.md` (11 tools) - Systematic biases: loss aversion, framing, anchoring, time discounting

### Added
- 10 new tools not in original economics extraction: Elasticity Thinking, Pareto Efficiency, Rent-Seeking, Substitutes/Complements, Price as Information, Screening, Winner's Curse, Revealed Preference, Sunk Cost Fallacy, Mental Accounting

### Fixed
- All economics tools now have complete 7-section structure (4 Tier 5 tools were previously truncated)
- Tool count: 516 → 523
- Domain count: 32 → 34

## [1.2.0] - 2025-12-29

### Added
- **Glossary** (`tools/glossary.md`) - Complete alphabetical index of all 516 tools with direct anchor links to source domains
- Glossary links added to all navigation sections (README, domains/README, tools READMEs)

### Changed
- **Simplified heading format** - Removed numbered prefixes (e.g., `## 1.4 Comparative Advantage` → `## Comparative Advantage`) from 156 headings across 8 domain files for cleaner anchor links
- **Fixed all navigation links** - All links in `tools/by-application/` and `tools/by-tool-name/` now point to specific tool sections with verified anchors
- **Removed incorrect domain claims** - Fixed 6 by-tool-name entries that incorrectly listed domains where the concept doesn't appear as a dedicated tool
- Updated cross-domain tools section in README with correct anchors

### Fixed
- Anchor links now work in GitHub and other md viewers (not Obsidian though)
- Links in by-application guides now point to specific tools instead of domain page tops

## [1.1.0] - 2025-12-27

### Added
- **Open Source Release** - Project now publicly available
- LICENSE file (CC-BY 4.0)
- CONTRIBUTING.md with contribution guidelines
- .gitignore for repository hygiene
- domains/README.md index for top-level navigation

### Changed
- Renamed all `_index.md` files to `README.md` for GitHub/Obsidian compatibility
- Updated all internal links to use README.md convention
- README.md now includes proper license and contributing sections

## [1.0.0] - 2025-12-25

### Added
- Initial release of Reasoning Tools Knowledge Base
- 32 domain extractions with 300+ transferable reasoning tools
- Structured organization by problem domain
- Cross-domain tool index
- Application-based tool index
- Visual hybrid matrix
- Comprehensive documentation and meta-documentation

### Domains Included

**Decision Under Uncertainty (4):**
- Bayesian Statistics - Rigorous framework for updating beliefs with evidence
- Meteorology - Ensemble forecasting, confidence intervals, model averaging
- Intelligence Analysis - Structured analytic techniques, red teaming, hypothesis testing
- Emergency Medicine - Triage, protocols, rapid assessment under pressure

**Persuasion & Influence (3):**
- Game Theory (Signaling) - Strategic information revelation, credible commitment
- Social Psychology - Persuasion dynamics, cognitive biases, behavioral influence
- Classical Rhetoric - Argumentation, ethos/pathos/logos, rhetorical devices

**Creative Generation (2):**
- Design Thinking - User-centered ideation, prototyping, iterative refinement
- Evolutionary Biology - Variation, selection, adaptation as creative mechanisms

**Complex Systems (4):**
- System Dynamics - Stock-flow thinking, feedback loops, delays, nonlinearity
- Network Science - Graph structure, centrality, clustering, diffusion
- Ecology - Ecosystem dynamics, trophic cascades, resilience, carrying capacity
- Accident Investigation - Root cause analysis, Swiss cheese model, barrier analysis

**Skill Mastery (3):**
- Learning Theory (Cognitive Science) - Spaced repetition, retrieval practice, transfer
- Sports Science - Deliberate practice, motor learning, performance optimization
- Expertise Studies - Expert-novice differences, skill acquisition stages

**Coordination & Cooperation (3):**
- Mechanism Design - Incentive compatibility, revelation principle, social choice
- Organizational Behavior - Team dynamics, organizational structure, culture
- Constitutional Design - Checks and balances, rights frameworks, governance structures

**Truth-Seeking & Verification (4):**
- Formal Verification - Proof systems, model checking, invariant analysis
- Experimental Design - Randomization, control, statistical power, confounding
- Investigative Journalism - Source verification, evidence triangulation, fact-checking
- Logic & Critical Thinking - Valid inference, fallacy detection, argument analysis

**Conflict & Competition (3):**
- Military Strategy - Force concentration, maneuver warfare, strategic surprise
- Competitive Game Theory - Nash equilibrium, minimax, strategic dominance
- Litigation Strategy - Discovery, argumentation, burden of proof, precedent

**Resource Allocation (4):**
- Economics - Opportunity cost, marginal analysis, comparative advantage
- Operations Research - Optimization, queuing theory, linear programming
- Portfolio Management - Diversification, risk-return tradeoff, rebalancing
- Distributive Justice - Fairness principles, allocation criteria, equity-efficiency tradeoffs

**Pattern Recognition (2):**
- Machine Learning - Feature engineering, regularization, cross-validation, bias-variance
- Medical Diagnostics - Differential diagnosis, Bayesian reasoning, sensitivity/specificity

### Quality Standards

All extractions adhere to rigorous quality criteria:

- **Clear Mental Operations**: Each tool describes an actionable cognitive operation, not just a concept
- **Evidence of Transfer**: Surprising applications demonstrate portability across domains
- **Honest Failure Modes**: Specific scenarios where each tool misleads or breaks down
- **Academic Citations**: All tools cite serious literature (textbooks, primary research, expert sources)
- **Consistent Structure**: Every tool includes What/Why/Key Move/Classic/Surprising/Failure/Go Deeper sections
- **Target Length**: 10-15 tools per domain, 400-600 words per tool
- **Tier Organization**: Tools organized into 3-4 tiers by importance/centrality

### Documentation

Comprehensive meta-documentation included:

- **Extraction Template** (`meta/extraction-template.md`) - Complete methodology for tool extraction
- **Quality Criteria** (`meta/quality-criteria.md`) - Checklist for evaluating extractions
- **Domain Selection Criteria** (`meta/domain-selection-criteria.md`) - Hybrid matrix approach rationale
- **Extraction Log** (`meta/extraction-log.md`) - Progress tracking across all extractions
- **Statistics** (`meta/statistics.md`) - Coverage metrics and cross-domain analysis

### Navigation

Multiple access paths to the knowledge base:

- **By Problem Domain**: Browse 10 category directories under `domains/`
- **By Tool Name**: Alphabetical cross-domain index in `tools/by-tool-name/`
- **By Application**: Problem-oriented guides in `tools/by-application/`
- **Visual Matrix**: Hybrid matrix view in `matrix.md`
- **Master README**: Comprehensive introduction and navigation guide

## [Planned] - Phase 2

### Planned Domains (38 additional)

Medium-extractability domains deferred for future expansion:

**Tacit Knowledge Traditions:**
- Jazz Improvisation
- Carpentry/Woodworking
- Wilderness Tracking
- Orchestra Conducting
- Martial Arts (Internal)

**Contemplative Practices:**
- Buddhist Mindfulness
- Stoic Philosophy
- Phenomenology
- Meditation Techniques
- Dream Analysis (Jungian)

**Creative & Artistic:**
- Photography/Visual Design
- Screenwriting
- Film Production
- Music Performance
- Literary Criticism
- Architecture

**Additional Empirical:**
- Art History
- Patent Law
- Sales/Negotiation
- Forensics
- Argumentation Theory

**Additional Formal:**
- Combinatorics
- Epistemology
- Social Contract Theory
- Just War Theory
- Hermeneutics
- Philosophy of Science

**Additional Practical:**
- Permaculture
- Construction Management
- Time Management
- Apprenticeship Models
- Debate
- Quaker Consensus

### Future Enhancements

- Enhanced cross-referencing between related tools
- Interactive tool recommendation engine
- Domain similarity analysis
- Tool combination patterns and workflows
- Expanded case studies and applications
- Community contributions and extensions

---

**Note**: This changelog follows the structure specified in the implementation plan (Task 23). For detailed extraction history, see `meta/extraction-log.md`.
