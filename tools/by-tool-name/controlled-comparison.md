# Controlled Comparison

**Appears in:** Experimental Design, Medical Diagnostics, Intelligence Analysis, Investigative Journalism, Operations Research

## Core Concept

To determine if X causes Y, you must compare outcomes when X is present versus when X is absent, while holding all other relevant factors constant. The comparison is the experiment - without it, you're engaging in storytelling, not causal inference.

## Domain-Specific Variations

### In Experimental Design
- **Context:** Fundamental principle of causal inference
- **Key operation:** Ask "compared to what?" - make the counterfactual explicit and concrete
- **Link:** [domains/07-truth-seeking/experimental-design.md](../../domains/07-truth-seeking/experimental-design.md#controlled-comparison)

### In Medical Diagnostics
- **Context:** Clinical trials with treatment vs. control groups
- **Key operation:** Compare patient outcomes receiving treatment vs. placebo, holding all else constant
- **Link:** [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md#discriminating-test-selection)

### In Intelligence Analysis
- **Context:** Structured analytic techniques for hypothesis testing
- **Key operation:** Compare predictions under different hypotheses - what would we observe if Hypothesis A is true vs. Hypothesis B?
- **Link:** [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md#analysis-of-competing-hypotheses-ach)

### In Investigative Journalism
- **Context:** Verifying claims by comparing similar cases with/without the alleged cause
- **Key operation:** Find comparison cases that differ only in the variable of interest
- **Link:** [domains/07-truth-seeking/investigative-journalism.md](../../domains/07-truth-seeking/investigative-journalism.md#document-first-investigation)

### In Operations Research
- **Context:** A/B testing, simulation studies, process improvement
- **Key operation:** Test process changes by running controlled comparisons - new process vs. baseline
- **Link:** [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#sensitivity-analysis)

## When to Use This Tool

Use controlled comparison when:
- Evaluating any causal claim ("Does X cause Y?")
- Someone presents before-after data without a control group
- You need to distinguish treatment effects from natural trends or regression to the mean
- Making decisions based on personal experience (what's the comparison case?)
- Debugging systems (does the problem occur with/without this component?)

The tool forces you to ask "compared to what?" and reveals that most casual causal claims lack proper comparison groups.
