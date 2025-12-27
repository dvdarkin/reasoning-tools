# Enhanced Extraction Template v2.0

*For extracting transferable reasoning tools from any domain*

---

## Instructions for Extraction

Your goal is to extract **transferable reasoning tools** from the target domain - not the specific facts, theories, or models, but the underlying **mental operations** that transfer across contexts.

### Target Structure

- **10-15 tools total** - Comprehensive coverage of the domain's key thinking primitives
- **3-4 tier organization** - Organized by increasing specificity:
  - Tier 1: Foundational tools that work almost anywhere
  - Tier 2: Structural/analytical tools for understanding system organization
  - Tier 3: Dynamic/temporal tools for reasoning about change and evolution
  - Tier 4: Applied/strategic tools for decision-making and intervention (optional)

### What Is a "Reasoning Tool"?

A reasoning tool is a **portable mental operation** - a way of structuring thought that remains useful even if specific theories are wrong. It should be:

- **Operational**: A move you can actually perform, not just a concept to understand
- **Transferable**: Applicable beyond its origin domain
- **Enabling**: Lets you see or do something you couldn't before
- **Bounded**: Has clear failure modes where it misleads

**Good examples:**
- "For any choice, identify the realistic next-best use of the same resources" (Opportunity Cost)
- "Distinguish what accumulates (stock) from what flows in/out (rate)" (Stock-Flow Distinction)
- "When tracing causation, check if effects circle back to influence their causes" (Feedback Loop Identification)

**Not reasoning tools:**
- Domain-specific facts ("The mitochondria is the powerhouse of the cell")
- Vague advice ("Think critically")
- Unfalsifiable interpretive frameworks ("Everything is power relations")
- Pure theory without practical operation ("Quantum mechanics describes reality")

---

## Output Format

Structure your extraction as follows:

### 1. Meta-Framing (200-300 words)

Begin with a section titled: "Why [DOMAIN] Generates Useful Thinking Tools"

Address:
- The domain's epistemic status (what it's good at, what it's not)
- Why extract from it despite limitations or controversies
- The core insight: what systematic errors do these tools correct?
- Extraction principle: what survives even when specific theories fail

**Tone:** Intellectually honest. Acknowledge the domain's limitations while defending its value as a source of reasoning tools. Avoid both uncritical celebration and dismissive skepticism.

### 2. Tiered Organization (10-15 tools, 400-600 words each)

For each tier, provide a brief header explaining what distinguishes this level.

For each tool, include ALL SEVEN components:

#### Tool Name

**What:** Core concept in 1-2 sentences. Be precise and concrete.

**Why it matters:** What problem does this solve? What does it let you see that you couldn't before? What systematic error does it correct?

**The key move:** The actual mental operation you perform. This must be OPERATIONAL - something you can DO, not just understand. Use imperative verbs: "identify," "distinguish," "check," "ask," "trace," "compare," "separate."

**Classic application:** Where did this tool originate? What was the canonical problem it solved? Be specific with examples, not generic.

**Surprising application:** Evidence of transfer to a genuinely different domain. This must be SURPRISING - not just another example from the same field. Show that the tool generalizes beyond its origin context. Explain why this application is non-obvious.

**Failure modes:** When does this tool mislead? Be specific about scenarios where applying it generates wrong conclusions. Good failure modes show understanding of boundaries:
- Over-application: using it where it doesn't fit
- Misidentification: confusing tool prerequisites
- False precision: treating approximations as exact
- Ignoring context: missing domain-specific features

**Go deeper:** 1-2 citations to serious treatments. Prefer:
- Academic sources, textbooks, primary literature
- Specific chapters or papers, not just book titles
- Authors who've thought deeply about this tool
- NOT pop science, blogs, or uncited claims

### 3. Quick Reference Section

Provide two practical aids:

#### Decision Type -> Tool Mapping

A table showing: "When you need to [problem type], use [tools from this domain]"

Examples:
- "When making predictions under uncertainty -> Tool A, Tool D"
- "When diagnosing system failures -> Tool B, Tool E, Tool F"
- "When evaluating trade-offs -> Tool C, Tool G"

#### Suggested Reading Path

3-5 resources ordered for learning:
1. Best entry point (accessible, foundational)
2. Deepening understanding (more technical/comprehensive)
3. Advanced/specialized (for serious students)

### 4. Usage Notes (200-300 words)

Address:
- **Domain of applicability**: Where do these tools work well? Where do they struggle?
- **Limitations**: What can these tools NOT do? What questions are they inappropriate for?
- **Composition**: How do these tools combine? Which pairs work well together? Which are substitutes?
- **Integration**: How do these relate to tools from other domains?

---

## Quality Criteria

Your extraction will be evaluated on:

### 1. Clear Mental Operations (CRITICAL)

Each "key move" must describe something you can actually DO:
- Good: "For any choice, identify the realistic next-best use of the same resources"
- Bad: "Understand opportunity cost"
- Good: "Count negative links in the causal loop; odd = balancing, even = reinforcing"
- Bad: "Recognize feedback loops"

### 2. Evidence of Transfer

"Surprising applications" must demonstrate genuine transfer:
- Good: Tool from meteorology applied to relationship maintenance
- Bad: Another weather forecasting example
- Good: Tool from economics applied to skill acquisition
- Bad: Another market analysis example

### 3. Honest Failure Modes

