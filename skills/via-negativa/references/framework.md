# Via Negativa Operating System v2 — Framework Reference

The canonical 20-section method, condensed. This file is the section catalog the
`via-negativa` skill draws from. Each section lists its Purpose, Core Question,
and Required Output. The tables are the operational core; reproduce their columns
when running a section.

> Core question of the whole system:
> What should stop existing so the system becomes harder to kill?

## Contents

- First Principles (10)
- Layer I — Diagnosis (sections 1-5)
- Layer II — Structural (sections 6-8)
- Layer III — Decision (sections 9-12)
- Layer IV — Operating (sections 13-15)
- Layer V — Validation (sections 16-18)
- Layer VI — Execution (sections 19-20)

---

## First Principles

1. Survival Before Optimization
2. Remove Before Adding
3. Avoid Ruin
4. Complexity Carries a Burden of Proof
5. Incentives Explain Behavior
6. Optionality Has Value
7. Small Failures Are Healthy
8. Concentration Creates Fragility
9. Attention Is Scarce
10. Reality Over Narrative

---

## Layer I — Diagnosis

Determines reality. What is actually true about this system.

### 1. Executive Diagnosis

Purpose: Identify the central reality of the system.

Required Output:

```
EXECUTIVE DIAGNOSIS
- System Purpose
- Primary Fragility
- Hidden Complexity
- False Knowledge
- Primary Source of Damage
- First Removal Candidate
```

### 2. Via Negativa Map

Purpose: Identify what should be removed, reduced, simplified, constrained, isolated, or capped.

| Area | Current State | Potential Harm | Recommended Action | Expected Benefit | Risk |

### 3. Fragility Audit

Purpose: Determine what breaks when assumptions fail.

| Stressor | What Breaks | Why | Severity | Probability | Warning Signal | Via Negativa Fix |

### 4. False Precision Detector

Purpose: Identify where measurement is being mistaken for understanding.

| Metric | Why It Looks Useful | Why It Is Dangerous | Better Alternative | Decision Rule |

### 5. Hidden Tail Risk

Purpose: Identify low-probability, high-impact threats to survival.

| Tail Risk | Why It Is Hidden | Worst Case | Downside Cap | Required Removal |

---

## Layer II — Structural

Explains why the system behaves the way it does.

### 6. Failure Mode & Blast Radius Analysis

Purpose: Determine how failures occur, spread, are detected, contained, and recovered.
Core Question: If this breaks, what breaks next?

| Component | Failure Mode | Immediate Impact | Secondary Impact | Blast Radius | Detection Time | Recovery Time | Containment Method |

Failure categories: Single Point of Failure, Cascading Failure, Hidden Coupling, Recovery Bottlenecks, Delayed Detection.
Blast radius scale: Local, Functional, Departmental, Operational, Systemic, Existential.

### 7. Incentive Autopsy

Purpose: Determine what actors are actually rewarded for.
Core Question: What are people rewarded for?

| Actor | Claimed Objective | Actual Incentive | System Damage | Correction |

Actors to scan: Leadership, Customers, Sales, Marketing, Product, Engineering, Operations, Vendors, Consultants, Data Providers, Algorithms.
Common failures: Activity Over Outcomes, Volume Over Quality, Short-Term Rewards, Privatized Upside, No Skin in the Game.

### 8. Attention Allocation Audit

Purpose: Determine what receives attention versus what deserves it.
Core Question: What matters that we are ignoring?

| Area | Current Attention | Importance | Over/Under Attended | Recommendation |

Distortions: Dashboard Addiction, Growth Obsession, Internal Politics, Feature Obsession, Revenue Fixation, Short-Term Thinking.

---

## Layer III — Decision

Determines what should change.

### 9. Complexity Kill List

Purpose: Identify components to remove, reduce, simplify, merge, delay, isolate, or kill.
Core Question: If this disappeared tomorrow, what would happen?

| Rank | Component | Action | Why | Expected Impact | Confidence |

Common targets: Reports, Meetings, Features, Customers, Vendors, Metrics, Processes, Automations, Product Lines.

### 10. Subtraction Before Addition

Purpose: Ensure additions occur only after subtraction has failed.
Core Question: Can this problem be solved by removing something?

| Proposed Addition | Problem | Removal Alternative | Reduction Alternative | Constraint Alternative | Still Necessary? |

Mandatory questions: Can removal solve it? Reduction? Narrowing scope? Incentives? Rules? Downside capping?

### 11. Optionality & Reversibility Audit

Purpose: Evaluate future freedom of action.
Core Question: What future choices are being preserved or destroyed?

| Decision Area | Current State | Optionality Gained | Optionality Lost | Reversible? | Recommendation |

### 12. Anti-Fragility Test

Purpose: Determine whether the system is Fragile, Robust, or Antifragile.
Core Question: Does volatility help or hurt?

| System Area | Classification | Evidence | Improvement |

Tests: Can failures stay small? Is downside capped? Is upside open? Are decisions reversible? Does the system learn?

---

## Layer IV — Operating

Defines operating behavior. Good systems rely less on intelligence and more on constraints.

### 13. Operational Rules

Purpose: Convert analysis into enforceable operating constraints. Rules must be Specific, Testable, Enforceable, Fragility-Reducing.

| Rule | Purpose | Failure Prevented | Enforcement Method |

