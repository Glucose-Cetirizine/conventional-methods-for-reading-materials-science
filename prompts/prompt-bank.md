# Prompt bank: materials-science paper reading

This page turns the original questions into reusable prompts. Replace the placeholders in angle brackets.

## 1. Whole-paper deep reading

### Prompt template

```text
Read the attached materials-science paper according to the following standards:

1. Explain the scientific story in plain language: what problem was solved, why it mattered, and how the authors solved it.
2. Explain all specialized and technical terms.
3. Identify the main innovations.
4. Highlight the contradictions, difficulties, bottlenecks, and conflicts. Explain the authors' thinking framework and methodology.
5. Explain every main figure clearly.
6. Give your own reading strategy and critical assessment.
7. Be detailed enough to turn a beginner into an expert.
8. Extract transferable thinking methods, bottom-level design logic, and unresolved problems.
```

### Expected output structure

```text
1. One-sentence summary
2. Research problem and bottleneck
3. Plain-language story
4. Technical glossary
5. Innovations
6. Contradictions and design logic
7. Figure-by-figure interpretation
8. Mechanism chain
9. Transferable methodology
10. Limitations and future work
```

---

## 2. Material synthesis and property logic

### Prompt template

```text
For the attached paper, explain the material synthesis and property-design logic.

Please answer:

1. Why did the authors choose this monomer, polymer, functional group, oxidation state, side chain, backbone, or block architecture?
2. What target material state were they trying to create?
3. Which intermolecular interactions control the key properties?
4. Why did they use these controls and comparisons?
5. What general design rules can be extracted?
6. How can this logic be transferred to other materials?
7. How could I develop a new material using the same thinking?
```

### Expected output structure

```text
1. Target property
2. Target material state
3. Key functional group
4. Synthesis choice
5. Property mechanism
6. Control experiments
7. Generalizable design rules
8. New-material development workflow
```

---

## 3. Why these characterization experiments?

### Prompt template

```text
For the attached paper, explain why each characterization or experiment was performed.

For each experiment, provide:

1. The question it answers.
2. The physical or chemical principle.
3. The expected evidence if the hypothesis is correct.
4. What competing explanation it excludes.
5. Where it sits in the evidence chain.
6. What would happen to the argument if this experiment were missing.
```

### Expected output structure

```text
Experiment name
- Question:
- Principle:
- Key result:
- Interpretation:
- Alternative explanation excluded:
- Position in evidence chain:
```

---

## 4. Figure-by-figure analysis

### Prompt template

```text
Analyze every main figure in the attached paper.

For each figure:

1. State what the figure is showing.
2. Explain each panel or major data block.
3. Identify the experimental comparison.
4. Explain the key result.
5. Explain why the authors needed this figure.
6. State what conclusion it supports.
7. Point out possible limitations or alternative interpretations.
```

### Expected output structure

```text
Figure N
- Purpose:
- Panel-by-panel explanation:
- Key comparison:
- Main conclusion:
- Why it matters:
- Caveats:
```

---

## 5. Mechanism and contradiction analysis

### Prompt template

```text
Identify the core contradiction or bottleneck in this paper.

Explain:

1. Why the conventional approach failed.
2. Why the problem was difficult.
3. What trade-off the authors had to manage.
4. How the authors turned a limitation into a useful mechanism.
5. How they designed controls to test the mechanism.
6. What would have falsified their hypothesis.
```

### Expected output structure

```text
Conventional view
Failure mode
Core contradiction
Key insight
Design solution
Evidence chain
Falsification criteria
```

---

## 6. Transferable methodology

### Prompt template

```text
Extract transferable methodology from this paper.

Explain how to apply the logic to other materials systems such as catalysts, batteries, membranes, coatings, sensors, protein formulation, polymer recycling, or nanoparticle delivery.

For each transfer:

1. State the abstract principle.
2. Give the original system.
3. Give a target system.
4. Explain how to redesign the material.
5. Define characterization experiments.
6. Define success criteria.
```

### Expected output structure

```text
Abstract principle
Original implementation
Transfer target
Redesign strategy
Expected properties
Required characterization
Success criteria
```

---

## 7. New-material development

### Prompt template

```text
Using the design logic from the attached paper, propose a new material.

Please provide:

1. Target application and performance metrics.
2. Desired guest state and microenvironment.
3. Candidate functional groups.
4. Polymer or material architecture.
5. Synthesis route.
6. Control materials.
7. Characterization plan.
8. Application test plan.
9. Risks and go/no-go criteria.
```

### Expected output structure

```text
Target
Desired state
Chemical design
Architecture
Synthesis
Controls
Characterization
Application testing
Risks
```

---

## 8. Review-style limitations analysis

### Prompt template

```text
Act as a constructive reviewer. Identify unresolved problems in the attached paper.

Please cover:

1. Scientific limitations.
2. Mechanistic uncertainties.
3. Characterization gaps.
4. Stability and scalability concerns.
5. Safety or regulatory issues.
6. Generalization risks.
7. Suggested follow-up experiments.
```

### Expected output structure

```text
Limitation
Why it matters
Possible risk
Missing evidence
Recommended follow-up
```
