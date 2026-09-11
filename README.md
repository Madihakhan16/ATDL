\# ATDL Assignment 1: KD + Ternary QAT (ResNet34 → ResNet18)



\## Overview

Knowledge distillation from a full-precision ResNet34 teacher to a ternary-weight

ResNet18 student, trained with Quantization-Aware Training on CIFAR-10.



\## Setup

pip install -r requirements.txt





\## Project Structure

\- `models/resnet.py` — ResNet34 teacher, FP32 ResNet18 baseline

\- `models/ternary\_resnet.py` — Ternary quantizer + ternary ResNet18 student

\- `train\_teacher.py` — trains ResNet34 teacher

\- `train\_baseline.py` — trains FP32 ResNet18 without KD

\- `train\_student\_kd\_qat.py` — trains ternary ResNet18 via KD+QAT

\- `evaluate.py` — evaluates and compares all three models

\- `verify\_ternary.py` — verifies saved student weights are ternary



\## How to Run

(to be filled in as scripts are completed)



\## Reproducibility

\- Random seed: TBD

\- Environment: see requirements.txt



\## Results

(to be filled in after training)





