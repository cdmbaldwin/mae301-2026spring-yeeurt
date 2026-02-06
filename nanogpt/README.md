# nanoGPT Implementation - Team YEEURT

## Overview
This directory contains the implementation of a GPT-style language model, following Andrej Karpathy's "build GPT from scratch" materials. It includes code for model architecture, training, and evaluation.

## Contents
*   `train.py`: Script for training the nanoGPT model.
*   `model.py`: Defines the nanoGPT model architecture.
*   `config/`: Directory for configuration files (e.g., YAML, JSON, or Python dicts).
*   `data/`: Placeholder for datasets or instructions to download them.
*   `logs/`: Directory for training logs and plots.
*   `requirements.txt`: List of Python dependencies.

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your_org/mae301-2026spring-yeeurt.git
    cd mae301-2026spring-yeeurt/nanogpt
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    .\venv\Scripts\activate  # On Windows
    source venv/bin/activate # On macOS/Linux
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## How to Run a Small Training Job

1.  **Prepare your dataset:**
    Place your dataset files in the `data/` directory or follow specific instructions if external data is used.

2.  **Configure training parameters:**
    Modify the configuration files in `config/` or directly within `train.py` (if using simple Python dicts) to set parameters like dataset path, batch size, learning rate, and model architecture.

3.  **Execute the training script:**
    ```bash
    python train.py --config-name=your_config.yaml # Example if using YAML configs
    ```
    (Adjust command based on your actual training script and config handling.)

## Expected Runtime
[Provide an estimate of how long a small training job might take on CPU vs. GPU, e.g., "A small training job on Tiny Shakespeare dataset takes approximately X minutes on a modern CPU and Y minutes on a standard GPU."]

## GitHub Release
A release will be tagged (e.g., `v0.1-nanogpt`) to mark this milestone.
