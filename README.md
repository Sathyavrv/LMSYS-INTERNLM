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
   ```
## Install Dependencies

Ensure you have Python 3.10+ and the necessary packages installed. You can install the required libraries using pip:

```bash
pip install -r requirements.txt
```

## How to Use

- **Training-InternLM.ipynb:** This notebook guides you through the process of fine-tuning the InternLM2 model using LoRA on an GPU. It includes steps for data preprocessing, model configuration, and training, culminating in a fine-tuned model ready for deployment.

- **efficient-fine-tuning-of-llama-for-sequence-classi.ipynb:** This notebook provides a comprehensive approach to fine-tuning the LLaMA model for sequence classification, utilizing advanced techniques like TPU/GPU acceleration and LoRA for efficient performance.

Both notebooks are designed to be easily customizable for your specific tasks and datasets.

## Requirements

- Python 3.10+
- Hugging Face Transformers
- PyTorch
- GPU / TPU

Refer to the installation instructions within each notebook for detailed dependencies.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or new features to add, please feel free to fork the repository, create a branch, and submit a pull request. Issues and bug reports are also appreciated.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
