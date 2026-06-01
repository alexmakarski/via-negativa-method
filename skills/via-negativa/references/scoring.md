# Via Negativa Scoring System

A standardized way to compare systems and track them over time. Scores are
directional, not predictions. Their purpose is consistency, not precision.

## How this scorecard is constrained

Scoring is the weakest part of the framework: scorecards drift toward false
precision, the exact failure that Section 4 (False Precision Detector) exists to
catch. So this scorecard is deliberately bounded.

- Full audits only. Quick and Standard audits do not score.
- The score never leads. Run the narrative analysis first; attach scores after.
- The score never substitutes for the analysis. A number is a summary of a
  finding, never a replacement for it.
- Apply Section 4 to the scorecard itself. If a number is being treated as
  understanding, flag it and revert to the narrative.
- A score should start a conversation. It should never end one.

## Scale

Use 1-10. General rule: 1 = Excellent / Low Risk, 10 = Poor / High Risk.
Document the assumptions behind each score.

Note the two survivability-style axes (Optionality, Survivability) invert the
risk reading: there, higher is better. Keep the per-axis interpretation bands in
view so a reader never misreads a 9.

## The seven axes

### 1. Fragility — how easily the system is damaged by volatility
Evaluate: single points of failure, dependency concentration, forecast dependence, coupling, recovery capability.
1-3 Robust | 4-6 Moderate | 7-8 Fragile | 9-10 Extremely Fragile

### 2. Complexity — operational complexity
Evaluate: number of tools, processes, dependencies, products, exceptions.
1-3 Simple | 4-6 Moderate | 7-8 Complex | 9-10 Excessively Complex

### 3. Optionality — future flexibility (higher is better)
Evaluate: reversible decisions, vendor portability, strategic flexibility, switching costs, experimentation capability.
1-3 Locked In | 4-6 Moderate | 7-8 Flexible | 9-10 Highly Optional

### 4. Concentration — dependence on a few critical components
Evaluate: customer, vendor, revenue concentration, key-person dependence.
1-3 Diversified | 4-6 Moderate | 7-8 High | 9-10 Dangerous

### 5. Incentive Alignment — rewards versus desired outcomes
Evaluate: skin in the game, reward structure, downside sharing, agency conflicts.
1-3 Strong | 4-6 Moderate | 7-8 Significant Misalignment | 9-10 Severe

### 6. Information Quality — reliability of decision inputs
Evaluate: accuracy, timeliness, completeness, verifiability, distortion risk.
1-3 High | 4-6 Mixed | 7-8 Poor | 9-10 Dangerous Information Environment

### 7. Survivability — ability to survive adverse conditions (higher is better)
Evaluate: cash resilience, dependency resilience, recovery capability, tail-risk exposure, operational resilience.
1-3 Survival Threatened | 4-6 Vulnerable | 7-8 Durable | 9-10 Highly Survivable

## Aggregate scorecard

| Category | Score (1-10) | One-line basis |
|----------|--------------|----------------|
| Fragility |  |  |
| Complexity |  |  |
| Optionality |  |  |
| Concentration |  |  |
| Incentive Alignment |  |  |
| Information Quality |  |  |
| Survivability |  |  |

Never average a risk axis against a survivability axis without saying so; the
aggregate is a discussion prompt, not a grade. If forced to summarize: Excellent
8+, Strong 6-7.9, Moderate 4-5.9, Weak 2-3.9, Critical under 2, with axes read in
their own direction.

The framework remains primary. The scores are summaries.
