# Verifying Claims

How to assess the truth or reliability of assertions and evidence.

## Overview

Verification requires distinguishing evidence from assertion, checking sources, eliminating alternative explanations, and calibrating confidence appropriately. The tools below help you evaluate claims rigorously without excessive skepticism or credulity.

## Relevant Tools

### From Experimental Design

- **Randomized Controlled Trials**: Eliminate confounding by randomizing treatment assignment
  - Link: [domains/07-truth-seeking/experimental-design.md](../../domains/07-truth-seeking/experimental-design.md)

- **Blinding**: Prevent expectation effects by concealing treatment from subjects and evaluators
  - Link: [domains/07-truth-seeking/experimental-design.md](../../domains/07-truth-seeking/experimental-design.md)

- **Replication**: Verify findings by repeating under independent conditions
  - Link: [domains/07-truth-seeking/experimental-design.md](../../domains/07-truth-seeking/experimental-design.md)

- **Control Groups**: Compare against baseline to isolate specific causal effects
  - Link: [domains/07-truth-seeking/experimental-design.md](../../domains/07-truth-seeking/experimental-design.md)

### From Investigative Journalism

- **Source Triangulation**: Verify claims through multiple independent sources
  - Link: [domains/07-truth-seeking/investigative-journalism.md](../../domains/07-truth-seeking/investigative-journalism.md)

- **Document Authentication**: Verify provenance and integrity of evidence
  - Link: [domains/07-truth-seeking/investigative-journalism.md](../../domains/07-truth-seeking/investigative-journalism.md)

- **Follow the Money**: Trace financial flows to reveal hidden relationships
  - Link: [domains/07-truth-seeking/investigative-journalism.md](../../domains/07-truth-seeking/investigative-journalism.md)

### From Logic & Critical Thinking

- **Identifying Logical Fallacies**: Recognize invalid argument structures
  - Link: [domains/07-truth-seeking/logic-critical-thinking.md](../../domains/07-truth-seeking/logic-critical-thinking.md)

- **Necessary vs Sufficient Conditions**: Distinguish what must be true from what guarantees truth
  - Link: [domains/07-truth-seeking/logic-critical-thinking.md](../../domains/07-truth-seeking/logic-critical-thinking.md)

- **Burden of Proof**: Allocate responsibility for providing evidence appropriately
  - Link: [domains/07-truth-seeking/logic-critical-thinking.md](../../domains/07-truth-seeking/logic-critical-thinking.md)

### From Formal Verification

- **Exhaustive Case Analysis**: Verify by checking all possible cases systematically
  - Link: [domains/07-truth-seeking/formal-verification.md](../../domains/07-truth-seeking/formal-verification.md)

- **Invariant Checking**: Verify that properties hold across all states
  - Link: [domains/07-truth-seeking/formal-verification.md](../../domains/07-truth-seeking/formal-verification.md)

### From Bayesian Statistics

- **Prior-Likelihood-Posterior Decomposition**: Separate prior plausibility from evidence strength
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md)

- **Likelihood Ratio Thinking**: Assess how diagnostic evidence is for the claim
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md)

- **Base Rate Anchoring**: Start with prior probability before evaluating specific evidence
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md)

### From Intelligence Analysis

- **Source Reliability Assessment**: Evaluate credibility and access of information sources
  - Link: [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md)

- **Analysis of Competing Hypotheses**: Test claim against alternative explanations
  - Link: [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md)

- **Deception Detection**: Look for indicators of deliberate misinformation
  - Link: [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md)

### From Medical Diagnostics

- **Test Sensitivity and Specificity**: Understand false positive and false negative rates
  - Link: [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md)

## Recommended Workflow

1. **Assess prior plausibility**: How likely is the claim before examining evidence?
2. **Identify the claim's structure**: Is it causal, correlational, descriptive, or predictive?
3. **Evaluate source credibility**: What's the source's track record, expertise, and potential bias?
4. **Examine the evidence**:
   - Is it from randomized controlled experiment or observational data?
   - Are confounds controlled for?
   - Is sample size adequate?
   - Could results be due to chance?
5. **Triangulate sources**: Do multiple independent sources corroborate?
6. **Check for logical fallacies**: Is the argument structurally valid?
7. **Consider alternative explanations**: What else could produce this evidence?
8. **Calculate likelihood ratio**: How diagnostic is this evidence for the claim vs alternatives?
9. **Update belief proportionally**: Combine prior with evidence strength for posterior confidence
10. **Seek replication**: Has anyone independently verified the finding?

## Example Application

**Scenario**: Evaluating claim that "new productivity app increases output by 50%"

1. **Prior plausibility**: Most productivity claims are exaggerated; 50% is very large effect; moderate skepticism warranted
2. **Claim structure**: Causal claim (app causes productivity increase)
3. **Source**: Startup company blog post (potential bias: selling the product)
4. **Evidence examination**:
   - Study design: Before-after comparison with 50 users (weak: no control group)
   - Confounds: Users self-selected to try app (motivated users), Hawthorne effect likely
   - Sample: Small (n=50), short duration (1 month)
   - Statistics: No significance testing reported
5. **Triangulation**: No independent studies, only company claims
6. **Logical fallacies**: Post hoc ergo propter hoc (correlation doesn't imply causation without controls)
7. **Alternative explanations**:
   - Motivated users would improve anyway
   - Hawthorne effect (being observed increases performance)
   - Regression to mean (users tried app during low-productivity period)
   - Measurement error (self-reported productivity)
8. **Likelihood ratio**: This evidence (uncontrolled before-after) has low diagnosticity (maybe 2:1 in favor)
9. **Updated belief**: Start skeptical, weak evidence, remain skeptical but slightly more open (5% → 10% credence)
10. **Replication**: Need randomized controlled trial with objective productivity measures

**Conclusion**: Claim is plausible but not verified; evidence is weak; remain appropriately skeptical

## Example of Strong Verification

**Scenario**: Evaluating claim that "vitamin D supplementation reduces COVID-19 severity"

1. **Prior**: Biologically plausible (vitamin D affects immune function); moderate prior
2. **Structure**: Causal claim
3. **Sources**: Multiple peer-reviewed studies in medical journals
4. **Evidence**:
   - RCT with 500 patients, randomized to vitamin D or placebo
   - Double-blind (neither patients nor doctors knew assignment)
   - Primary outcome: ICU admission rate
   - Results: 12% ICU rate in treatment vs 22% in control (p=0.003)
5. **Triangulation**: Three independent RCTs show similar effects
6. **Logic**: Valid causal inference due to randomization
7. **Alternatives**: Randomization eliminates most confounds
8. **Likelihood ratio**: Strong evidence (maybe 20:1 in favor)
9. **Update**: Moderate prior + strong evidence = high confidence (60-70%)
10. **Replication**: Multiple independent RCTs confirm

**Conclusion**: Claim is well-verified; high confidence appropriate

## Common Pitfalls

- **Motivated reasoning**: Evaluating evidence more critically when it opposes your preferences
- **Source credibility heuristic**: Accepting claims from prestigious sources without checking evidence
- **Correlation-causation confusion**: Treating observational data as causal proof
- **P-value misinterpretation**: Treating p<0.05 as "proved" rather than "some evidence against null"
- **Publication bias neglect**: Not accounting for selective reporting of positive results
- **Single study reliance**: High confidence based on one study before replication
- **Base rate neglect**: Ignoring prior probability when evaluating evidence
- **Unfalsifiability**: Accepting claims that cannot be tested or disproven
- **Burden of proof reversal**: Demanding others disprove claims rather than providing positive evidence
