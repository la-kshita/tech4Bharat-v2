# Dataset fit at a glance

No dataset reviewed here fully matches the proposed setting: a worker using a phone in a small unit to inspect a known populated board and preserve buyer-relevant quality evidence.

| Dataset | Useful for | Main gap for this project | Status in this research |
|---|---|---|---|
| VisA PCB1–PCB4 | Populated-board anomaly experiments | Benchmark images do not establish target-unit or phone performance; labels do not supply all desired defect subtypes | PCB1 used in the prior experiment; other PCB subsets not evaluated here |
| DeepPCB | Bare-board copper-pattern comparison with paired templates | Bare board, aligned scan-style images; not populated assembly inspection | Reviewed as a conditional bare-board alternative; not run here |
| FPIC / FICS-PCB | Component localization and board imagery | Component annotations are not verified labels for our missing, placement, or polarity decisions | Candidate reviewed; exact subset/labels need task-level checks |
| PCB-SAID | Few-shot surface-mount assembly defect research | Small image count and access/terms need confirmation | New research lead; not run here |
| PCB-MC | Missing-component localization at expected footprints | New preprint, board layout distribution and public release must be verified | New research lead; not run here |

## Selection rule

Choose one target task, one board model/revision, and one prescribed view. Inspect a small sample and verify the label schema, source, grouping, and licence before downloading or adopting a dataset. Keep results from bare-board inspection separate from populated-board assembly inspection.

## Full lists

- [Components-first dataset shortlist](../COMPONENT_DATASETS.md)
- [Full dataset catalogue](../DATASET_CATALOGUE.md)
- [Prior PCB1 experiment report](../experiment/artifacts/EXPERIMENT_REPORT.md)

The catalogue includes adjacent component datasets and options that are out of the current PCB scope. Their inclusion is not an endorsement or a claim that they were downloaded or tested.

