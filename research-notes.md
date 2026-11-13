# PCB inspection research notes

## Proposed workflow

A worker selects or scans the PCB model and revision, captures a guided image, and the app compares visible components with the approved inspection plan. It flags possible missing components, visible placement/orientation errors, and reversed polarity where the markings and reference are clear. The worker or reviewer confirms findings; unclear images, missing plans, and uncertain results go to manual review. A “no issue detected” result is not an approval. Start with one board/revision and consistent lighting, framing, and orientation.

## Dataset leads

- **VisA PCB1–PCB4** ([official repository and data](https://github.com/amazon-science/spot-diff)): assembled-board anomaly benchmark; some structural defects are relevant. PCB1 was tested in the previous experiment and failed its provisional screen. Benchmark results do not establish factory performance.
- **FPIC / FICS PCB Image Collection** ([collection](https://physicaldb.ece.ufl.edu/index.php/fics-pcb-image-collection-fpic/)): populated-board component annotations useful for detection/localization; not a verified source of missing, misaligned, or reversed-polarity defect labels.
- **PCB-MC** ([paper](https://arxiv.org/abs/2609.39427)): candidate for missing-component detection. Confirm downloadable data, labels, and terms before relying on it.
- **DeepPCB** ([official repository](https://github.com/tangsanli5201/DeepPCB)): bare-board copper-pattern defects, not populated-board assembly inspection. The dataset source restricts use to research.

Misalignment and polarity remain gaps in the public data reviewed so far. Expect to collect target-board images paired with the approved board revision and placement/orientation references, then obtain qualified labels for normal and defective examples. Check dataset access and licence terms before use. See [component shortlist](COMPONENT_DATASETS.md) and [full catalogue](DATASET_CATALOGUE.md) for more candidates and limitations.

## Prior experiment evidence

The copied [experiment report](experiment/artifacts/EXPERIMENT_REPORT.md) found that both tested VisA PCB1 methods failed provisional detection screens. The copied README, protocol, per-image metrics, split audit, checksums, failure examples/gallery, and focused test scripts preserve the key review evidence under `experiment/`. These are research records, not a validated product model. The old app, virtual environment, installed dependencies, model files, and datasets were not copied; this is not a self-contained rerun package. The original research backup remains separate; this repository preserves selected evidence only.

## Questions to settle with the intended users

1. How will a worker identify the board and revision, and where does the approved BOM/placement plan come from?
2. Which component sizes and defect types are visibly inspectable in the intended camera setup? Is one full-board photo enough, or are guided close-ups needed?
3. Which check should the pilot prioritize: missing parts, placement/orientation, or polarity?
4. Who confirms flags and decides routing/rework? What evidence and history must each inspection retain?
5. What missed-issue rate, unnecessary-recheck rate, capture time, and “cannot inspect” rate are acceptable for a supervised pilot?
6. What target-board examples and expert review can the manufacturer provide, and what are the privacy/retention rules?

Treat these as questions for discovery; no production requirements or performance claims have been established.

