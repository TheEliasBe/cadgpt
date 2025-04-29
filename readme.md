# Supplementary Code for Submission

# Flexible Sequence-to-Sequence Modeling for CAD Construction Tasks  
**ECAI 2025**  
*Anonymous Authors*

---

# Repository Overview

This repository provides the supplementary code used for our ECAI 2025 submission on flexible sequence-to-sequence modeling for CAD construction tasks.

- **`data_loader/`** — PyTorch data loaders for CAD construction datasets.
- **`models/`** — Model definitions and training code. The `cadgpt` folder includes our **novel sequence decoder**, while standard seq2seq models are also provided.
- **`pycad/` and `pycadseq/`** — Python libraries for CAD construction sequences:
  - `pycad` is based on Khan et al. (2024),
  - `pycadseq` is our **new, extended implementation**.
- **`scripts/`** — Utility scripts for data conversion, visualization, and miscellaneous tasks.

---

# Model Training

The main training script is located at `modules/train.py`.  
Training hyperparameters can be configured in `modules/config.py`.

To start training:

```bash
python modules/train.py
