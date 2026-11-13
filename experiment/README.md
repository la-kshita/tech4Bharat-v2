# PCB1 benchmark experiment archive

This folder preserves the available evidence from the earlier VisA PCB1 diagnostic experiment. It is not a validated model release or a complete reproduction bundle.

## Start with

1. [Experiment report](artifacts/EXPERIMENT_REPORT.md) for the results and interpretation.
2. [Frozen protocol](PROTOCOL.md) for the dataset split, thresholding, measurements, and provisional stop/go screen.
3. [Machine-readable summary](results/summary.json) and [failure examples](artifacts/failure_examples.json) for supporting records.

## Headline results

- Reference matching flagged **15/80 defects (18.75%)** and **1/100 normal images (1%)**.
- PaDiM flagged **45/80 defects (56.25%)** and falsely flagged **15/100 normal images (15%)**.
- Both methods failed the experiment's predeclared provisional screen. These targets were engineering screens for this experiment, not industrial requirements.

This was a custom VisA PCB1 benchmark split, not official VisA leaderboard performance. Synthetic lighting/blur transforms were stress tests, not real factory lighting. A phone, factory, manufacturer, buyer, or expert labeler was not tested. Human review time and buyer acceptance remain unknown.

## What is included and excluded

Included: report, protocol, available result JSON, source download manifest, and failure examples. Benchmark images and model binaries are excluded. Some source scripts listed in the historical checksum record are not present in this archive, so the experiment cannot be rerun from these files alone. The checksum list is retained as provenance, not as proof of a complete source snapshot.

The separate project [dataset shortlist](../COMPONENT_DATASETS.md) and [research overview](../research/overview.md) explain how to interpret these results for the proposed product.

