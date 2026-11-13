# Research overview

## Research question

Can a narrow, board-specific visual inspection workflow help a small electronics unit capture more consistent quality evidence while keeping workers and owners in control of inspection decisions?

The proposed study begins with one populated PCB model and revision. It considers guided image capture, visible component checks, worker review, a retake/assisted-review path, and a batch record tied to the actual inspection. This is a pilot hypothesis, not a validated product specification.

## What the evidence says

1. **The general SME need is credible.** A 2025 systematic review of 770 articles identifies investment limits, skills shortages, high-variety/low-volume production, and insufficient training data as recurring barriers to machine vision adoption in manufacturing SMEs.
2. **PCB inspection changes with the task.** Research separates bare-board conductive-pattern checks from populated-board assembly checks. Evidence for one does not establish performance on the other.
3. **Public datasets are partial substitutes.** VisA PCB images support anomaly experiments; DeepPCB supports bare-board pattern comparison; component-image collections support localization. None alone proves field performance on the target unit's boards, phone camera, lighting, or pace.
4. **The earlier PCB1 test is cautionary.** The tested reference baseline and PaDiM configuration both failed their predeclared provisional screen. The experiment does not show that all methods or all boards will fail.
5. **Field evidence is still required.** Buyer defect priorities, rejection baseline, accepted quality proof, actual workspace conditions, board change rate, reviewer identity, and time available for labels have not been validated with target enterprises in this research archive.

## Proposed research sequence

- Confirm one target board/revision and the defects buyers care about.
- Obtain approved component/placement references and qualified normal/defect labels.
- Capture target-board examples in the intended workspace and phone setup.
- Measure image quality, misses, false flags, abstentions, worker review time, label agreement, and batch-record acceptance.
- Keep owner sign-off and buyer acceptance separate from automated suggestions.
- Expand scope only after the selected workflow clears agreed pilot criteria on an untouched target-board holdout.

## Claims boundary

The organizer's 10–15% missed-defect estimate is challenge-brief context, not our measured baseline. Dataset metrics are benchmark-specific. Our PCB1 results are not factory validation. No field study, buyer interview, phone deployment, or verified commercial dataset clearance is documented here.

