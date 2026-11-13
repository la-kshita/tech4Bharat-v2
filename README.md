# PCB Inspection Research

Research archive for a proposed, board-specific inspection assistant for small electronics manufacturers.

The project explores whether guided phone capture, a board/revision-specific inspection plan, and worker-reviewed visual flags can help document checks on one selected PCB. It is a research and validation effort: no model or workflow in this repository is validated for production use.

## Research at a glance

- **Problem context:** the Tech4Bharat 2026 challenge brief describes manual inspection misses, costly specialist machine vision, and the resulting quality-evidence gap for small units. The brief's 10–15% estimate is attributed to the organizers, not to our measurements.
- **Research signal:** literature on manufacturing SMEs points to cost, skills, product variety, and limited labelled data as adoption barriers.
- **Dataset finding:** no reviewed public dataset fully represents phone-captured, populated PCB assembly inspection under a small unit's working conditions.
- **Experiment finding:** both tested VisA PCB1 baselines failed the experiment's provisional detection screen. The result is a warning about that configuration and data setup, not a verdict on every inspection method.
- **Current boundary:** begin with a single board model/revision; human review remains responsible for decisions; uncertain or poor-quality images require recheck or assisted review.

## Navigate the archive

| Topic | Start here |
|---|---|
| Research synthesis and project boundaries | [Research overview](research/overview.md) |
| Challenge problem and evidence attribution | [Problem statement](research/problem-statement.md) |
| Papers and recent context | [Literature and context](research/literature-and-context.md) |
| PCB datasets and limitations | [Dataset notes](research/dataset-notes.md), [component shortlist](COMPONENT_DATASETS.md), [full catalogue](DATASET_CATALOGUE.md) |
| Previous PCB1 experiment | [Experiment report](experiment/artifacts/EXPERIMENT_REPORT.md), [protocol](experiment/PROTOCOL.md), [experiment README](experiment/README.md) |
| Questions still to validate | [Open questions](research/open-questions.md) |
| Sources and licensing boundaries | [Source register](research/sources.md), [licence note](LICENSE-STATUS.md) |

## Scope and contents

This repository contains research notes, dataset assessments, literature references, and selected experiment evidence. It intentionally excludes application scaffolding, model bundles, installed dependencies, virtual environments, and dataset files. Dataset links point to their original providers; verify current access and terms before use.

The experiment folder preserves the available report, protocol, result records, failure examples, and focused checks. It is not a complete standalone reproduction package: some source files listed by historical checksums are not present in this archive, and the benchmark data is not included.

## How to cite

For the challenge estimate, cite the Tech4Bharat 2026 challenge brief. For claims about this project's test results, cite the experiment report and protocol in this repository. Do not cite public benchmark results as factory or phone-camera performance.

