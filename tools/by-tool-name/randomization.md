# Randomization

**Appears in:** Experimental Design, Bayesian Statistics, Machine Learning, Formal Verification

## Core Concept

Random assignment of subjects to conditions ensures that groups are statistically equivalent in expectation across all variables - measured, unmeasured, known, and unknown. It's the only method that controls for confounds you don't even know exist.

## Domain-Specific Variations

### In Experimental Design
- **Context:** Gold standard for causal inference in clinical trials and experiments
- **Key operation:** Use a random number generator to assign treatments, not alternation or judgment
- **Link:** domains/07-truth-seeking/experimental-design.md#randomization

### In Bayesian Statistics
- **Context:** Monte Carlo methods for sampling from posterior distributions
- **Key operation:** Generate random samples to approximate intractable probability distributions
- **Link:** domains/01-decision-under-uncertainty/bayesian-statistics.md

### In Machine Learning
- **Context:** Random initialization, stochastic gradient descent, random forests
- **Key operation:** Use randomization to escape local optima and explore solution space
- **Link:** domains/10-pattern-recognition/machine-learning.md

### In Formal Verification
- **Context:** Randomized testing and property-based testing
- **Key operation:** Generate random test cases to find edge cases that structured testing misses
- **Link:** domains/07-truth-seeking/formal-verification.md

## When to Use This Tool

Use randomization when:
- Testing causal hypotheses where you control assignment
- Breaking systematic biases and confounds
- Exploring large solution spaces efficiently
- Need to ensure groups are comparable at baseline
- Personal experiments with productivity methods or habits

Randomization is conceptually simple but psychologically difficult - we prefer systematic rules. But systematic rules introduce bias that randomization prevents.
