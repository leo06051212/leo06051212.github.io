---
title: Co-Designed Physics-Informed Neural Network FPGA Accelerator for Battery Health
  Estimation
authors:
- Jianglan Zhu
- Yulin Fu
- Jiale Li
- me
- Chiu-Wing Sham
date: '2026-10-21T00:00:00Z'
publication_types:
- article-journal
publication:
  name: IEEE Consumer Electronics Magazine
  pages: 1-8
  publisher: IEEE
abstract: Physics-informed neural networks (PINNs) provide strong generalization for
  battery state-of-health (SOH) estimation, but their sine activations make aggressive
  low-bit quantization and efficient edge deployment difficult. This paper presents
  a co-designed quantization and FPGA acceleration framework for PINN-based SOH estimation.
  We introduce per-channel GridWarp quantization-aware training, which learns neuron-wise
  scale and bias parameters to align the quantization grid with the non-uniform activation
  distribution. The learned transforms are compiled into per-channel activation LUTs
  that fuse sine evaluation, GridWarp, and requantization in hardware, while the fully
  connected layers are mapped to an output-neuron-parallel datapath with DSP packing
  and deferred offset correction. Across 11 evaluation settings, including six XJTU
  batches with different charge/discharge protocols, three TJU chemistry batches,
  and the MIT and HUST datasets, per-channel GridWarp reduces average W4A4 MAPE to
  1.93%, compared with 5.51% for post-training quantization, 3.45% for QAT, and 2.41%
  for per-layer GridWarp. Implemented on a ZYNQ-7020 FPGA, the accelerator delivers
  0.69 μs latency at 0.182W, with 37× and 80× lower latency than a desktop CPU and
  GPU, respectively.
featured: false
draft: false
requires_correction: false
correction_reasons: []
date_precision: day
publication_date_parts:
- 2026
- 10
- 21
publication_importer:
  managed_citation: true
hugoblox:
  ids:
    doi: 10.1109/mce.2026.3745192
links:
- type: source
  url: https://doi.org/10.1109/mce.2026.3745192
metadata_review:
  verified_on: '2026-10-30'
  publication_date_source: https://ieeexplore.ieee.org/abstract/document/11744623
  crossref_source: https://api.crossref.org/works/10.1109/mce.2026.3745192
---

Published online as an IEEE Early Access article.
