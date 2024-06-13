- [1. Association (Seeing/Observing)](#1-association-seeingobserving)
- [2. Intervention (Doing)](#2-intervention-doing)
- [3. Counterfactuals (Imagining)](#3-counterfactuals-imagining)
- [Summary:](#summary)

Judea Pearl's causal hierarchy outlines three levels of problems that correspond to different kinds of causal relationships and reasoning:

### 1. Association (Seeing/Observing)

**Level:** The first level of Pearl's causal hierarchy is association. This level deals with observing and describing statistical relationships between variables. At this stage, you can identify correlations and patterns but cannot infer causation. The primary tool for this level is probability theory.

**Example Questions:**

- What is the probability of Y given X? (P(Y|X))
- Are smoking and lung cancer correlated?

### 2. Intervention (Doing)

**Level:** The second level is intervention, which involves understanding how manipulating one variable affects another. This level requires causal models to predict the effects of interventions. This is where the concept of "do-calculus" comes into play, which allows us to reason about interventions (e.g., what happens if we force a change in a variable).

**Example Questions:**

- What happens to Y if we intervene and set X to a specific value? (P(Y|do(X=x)))
- If we force someone to stop smoking, how will it affect their likelihood of getting lung cancer?

### 3. Counterfactuals (Imagining)

**Level:** The third and highest level is counterfactuals. This level deals with hypothetical scenarios and understanding what would have happened under different circumstances. Counterfactual reasoning allows us to evaluate causal claims in a more nuanced way, considering alternate realities or scenarios.

**Example Questions:**

- What would have happened to Y if X had been different, given that we observed Z? (P(Y_X=x|Z))
- Would the patient have survived if they had received a different treatment?

### Summary:

1. **Association:** Identifying patterns and correlations (seeing/observing).
2. **Intervention:** Understanding the effects of actions and interventions (doing).
3. **Counterfactuals:** Exploring hypothetical scenarios and alternate outcomes (imagining).

Each level requires progressively more sophisticated tools and assumptions to make causal inferences, with counterfactuals being the most complex and powerful form of causal reasoning.
