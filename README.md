1. Project Overview
This project implements a Transformer-based autoregressive language model from scratch using PyTorch.

  The model includes:
- token embedding
- positional encoding
- masked multi-head self-attention
- residual connections & layer normalization
- next-token prediction training
- autoregressive text generation with EOS termination

2. Architecture Diagram
Tokens -> Embedding + Positional Encoding -> Masked Decoder Block -> Linear(LM Head) -> Softmax
  
3. Training Objective
The model is trained with a next-token prediction objective using cross-entropy loss.

4. Example Output
Input: i
Output: i went to the hospital <EOS>

5. What I learned
- How slef-attention works at the tensor level
- Why causal masking is required for language models
- How training and inference differ in LLMs
- How EOS tokens enable proper sequence termination
