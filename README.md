# GPTmodel
# TinyGPT2 - A Clean GPT-2 from Scratch (PyTorch)

TinyGPT2 is a lightweight and educational implementation of GPT-2 built entirely from scratch using PyTorch. It replicates the core architecture of GPT-2 and is trained on the [TinyStories](https://huggingface.co/datasets/roneneldan/TinyStories) dataset for simplicity and efficiency. This project is ideal for learning how transformers and language models work under the hood.

## Features

- Clean and readable codebase
- GPT-2 style transformer architecture
- Trains on the TinyStories dataset using HuggingFace `datasets`
- Supports checkpointing and resuming training
- Includes an interactive text generation interface
- Custom implementation of:
  - Multi-Head Self-Attention
  - Positional Encoding
  - Feed-Forward Networks
  - Transformer Blocks

## Model Architecture

- **Layers:** 4 Transformer blocks
- **Heads:** 4 attention heads
- **Embedding size:** 256
- **Block size:** 128 tokens
- **Parameters:** ~12M tokens max, suitable for small-scale experimentation

## Installation

```bash
git clone https://github.com/yourusername/tinygpt2.git
cd tinygpt2
pip install -r requirements.txt
