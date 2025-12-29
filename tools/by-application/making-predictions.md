# Making Predictions

How to forecast future events with incomplete information.

## Overview

Prediction requires combining base rates, specific evidence, and model uncertainty. The tools below help you avoid overconfidence, anchor to relevant reference classes, update beliefs proportionally, and communicate uncertainty honestly.

## Relevant Tools

### From Bayesian Statistics

- **Base Rate Anchoring**: Start with the frequency of the outcome in the appropriate reference class before considering individual evidence
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md#base-rate-anchoring)

- **Proportional Belief Updating**: Update confidence in proportion to evidence strength, avoiding both anchoring and overreaction
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md#proportional-belief-updating)

- **Prior-Likelihood-Posterior Decomposition**: Separate prior plausibility, evidence strength, and final conclusion
  - Link: [domains/01-decision-under-uncertainty/bayesian-statistics.md](../../domains/01-decision-under-uncertainty/bayesian-statistics.md#prior-likelihood-posterior-decomposition)

### From Meteorology

- **Ensemble Forecasting**: Generate multiple predictions using different models or assumptions to capture uncertainty
  - Link: [domains/01-decision-under-uncertainty/meteorology.md](../../domains/01-decision-under-uncertainty/meteorology.md#ensemble-thinking)

- **Confidence Calibration**: Match confidence levels to actual accuracy rates through systematic tracking
  - Link: [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md#confidence-calibration)

- **Probabilistic Forecasting**: Express predictions as probability distributions, not point estimates
  - Link: [domains/01-decision-under-uncertainty/meteorology.md](../../domains/01-decision-under-uncertainty/meteorology.md#probabilistic-expression)

### From Intelligence Analysis

- **Analysis of Competing Hypotheses (ACH)**: Systematically evaluate evidence against multiple alternative explanations
  - Link: [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md#analysis-of-competing-hypotheses-ach)

- **Red Team Analysis**: Challenge your main prediction by arguing for alternative outcomes
  - Link: [domains/07-truth-seeking/logic-critical-thinking.md](../../domains/07-truth-seeking/logic-critical-thinking.md#red-team-analysis)

- **Indicators and Warnings**: Identify observable signals that would confirm or disconfirm your prediction
  - Link: [domains/01-decision-under-uncertainty/intelligence-analysis.md](../../domains/01-decision-under-uncertainty/intelligence-analysis.md#diagnostic-vs-supportive-evidence)

### From System Dynamics

- **Stock-Flow Distinction**: Distinguish between levels (stocks) and rates of change (flows) to predict accumulations over time
  - Link: [domains/04-complex-systems/system-dynamics.md](../../domains/04-complex-systems/system-dynamics.md#stock-flow-distinction)

- **Feedback Loop Analysis**: Trace reinforcing and balancing loops to predict system behavior
  - Link: [domains/09-resource-allocation/operations-research.md](../../domains/09-resource-allocation/operations-research.md#positive-feedback-loops)

### From Economics

- **Marginal Analysis**: Predict how outcomes change with small incremental changes in inputs
  - Link: [domains/09-resource-allocation/economics.md](../../domains/09-resource-allocation/economics.md#marginal-thinking)

- **Equilibrium Thinking**: Identify stable states where opposing forces balance
  - Link: [domains/09-resource-allocation/economics.md](../../domains/09-resource-allocation/economics.md#equilibrium-as-analytical-tool)

### From Machine Learning

- **Cross-Validation**: Test predictions on held-out data to estimate real-world performance
  - Link: [domains/10-pattern-recognition/machine-learning.md](../../domains/10-pattern-recognition/machine-learning.md#cross-validation-robust-performance-estimation)

- **Bias-Variance Tradeoff**: Balance between oversimplifying (high bias) and overfitting to noise (high variance)
  - Link: [domains/10-pattern-recognition/machine-learning.md](../../domains/10-pattern-recognition/machine-learning.md#the-bias-variance-tradeoff)

## Recommended Workflow

1. **Establish base rate**: What's the frequency of this outcome in the reference class?
2. **Partition hypothesis space**: What are the distinct possible outcomes?
3. **Identify indicators**: What evidence would distinguish between outcomes?
4. **Generate ensemble**: Consider multiple models/approaches
5. **Update proportionally**: Adjust confidence based on evidence strength
6. **Express probabilistically**: State predictions as probability distributions
7. **Calibrate over time**: Track predictions against outcomes to improve

## Example Application

**Scenario**: Predicting whether a new product launch will succeed.

1. **Base rate**: What percentage of similar products succeed in this category? (e.g., 30%)
2. **Hypotheses**: Strong success (>50% market share), moderate success (20-50%), weak success (5-20%), failure (<5%)
3. **Indicators**: Pre-orders, early reviews, competitor responses, market conditions
4. **Ensemble**: Ask marketing team, use historical model, run customer surveys
5. **Update**: As pre-orders come in, adjust probabilities proportionally
6. **Express**: "35% chance of moderate success, 25% strong, 25% weak, 15% failure"
7. **Track**: Record prediction and outcome to improve calibration

## Common Pitfalls

- **Inside view dominance**: Focusing on case-specific details while ignoring base rates
- **False precision**: Expressing uncertainty as exact probabilities when evidence doesn't support it
- **Update asymmetry**: Overweighting confirming evidence, underweighting disconfirming evidence
- **Single model reliance**: Trusting one forecasting approach without ensemble validation
- **Calibration neglect**: Never checking predictions against outcomes
