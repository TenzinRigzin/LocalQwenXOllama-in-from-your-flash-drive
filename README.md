# Portable Local LLM

> A portable, offline Large Language Model setup that can be run directly from a USB drive without installing the complete environment on every computer.

## 🚀 Overview

This project documents my journey of building a portable Local LLM environment using a USB drive.

The main goal was simple:

**Carry my AI environment with me and run it on a compatible Windows computer whenever I need it.**

Instead of depending completely on cloud-based AI services, I wanted to experiment with running an LLM locally.

The setup uses:

- llama.cpp
- GGUF model format
- Qwen3 4B Thinking model
- Windows
- USB storage
- Local HTTP server

The model and required runtime files are stored on the USB drive, allowing the setup to be moved between compatible systems.

---

## 🎯 Project Goals

The main goals of this project were:

- Run an LLM locally
- Keep the model on a USB drive
- Avoid downloading the model repeatedly
- Use the LLM without an internet connection
- Learn how local LLM inference works
- Understand GGUF models and llama.cpp
- Experiment with running AI on consumer hardware
- Measure how my laptop handles local inference

---

## 🧠 Model

### Model

**Qwen3 4B Thinking**

Model file:

```text
qwen3-4b-thinking-2507.Q4_K_M.gguf
