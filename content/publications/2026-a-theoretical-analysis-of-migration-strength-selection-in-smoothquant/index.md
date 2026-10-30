---
title: A Theoretical Analysis of Migration Strength Selection in SmoothQuant
authors:
- Zhihang Liu
- Chiu-Wing Sham
- Jiale Li
- me
- Chong Fu
date: '2026-06-22T00:00:00Z'
publication_types:
- paper-conference
publication:
  name: 2026 International Joint Conference on Neural Networks (IJCNN)
  pages: 1-8
  publisher: IEEE
abstract: Post-training quantization (PTQ) is essential for efficient inference of
  large language models, yet remains challenging due to activation outliers with large
  magnitudes. SmoothQuant mitigates this issue by migrating quantization difficulty
  from activations to weights using a global migration strength α. However, the choice
  of α in prior work is empirically motivated and lacks theoretical grounding, while
  a global α ignores layer heterogeneity. In this paper, we provide a theoretical
  analysis of SmoothQuant by formulating it as a quantization-noise balancing problem.
  Under standard quantization noise assumptions, we derive an explicit objective that
  characterizes the trade-off between activation and weight quantization errors, revealing
  that the error-minimizing migration strength depends on layer-specific activation
  and weight statistics. Motivated by this analysis, we propose a layer-wise smoothing
  strategy in which each layer adopts its own theory-guided α. With minimal modifications
  to the original method and no additional runtime overhead, the proposed approach
  consistently reduces layer output error and improves accuracy on LLaMA models under
  W8A8 quantization, demonstrating the practical effectiveness of the theoretical
  insights. Our implementation is publicly available.
featured: false
draft: false
requires_correction: false
correction_reasons: []
date_precision: day
publication_date_parts:
- 2026
- 6
- 22
publication_importer:
  managed_citation: true
hugoblox:
  ids:
    doi: 10.1109/ijcnn69854.2026.11728525
links:
- type: source
  url: https://doi.org/10.1109/ijcnn69854.2026.11728525
metadata_review:
  verified_on: '2026-10-30'
  publication_date_source: https://ieeexplore.ieee.org/abstract/document/11728525
  crossref_source: https://api.crossref.org/works/10.1109/ijcnn69854.2026.11728525
---
