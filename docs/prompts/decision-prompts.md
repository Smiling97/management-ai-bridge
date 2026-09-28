---
layout: default
title: Decision Prompts
description: Prompts for management decision support.
---

# Decision Prompts

## Decision Matrix

### Use Case

Compare management options against explicit criteria.

### Input Needed

Decision, options, criteria, constraints, and evidence.

### Prompt

```text
Create a decision matrix for this management decision.

Decision: [decision]
Options: [options]
Criteria: [criteria]
Evidence: [evidence]
Constraints: [constraints]

Include scores only if evidence supports scoring. For each option, list assumptions, risks, implementation requirements, and evidence gaps.
```

### Expected Output

A decision matrix with assumptions and risks.

### Review Criteria

Check whether the criteria reflect real priorities and whether scores are justified.

## Pre-Mortem

### Use Case

Identify failure modes before implementing a decision.

### Input Needed

Decision, implementation plan, stakeholders, timeline, and constraints.

### Prompt

```text
Run a pre-mortem for this management decision.

Decision: [decision]
Plan: [plan]
Stakeholders: [stakeholders]
Timeline: [timeline]
Constraints: [constraints]

Assume the decision failed one year later. Identify likely causes, early warning signs, mitigation actions, and what to monitor.
```

### Expected Output

A risk-oriented implementation review.

### Review Criteria

Confirm that risks are specific, observable, and actionable.
