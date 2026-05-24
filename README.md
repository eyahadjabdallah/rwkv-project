# 🧠 RWKV Deep Learning Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eyahadjabdallah/rwkv-project/blob/main/RWKV_Demo_Fixed.ipynb)

## Description
Mini RWKV (Receptance Weighted Key Value) implementation
from scratch in PyTorch.
Character-level text generation on Shakespeare dataset.

## Files
- `RWKV_Demo_Fixed.ipynb` — Main Colab notebook (run this!)

## How to Run
1. Click the **Open in Colab** badge above
2. Runtime → Change runtime type → **T4 GPU**
3. Runtime → **Run All**
4. Done in ~5 minutes!

## Architecture
- Time Mixing → replaces Self-Attention — O(n)
- Channel Mixing → replaces FFN
- Linear complexity O(n) vs Transformer O(n²)

## Results
- Parameters : ~50,000
- Task : Character-level text generation
- Dataset : Mini Shakespeare (built-in)
