# Literature and recent context

These sources support the problem framing and technical limits. They do not validate this project's proposed product or prove demand at a specific PCB unit.

## Manufacturing SMEs and quality inspection

### Werheid et al. (2025) — machine vision in manufacturing SMEs

[Machine vision in manufacturing SMEs: a review](https://doi.org/10.1007/s42452-025-06923-4), *Discover Applied Sciences*, published 19 April 2025. The systematic review analyzes 770 articles and identifies cost/investment limits, skills and labour shortages, high-variety/low-volume work, and insufficient labelled data as recurring challenges. It also surveys low-cost hardware, open-source software, and intuitive tools as approaches explored in prior work.

**Use in the pitch:** supports why an SME-focused solution should be affordable, simple to operate, and designed around limited data. The review is broad across manufacturing, not PCB-specific field evidence from India.

### World Economic Forum and Office of the Principal Scientific Adviser to the Government of India (2025)

[Transforming Small Businesses: An AI Playbook for India's SMEs](https://psa.gov.in/CMS/web/sites/default/files/publication/WEF_Transforming_Small_Businesses_2025.pdf), 2025. Its SME quality-management section describes manual checks as prone to error and inconsistency and discusses quality management as a competitiveness issue.

**Use in the pitch:** India-focused context for SME quality management. It is a policy/AI playbook and illustrative use-case source, not a controlled evaluation of this PCB workflow.

## PCB inspection and dataset limits

### Domingues et al. (2023) — PCB inspection survey

[Automatic printed circuit board inspection: a comprehensible survey](https://link.springer.com/article/10.1007/s44163-023-00081-5), *Discover Artificial Intelligence*, 2023. The survey distinguishes bare PCB (BPCB) inspection from populated PCB assembly (PCBA) inspection, reviews public datasets, and notes limited representative datasets and difficulty comparing results across private datasets and different setups.

**Use in the pitch:** supports keeping bare-board and assembly defects distinct and measuring a board-specific workflow.

### Ling and Isa (2023) — methods survey

[Printed Circuit Board Defect Detection Methods Based on Image Processing, Machine Learning and Deep Learning: A Survey](https://doi.org/10.1109/ACCESS.2023.3246008), *IEEE Access*, 2023. Broad survey of visual PCB defect-detection methods. Treat findings as method context; the capture conditions and dataset determine how much applies to the proposed phone workflow.

## New dataset research leads

### PCB-SAID (ICCV Workshops 2025)

[PCB-SAID: A Low-Cost Camera-Based Dataset for Few-Shot SMD Assembly Inspection](https://doi.org/10.1109/ICCVW69036.2025.00145), 2025. The paper reports 175 RGB images and labels including missing, misaligned, lifted, rotated, and short-circuit cases. It describes public availability upon request; verify access, exact labels, and current terms before relying on it.

### PCB-MC (2026 preprint)

[PCB-MC: Missing Component Analysis in Printed Circuit Boards](https://arxiv.org/abs/2609.39427), arXiv preprint, 2026. Focuses on footprint-level missing-component annotations and board-aware evaluation. The authors report difficulties on unseen board designs and limitations for methods without board-specific alignment. It is a new preprint; verify release status, annotation quality, and licence.

## Presentation caveat

For the slide deck, use the challenge brief for its 10–15% estimate, the 2025 SME review for adoption barriers, and the PCB survey for the bare-board/assembly distinction. Label each as published research or organizer-provided context. Do not describe these sources as field research conducted by the team.

