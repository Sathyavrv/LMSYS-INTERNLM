# LMSYS-INTERNLM

Welcome to the **LMSYS-INTERNLM** repository! This project focuses on advanced fine-tuning techniques for large language models, particularly InternLM2 and LLaMA, using state-of-the-art methods like Low-Rank Adaptation (LoRA) and GPU acceleration.

## Repository Overview

This repository includes two main Jupyter notebooks:

1. **Training-InternLM.ipynb**
   - **Purpose:** Fine-tuning the InternLM2 model for sequence classification.
   - **Hardware:** A100 GPU (40GB).
   - **Techniques:** Low-Rank Adaptation (LoRA), mixed precision training, efficient model saving.
   - **Outcome:** A fine-tuned InternLM2 model, with LoRA layers merged for efficient deployment.

2. **efficient-fine-tuning-of-llama-for-sequence-classi.ipynb**
   - **Purpose:** Efficient fine-tuning of the LLaMA model for sequence classification tasks.
   - **Hardware:** TPU/GPU.
   - **Techniques:** Low-Rank Adaptation (LoRA), TPU/GPU acceleration, mixed precision training.
   - **Outcome:** An optimized LLaMA model, ready for high-performance applications.

## Installation

To get started with this repository, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sathyavrv/LMSYS-INTERNLM.git
   cd LMSYS-INTERNLM
