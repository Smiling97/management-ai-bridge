---
layout: default
title: Analysis Prompts
description: Prompts for management and organizational analysis.
---

# Analysis Prompts

## Organizational Diagnosis

### Use Case

Analyze an organizational situation from multiple plausible perspectives.

### Input Needed

Situation, stakeholders, symptoms, constraints, and available evidence.

### Prompt

```text
Analyze this organizational situation without assuming one correct cause.

Situation: [description]
Stakeholders: [list]
Symptoms: [list]
Evidence: [evidence]
Constraints: [constraints]

Generate three plausible diagnoses, evidence for and against each, missing information, and risks of acting too early.
```

### Expected Output

Competing diagnoses and evidence needs.

### Review Criteria

Check whether the analysis separates symptoms, causes, and remedies.

## Stakeholder Map

### Use Case

Map affected groups before a change, policy, or decision.

### Input Needed

Decision context, known stakeholders, goals, and constraints.

### Prompt

```text
Create a stakeholder map for this management situation.

Context: [context]
Known stakeholders: [list]
Goals: [goals]
Constraints: [constraints]

For each stakeholder, identify interests, likely concerns, influence, information needs, and engagement approach.
```

### Expected Output

A stakeholder table that supports planning and communication.

### Review Criteria

Look for missing stakeholders and oversimplified interests.
