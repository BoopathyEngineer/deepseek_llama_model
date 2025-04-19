# 🦙 Llama Chatbot using DeepSeek-R1-Distill-Llama-8B

This project demonstrates a lightweight, terminal-based chatbot powered by the `deepseek-ai/DeepSeek-R1-Distill-Llama-8B` model using HuggingFace's `transformers` library. It leverages 4-bit quantization using `bitsandbytes` to run efficiently even on limited GPU memory, making it suitable for developers who want to build or test large language models locally.

## 🚀 Project Overview

The chatbot simulates human-like conversation through terminal input/output and is capable of handling long-form responses with style-enhanced printing (thinking vs. answering phases).

It uses:
- **Quantized LLM model** for performance on consumer hardware
- **`pipeline` API** from HuggingFace for simplicity
- **GPU acceleration** (if available)
- **Terminal styling** using the `sty` package

---

## 🔧 Features

- ✅ Uses the **DeepSeek-R1-Distill-Llama-8B** model (compact, distilled LLaMA variant)
- ✅ Efficient **4-bit NF4 quantization** using `BitsAndBytesConfig`
- ✅ Automatically detects GPU (CUDA) availability
- ✅ Simulates "thinking" and answering using terminal colors
- ✅ Built with modular Python code for easy extension

---


