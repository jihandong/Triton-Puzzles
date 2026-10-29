# Triton Puzzles

w/ [Tejas Ramesh](https://tejas3070.github.io/) and [Keren Zhou](https://www.jokeren.tech/) based on [Triton-Viz](https://github.com/Deep-Learning-Profiling-Tools/triton-viz)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jihandong/Triton-Puzzles/blob/main/Triton-Puzzles.ipynb)

## Start in Colab

1. Sign in to Colab with the Google account you want to use (for example, `hj2868`), then open the notebook with the badge above.
2. Select **Runtime > Change runtime type > T4 GPU** (or another available GPU), then connect to the hosted runtime. The first puzzles also work with a CPU runtime through the Triton interpreter.
3. Run the installation cell and the setup cells from the top of the notebook before solving Puzzle 1. The installation cell installs `triton-viz` and `jaxtyping` in the Colab runtime; no local GPU or local Python installation is needed.
4. To keep your answers, save an editable copy to Google Drive, or save the notebook back to your GitHub repository. A notebook opened directly from GitHub does not automatically commit changes to GitHub.

The `main` branch starts from the upstream unsolved puzzles. Earlier answers are preserved on the [`deprecated` branch](https://github.com/jihandong/Triton-Puzzles/tree/deprecated).


Programming for accelerators such as GPUs is critical for modern AI systems.
This often means programming directly in proprietary low-level languages such as CUDA. [Triton](https://github.com/openai/triton/) is an alternative open-source language that allows you to code at a higher-level and compile to accelerators like GPU.

Coding for Triton is very similar to Numpy and PyTorch in both syntax and semantics. However, as a lower-level language, there are a lot of details that you need to keep track of. In particular, one area that learners have trouble with is memory loading and storage which is critical for speed on low-level devices.

This set of puzzles is meant to teach you how to use Triton from first principles in an interactive fashion. You will start with trivial examples and build your way up to real algorithms like Flash Attention and Quantized neural networks. These puzzles **do not** need to run on GPU since they use a Triton interpreter.

Discord: https://discord.gg/gpumode #triton-puzzles

<img width="2397" height="1195" alt="image" src="https://github.com/user-attachments/assets/a7e0219b-9df7-4640-a73e-35c1fa50b0f2" />



If you are into this kind of thing, this is 7th in a series of these puzzles.

* https://github.com/srush/gpu-puzzles
* https://github.com/srush/tensor-puzzles
* https://github.com/srush/autodiff-puzzles
* https://github.com/srush/transformer-puzzles
* https://github.com/srush/GPTworld
* https://github.com/srush/LLM-Training-Puzzles
