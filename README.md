# ShakespeareGPT
A GPT-based model trained entirely on Shakespeare’s works, built from scratch.

This project implements a mini GPT-style Transformer from scratch in PyTorch, trained on the Tiny Shakespeare dataset.
It includes:

-> Multi-Head Self Attention

-> Transformer Blocks

-> Token & Positional Embeddings

-> Causal Masking

-> AdamW Optimization

-> GPU acceleration (CUDA 11.8)

-> Text generation (character-level)

This project follows the core ideas from GPT architecture (Attention, Residuals, LayerNorm, FFN) and trains a 10M-parameter model capable of generating Shakespeare-like text.

**Model Highlights**

-> 10.7 million parameters

-> 6 Transformer layers

-> 6 Attention heads

-> 384-dimensional embeddings

-> Training loss improves from 4.32 → 1.20

Generates coherent Shakespeare-style dialogue
