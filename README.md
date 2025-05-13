# GPT From Scratch

This repository contains a minimal implementation of a GPT (Generative Pretrained Transformer) model built entirely from scratch, based on the brilliant video series by [Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy). It walks through how large language models (LLMs) like GPT are trained at a fundamental level.

![image](https://github.com/user-attachments/assets/04c0757c-82c2-4af3-83cc-7c44bd6cd474)
Source: Andrej Karpathy's YouTube Banner (love it)


## Overview

- Tokenisation and vocabulary building
- Simple version of positional embeddings
- Transformer blocks with multi-head self-attention
- Training loop and loss computation
- Language generation via sampling

All of this is implemented in a **single Jupyter notebook**:  
`gpt-from-scratch.ipynb`

---

## Files

| File | Description |
|------|-------------|
| `gpt-from-scratch.ipynb` | End-to-end implementation of GPT, following Karpathy’s walkthrough. Contains detailed comments and step-by-step explanations. |

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/gpt-from-scratch.git
   cd gpt-from-scratch
