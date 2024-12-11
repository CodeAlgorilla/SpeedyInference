# Dynamic Early Exit and Layer Skipping

## Project Overview
This repository implements **Dynamic Early Exit** and **Dynamic Layer Skipping**, techniques designed to accelerate inference for **Large Language Models (LLMs)** like Llama2. These strategies enhance efficiency in real-time applications such as conversational AI, live translation, and code generation.

Building upon prior works like **LayerSkip**, we present a unified framework for dynamic inference optimization, achieving significant speedups while maintaining high-quality outputs across diverse tasks.

---

## Key Features

- **Dynamic Early Exit**:
  - Implements token-level confidence thresholds to dynamically exit inference early, optimizing resource usage for simpler inputs.
  
- **Dynamic Layer Skipping**:
  - Skips non-critical layers during inference, determined by input complexity and optimized through **Bayesian Optimization**.

- **Self-Speculative Decoding**:
  - Combines draft and verify mechanisms to accelerate decoding with minimal accuracy loss.

- **Interpretability Tools**:
  - Includes layer-wise token prediction visualizations and cosine similarity analysis for model behavior insights.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Garyli2333/layer_skip.git
   cd layer_skip
