# Recognizing Patterns

How to identify meaningful regularities in complex data and situations.

## Overview

Pattern recognition requires distinguishing signal from noise, avoiding overfitting to spurious patterns, and building mental models that generalize beyond training examples. The tools below help you see genuine patterns while avoiding false positives.

## Relevant Tools

### From Machine Learning

- **Bias-Variance Tradeoff**: Balance between oversimplifying (high bias) and overfitting to noise (high variance)
  - Link: [domains/10-pattern-recognition/machine-learning.md](../../domains/10-pattern-recognition/machine-learning.md)

- **Cross-Validation**: Test pattern on held-out data to verify generalization
  - Link: [domains/10-pattern-recognition/machine-learning.md](../../domains/10-pattern-recognition/machine-learning.md)

- **Feature Engineering**: Transform raw observations into meaningful predictive variables
  - Link: [domains/10-pattern-recognition/machine-learning.md](../../domains/10-pattern-recognition/machine-learning.md)

- **Regularization**: Penalize overly complex patterns to prefer simpler explanations
  - Link: [domains/10-pattern-recognition/machine-learning.md](../../domains/10-pattern-recognition/machine-learning.md)

### From Medical Diagnostics

- **Pattern Matching to Syndromes**: Recognize symptom clusters that indicate specific conditions
  - Link: [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md)

- **Bayesian Pattern Updating**: Start with base rate frequency of patterns, update with specific observations
  - Link: [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md)

- **Pathognomonic Signs**: Identify observations that definitively indicate a specific pattern
  - Link: [domains/10-pattern-recognition/medical-diagnostics.md](../../domains/10-pattern-recognition/medical-diagnostics.md)

### From Bayesian Statistics

- **Base Rate Anchoring**: Start with frequency of pattern in reference class before weighing specific evidence
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md)

- **Likelihood Ratio**: Assess how diagnostic an observation is for the pattern
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md)

### From Experimental Design

- **Control Groups**: Compare against baseline to isolate genuine pattern from background variation
  - Link: [domains/07-truth-seeking/experimental-design.md](../../domains/07-truth-seeking/experimental-design.md)

- **Multiple Testing Correction**: Adjust for false positives when examining many potential patterns
  - Link: [domains/07-truth-seeking/experimental-design.md](../../domains/07-truth-seeking/experimental-design.md)

### From Expertise Studies

- **Chunking**: Organize observations into meaningful higher-level patterns
  - Link: [domains/05-skill-mastery/expertise-studies.md](../../domains/05-skill-mastery/expertise-studies.md)

- **Mental Models**: Build causal understanding of why patterns occur, not just correlation
  - Link: [domains/05-skill-mastery/expertise-studies.md](../../domains/05-skill-mastery/expertise-studies.md)

### From Evolutionary Biology

- **Convergent Evolution**: Same pattern arising independently suggests adaptive pressure, not accident
  - Link: [domains/03-creative-generation/evolutionary-biology.md](../../domains/03-creative-generation/evolutionary-biology.md)

### From Network Science

- **Motif Detection**: Identify recurring small-scale network structures
  - Link: [domains/04-complex-systems/network-science.md](../../domains/04-complex-systems/network-science.md)

- **Scale-Free Patterns**: Recognize power-law distributions across many contexts
  - Link: [domains/04-complex-systems/network-science.md](../../domains/04-complex-systems/network-science.md)

## Recommended Workflow

1. **Gather observations**: Collect sufficient data across variety of contexts
2. **Define reference class**: What's the base rate of this pattern?
3. **Generate candidate patterns**: What regularities might explain the observations?
4. **Feature engineer**: Transform raw data into meaningful variables
5. **Test on held-out data**: Does pattern generalize beyond training examples?
6. **Apply regularization**: Prefer simpler patterns over complex ones
7. **Calculate likelihood ratio**: How diagnostic are observations for the pattern?
8. **Correct for multiple testing**: Adjust confidence if examining many patterns
9. **Build causal model**: Why does this pattern occur? What's the mechanism?
10. **Track performance**: Monitor whether pattern continues to hold

## Example Application

**Scenario**: Recognizing patterns in customer churn to predict who will cancel service.

1. **Observations**: Collect 1000 customer records with usage data and cancellation outcomes
2. **Reference class**: 15% of customers cancel within 6 months (base rate)
3. **Candidate patterns**:
   - Low usage in first month
   - Customer service contacts
   - Price-sensitive cohort
   - Competitor product launch
4. **Feature engineering**:
   - Transform raw usage into "engagement score"
   - Count support tickets
   - Calculate price relative to alternatives
5. **Cross-validation**:
   - Train pattern on 70% of data
   - Test on held-out 30%
   - Pattern correctly predicts 60% of cancellations
6. **Regularization**: Simple model (3 features) outperforms complex model (20 features) on test set
7. **Likelihood ratios**:
   - Low first-month engagement: 4:1 (strong predictor)
   - Support tickets: 2:1 (moderate)
   - Price sensitivity: 1.5:1 (weak)
8. **Multiple testing**: Examined 15 potential patterns, adjust significance threshold
9. **Causal model**: Low engagement → customer doesn't build habit → switches when competitor offers deal
10. **Monitoring**: Track prediction accuracy monthly, retrain when performance degrades

## Common Pitfalls

- **Overfitting**: Seeing spurious patterns in noise (apophenia)
- **Confirmation bias**: Noticing observations that fit pattern, ignoring those that don't
- **Base rate neglect**: Thinking pattern is common because you noticed examples, ignoring denominator
- **Multiple testing**: Finding "significant" patterns by chance when examining many candidates
- **No generalization testing**: Pattern works on training data but fails on new cases
- **Correlation without causation**: Recognizing co-occurrence without understanding mechanism
- **Sample bias**: Pattern exists in observed sample but not in broader population
- **Overly complex patterns**: Explaining data with elaborate theory when simple one suffices
- **Single example generalization**: Inferring pattern from one or two instances
- **Ignoring alternative patterns**: Focusing on first pattern noticed without considering alternatives
