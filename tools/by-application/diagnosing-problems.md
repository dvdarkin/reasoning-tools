# Diagnosing Problems

How to identify root causes of failures and malfunctions.

## Overview

Diagnosis requires distinguishing symptoms from causes, generating alternative hypotheses, gathering discriminating evidence, and avoiding premature closure. The tools below help you systematically investigate problems without jumping to conclusions.

## Relevant Tools

### From Medical Diagnostics

- **Differential Diagnosis**: Generate and test multiple competing explanations simultaneously
  - Link: [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md#differential-diagnosis-generation)

- **Pattern Recognition**: Match symptom clusters to known syndrome patterns
  - Link: [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md#pattern-matching-vs-first-principles)

- **Test Ordering Strategy**: Sequence diagnostic tests to maximize information gain per cost
  - Link: [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md#discriminating-test-selection)

### From Intelligence Analysis

- **Analysis of Competing Hypotheses (ACH)**: Systematically evaluate evidence for and against each hypothesis
  - Link: [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md#analysis-of-competing-hypotheses-ach)

- **Key Assumptions Check**: Identify and test the assumptions underlying your diagnosis
  - Link: [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md#key-assumptions-check)

### From Accident Investigation

- **5 Whys Analysis**: Iteratively ask "why" to trace from symptoms to root causes
  - Link: [domains/04-complex-systems/accident-investigation.md](../../domains/04-complex-systems/accident-investigation.md#contributing-factor-chains)

- **Swiss Cheese Model**: Look for alignment of multiple failures rather than single causes
  - Link: [domains/04-complex-systems/accident-investigation.md](../../domains/04-complex-systems/accident-investigation.md#swiss-cheese-model-analysis)

- **Timeline Reconstruction**: Map events chronologically to reveal causal sequences
  - Link: [domains/07-truth-seeking/investigative-journalism.md](../../domains/07-truth-seeking/investigative-journalism.md#timeline-construction)

### From Bayesian Statistics

- **Hypothesis Space Partitioning**: Enumerate mutually exclusive, exhaustive possible causes
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md#hypothesis-space-partitioning)

- **Likelihood Ratio Thinking**: Assess how diagnostic each piece of evidence is
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md#likelihood-ratio-thinking)

### From Experimental Design

- **Controlled Comparison**: Isolate variables by comparing cases where problem occurs vs doesn't
  - Link: [domains/07-truth-seeking/experimental-design.md](../../domains/07-truth-seeking/experimental-design.md#controlled-comparison)

- **Ablation Testing**: Remove components one at a time to identify necessary causes
  - Link: [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md#discriminating-test-selection)

### From System Dynamics

- **Feedback Loop Analysis**: Identify whether problem is caused by reinforcing or balancing loops
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#positive-feedback-loops)

- **Delays and Lags**: Look for time lags between cause and observed effect
  - Link: [domains/04-complex-systems/system-dynamics.md](../../domains/04-complex-systems/system-dynamics.md#delay-recognition-and-classification)

### From Network Science

- **Bottleneck Identification**: Find critical nodes whose failure causes system-wide problems
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#bottleneck-identification-theory-of-constraints)

## Recommended Workflow

1. **Document symptoms**: What exactly is failing? When? Under what conditions?
2. **Generate hypotheses**: Brainstorm multiple possible root causes (aim for 5-10)
3. **Partition space**: Ensure hypotheses are mutually exclusive and exhaustive
4. **Identify discriminating tests**: What evidence would distinguish between hypotheses?
5. **Gather evidence systematically**: Run tests with highest information gain first
6. **Update probabilities**: Use ACH matrix to track which hypotheses fit the evidence
7. **Trace causality**: Use 5 Whys or timeline reconstruction to verify root cause
8. **Check for Swiss cheese**: Look for multiple contributing factors, not just one cause
9. **Validate fix**: Test that addressing the diagnosed cause actually solves the problem

## Example Application

**Scenario**: Web application experiencing intermittent slowdowns.

1. **Symptoms**: Response time spikes to 5s (normally 200ms), 3-4 times per hour, random endpoints
2. **Hypotheses**: Database query inefficiency, memory leak, network latency, external API timeout, cache invalidation, resource contention
3. **Partitioning**: Each hypothesis is distinct; "other" covers unknowns
4. **Discriminating tests**:
   - Check DB query logs (tests query inefficiency)
   - Monitor memory usage over time (tests memory leak)
   - Compare response times across regions (tests network)
   - Check external API latency (tests API timeout)
5. **Evidence gathering**:
   - DB queries show normal patterns (weak evidence against DB)
   - Memory grows linearly with uptime (strong evidence for leak)
   - Latency uncorrelated with region (rules out network)
   - External APIs timeout during slowdowns (moderate evidence)
6. **ACH analysis**: Memory leak hypothesis explains all evidence; API timeouts might be consequence
7. **5 Whys**: Why memory leak? → Objects not garbage collected → Event listeners not removed → Recent code change added listeners without cleanup
8. **Swiss cheese**: Primary cause is listener leak; secondary factor is external API intolerance to slight delays
9. **Validate**: Fix listener cleanup, verify memory stable and slowdowns gone

## Common Pitfalls

- **Premature closure**: Stopping at first plausible explanation without testing alternatives
- **Confirmation bias**: Seeking evidence that supports your initial hypothesis
- **Single cause assumption**: Missing that multiple failures must align (Swiss cheese)
- **Symptom treatment**: Addressing proximate symptoms rather than root causes
- **Sequential hypothesis testing**: Testing one hypothesis at a time instead of ACH matrix approach
- **Ignoring base rates**: Pursuing exotic diagnoses when common causes haven't been ruled out
- **Insufficient data**: Making diagnosis without gathering discriminating evidence
