# VionWorks Research Template

Canonical starting point for public research, reproduction, benchmark, and study projects whose primary value is a well-defined question, transparent methodology, reproducible evidence, and explicit limitations.

## Use this template for

- paper reproductions
- benchmark studies
- comparative evaluations
- empirical investigations
- dataset studies
- research prototypes where the research question matters more than product delivery

Use the Technical Lab family instead when the primary goal is to prove a specific engineering capability through implementation. Use the Business Demo family when the primary goal is to solve a commercial problem.

## Required first steps

1. Replace every `REPLACE-ME` value in `PROJECT.yaml`.
2. Register the project in `VionWorks/portfolio-registry` and allocate its permanent `RES-###` ID.
3. State the research question before implementation or data collection.
4. Record relevant prior work and baselines.
5. Define methodology and metrics before presenting conclusions.
6. Separate measured results from interpretation.
7. Publish limitations and reproducibility instructions with the final result.

## Documentation structure

```text
docs/
├── QUESTION.md
├── LITERATURE.md
├── METHODOLOGY.md
├── RESULTS.md
├── LIMITATIONS.md
└── REPRODUCIBILITY.md
```

Code, notebooks, data adapters, figures, and experiment folders should be added according to the actual study rather than forced by the template.

## Research standard

A Research project should make it possible for another reader to determine:

- what exact question was asked
- what prior work or baseline it relates to
- how the evidence was produced
- which results were measured versus inferred
- what limitations constrain the conclusion
- whether the result can be reproduced

The goal is credible evidence and clear reasoning, not the appearance of certainty.

## Registry

Canonical taxonomy and metadata rules live in [VionWorks/portfolio-registry](https://github.com/VionWorks/portfolio-registry).