Show you understand boundaries:
- Good: "Fails when stocks have no conservation law (e.g., 'happiness')"
- Bad: "Can be misused if applied incorrectly"
- Good: "Misleads when confusing correlation with feedback causation"
- Bad: "Doesn't always work"

### 4. Academic Citations

Reference serious literature:
- Good: "Meadows, Thinking in Systems, Chapter 1"
- Good: "Kahneman & Tversky (1979), Prospect Theory"
- Bad: "Various experts suggest..."
- Bad: "As everyone knows..."

---

## What to AVOID

### Domain-Specific Facts Masquerading as Tools

- Bad: "The Krebs cycle processes energy" (biology fact)
- Good: "Trace a process through its cycle to find rate-limiting steps" (biochemistry reasoning tool)

### Common Sense That Everyone Already Knows

- Bad: "Think before acting"
- Bad: "Consider multiple perspectives"
- Good: "Perform a pre-mortem: assume failure and work backward to causes"

### Unfalsifiable Interpretive Frameworks

- Bad: "See everything as power dynamics"
- Bad: "All behavior is status competition"
- Good: "Check if apparent cooperation has defection payoffs that exceed cooperation payoffs"

### Pure Theory Without Practical Operation

- Bad: "Quantum mechanics describes subatomic reality"
- Good: "Model discrete states; treat transitions as probabilistic jumps, not continuous paths"

### Tools Without Transfer Evidence

If it only works in one domain, it's probably domain knowledge, not a reasoning primitive.

### Vague Failure Modes

- Bad: "Can be misused"
- Bad: "Doesn't always work"
- Good: "Fails when causal links have delays exceeding observation windows"

---

## Calibration Examples

Study these two exemplar tools to calibrate your understanding:

### Example 1: Stock-Flow Distinction (from System Dynamics)

**What:** Stocks are accumulations (bathtub water level, bank balance, reputation, skill). Flows are rates of change (faucet rate, income/spending, actions that build or erode). Every stock changes only through its flows.

**Why it matters:** Humans chronically confuse levels with rates. "Sales are good" - do you mean stock of revenue or flow of new sales? This confusion generates systematic errors: we try to change stocks directly (impossible), ignore accumulation effects, and misattribute causation.

**The key move:** When someone describes a situation using a noun (trust, debt, inventory, knowledge), ask: is this a stock or a flow? If stock, what are its inflows and outflows? If flow, what stock does it fill or drain? Force the accounting to balance.

**Classic application:** Inventory management. The "bullwhip effect" in supply chains - small demand fluctuations amplify into huge inventory swings - becomes obvious once you draw the stock-flow structure.

**Surprising application:** Relationship maintenance. Trust is a stock with inflows (consistent small deposits) and outflows (violations). The common error: trying to restore trust through a single grand gesture (attempting to set stock directly) rather than re-establishing positive flow over time.

**Failure modes:** Over-specifying - not everything meaningful is a stock. "Happiness" has stock-like properties but no sensible conservation law. Misidentifying boundaries - what looks like a stock may be a flow at larger timescales.

**Go deeper:** Meadows, Thinking in Systems, Chapter 1; Sterman, Business Dynamics, Chapter 2

### Example 2: Opportunity Cost (from Economics)

**What:** The opportunity cost of any choice is the value of the next-best alternative you forgo. Every choice has an opportunity cost, even when money isn't involved.

**Why it matters:** Naive decision-making only considers direct costs/benefits. Opportunity cost forces you to ask: "Compared to what?" It reveals hidden costs (time, attention, options foreclosed) and prevents treating "free" as actually costless.

**The key move:** For any choice under consideration, identify the realistic next-best use of the same resources (time, money, attention, capacity). Compare the choice not to doing nothing, but to that specific alternative. If you can't articulate the alternative, you don't understand your constraints.

**Classic application:** Capital budgeting. A company evaluates projects not just on absolute returns but on returns relative to other uses of capital. A 10% return is good or bad depending on what else is available.

**Surprising application:** Personal relationship decisions. The opportunity cost of staying in a mediocre relationship isn't being alone - it's the other relationships you could form with that time and emotional energy. Makes clear why "better than nothing" is insufficient reasoning.

**Failure modes:** Paralysis from infinite alternatives - you need to identify the realistic next-best option, not enumerate all possibilities. Ignoring transaction costs - switching has costs that may exceed the opportunity cost. Treating sunk costs as opportunity costs - past expenditures don't create future alternatives.

**Go deeper:** Frank, The Economic Naturalist; Buchanan, Cost and Choice: An Inquiry in Economic Theory

---

## Template Invocation

To use this template, provide:

1. **Domain name**: The field you're extracting from
2. **Optional context**: Specific aspects to focus on, known limitations, or particular applications of interest

The extraction will produce a standalone document that can be read independently, following the structure above.

---

## Notes on Process

### Intellectual Honesty

- Acknowledge domain limitations while defending value
- Distinguish "this model is wrong" from "these reasoning tools are useless"
- Be skeptical of unfalsifiable claims while extracting falsifiable operations

### Transfer as Validation

- If a "tool" only works in one domain, it's probably domain knowledge
- The best tools are those you forget came from anywhere specific
- Surprising applications are evidence, not decoration

### Practical Orientation

- These are tools for USE, not just understanding
- The test is: can someone actually apply this?
- Vague advice ("think systematically") is not a tool

### Quality Over Quantity

- 10-15 well-developed tools beats 30 superficial ones
- Each tool should be 400-600 words
- Every component (all 7) must be present and substantive

---

*End of template. Total length: ~2000 words.*