Categories: Scaling, Customer, Product, Process, Automation, Metrics, Financial, Vendor, Hiring, Decision rules.

### 14. Minimal Viable System

Purpose: Design the smallest version of the system that still works.
Core Question: What is the minimum that must exist?

| System Area | Minimum Required Version | Why It Must Exist | Removed Components |

Cover: Minimum Inputs, Process, Team, Tools, Metrics, Customer Promise, Feedback Loop, Failure Controls.

### 15. Decision Tree

Purpose: Convert the framework into operational decision logic.
Core Principle: Most decisions should be evaluated as reversible or irreversible.

Core rules:
- If downside is uncapped, do not proceed.
- If uncertainty is high, run a small test.
- If reversible, decide quickly. If irreversible, decide slowly.
- Buy learning before commitment.
- Require stronger justification for complexity.
- Prefer removal when it solves the problem.
- Safeguard against concentration. Protect optionality. Protect survival.

Outcomes: Proceed | Proceed With Constraints | Test First | Reduce Scope | Isolate | Delay | Reject.
Output form: If [condition], then [action].

---

## Layer V — Validation

Challenges information, assumptions, recommendations, consequences. The framework assumes it may be wrong.

### 16. Information Quality Audit

Purpose: Evaluate the quality of information entering the system.
Core Principle: A decision cannot be better than the information supporting it.

| Information Source | Reliability | Timeliness | Distortion Risk | Failure Mode | Recommendation |

Failure modes: Delayed, Distorted, Incomplete, Incentivized, Noisy, Selective.

### 17. Red Team Critique

Purpose: Attack the framework's own conclusions.
Core Principle: Strong ideas survive criticism. Weak ideas require protection.

Run each sub-analysis:

- Assumption Attack: | Assumption | Why It Might Be Wrong | Consequence If Wrong | Evidence Needed |
- Evidence Attack: | Recommendation | Missing Evidence | Why It Matters | Confidence Impact |
- Removal Backfire: | Removal | Potential Backfire | Severity | Mitigation |
- Simplification Backfire: | Simplification | Potential Harm | Severity | Mitigation |
- Hidden Dependency: | Dependency | Why It Matters | Failure Scenario |
- Alternative Explanation: | Original Diagnosis | Alternative Explanation | Plausibility | Evidence Needed |
- Survival vs Efficiency: | Proposed Removal | Hidden Resilience Value | Risk |
- Optionality: | Recommendation | Optionality Lost | Importance | Acceptable? |

On Full audits this section is executed by the isolated `via-negativa-redteam`
agent, not self-graded. See SKILL.md.

### 18. Second-Order Effects Analysis

Purpose: Analyze consequences beyond immediate outcomes.
Core Principle: First-order effects are visible. Second-order effects often matter more.

| Action | First-Order Effect | Second-Order Effect | Third-Order Effect | Risk | Recommendation |

Examples: Automation -> less labor -> less visibility -> hidden failures. Features -> more capability -> more complexity -> slower development. Vendor consolidation -> lower cost -> higher concentration -> systemic risk.

---

## Layer VI — Execution

Converts analysis into prioritized action. Stop harmful activity before starting new activity.

### 19. Final Via Negativa Action Plan

Purpose: Convert analysis into prioritized action.

Produce these buckets, in this order:

- Remove Immediately: | Item | Why Remove | Expected Benefit | Urgency | Confidence |
- Reduce Immediately: | Item | Current Level | Recommended Level | Expected Benefit | Confidence |
- Isolate Immediately: | Risk | Why It Remains | Isolation Method | Expected Reduction |
- Test Before Scaling: | Initiative | Assumption | Smallest Useful Test | Success Criteria |
- Do Not Add Yet: | Proposed Addition | Why Delay | What Must Happen First |
- Add Only After Subtraction: | Addition | Potential Value | Required Removal | Readiness Criteria |

Prioritization: | Action | Survival Impact | Risk Reduction | Complexity Reduction | Ease Of Execution | Priority |

Time horizons:
- First 30 Days: Removals, Reductions, Immediate Risk Controls.
- First 90 Days: Simplification, Validation, Dependency Reduction.
- First Year: Structural Improvements, Optionality Increases, Long-Term Survivability.

### 20. Final Answer Standard

Purpose: Govern how every Via Negativa analysis is written and evaluated.

Required characteristics: Direct, Practical, Specific, Ruthless But Fair (attack systems, not people), Survival Focused, Cash Focused, Quality Focused, Risk Focused, Incentive Focused, Simplicity Focused.

Prohibited: Generic consulting language, Motivational language, Framework inflation, Feature bias, Automation bias, Scale bias, Metric worship.

Evaluation checklist for every recommendation: Does it reduce fragility? Improve survivability? Reduce complexity? Identify incentives? Cap downside? Preserve optionality? Remove before adding? Can it be implemented?

Priority hierarchy (resolve all conflicts in this order):

1. Prevent Ruin
2. Reduce Fragility
3. Improve Incentives
4. Improve Quality
5. Reduce Complexity
6. Improve Efficiency
7. Pursue Growth

Final test, a completed analysis answers: What to remove first? Reduce first? Isolate first? Test first? Not add? What threatens survival? What creates fragility? What incentive causes damage? What complexity should disappear? What action happens tomorrow?
