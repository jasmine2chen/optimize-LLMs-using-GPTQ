# Optimize LLM using Hugging Face AutoGPTQ

### Project Overview
This project demonstrates how to optimize LLMs with GPTQ, which is a post-training quantziation method to compress LLMs.

### Key highlights

- GPTQ compresses GPT models by reducing the number of bits needed to store each weight in the model, from 32 bits down to just 3-4 bits, so that the model takes up much less memory, so it can run on less Hardware, e.g. Single GPU for 13B Llama2 models.
- GPTQ analyzes each layer of the model separately and approximating the weights in a way that preserves the overall accuracy

### Workflow
- Setup our development environment
- Prepare quantization dataset
- Load and Quantize Model
- Test performance and inference speed
- Run Inference with Text Generation Inference

### Model Used
philschmid/llama-2-7b-instruction-generator
