# This Folder Consists of the LLMs Finetuning Experiments and Customized Dataset Handling Including SOTA LLMOps

# Summary of the Models we are using
    - Flang20B (weights available)
    - Alpaca7B (weights not available)
    - Dolly (weights not available)
    - CelebrasGPT (weights available)

### 1. Play with [Flang20B](https://github.com/1zuu/experiments-on-large-language-models/blob/main/FineTuning-LLMs/1.%20Flang20B-with-UL2.ipynb) API Inference and The Model

    - Framework : PyTorch
    - API : HuggingFace
    - model : https://huggingface.co/google/flan-ul2

### 2. Play with [Alpaca7B](https://github.com/1zuu/experiments-on-large-language-models/blob/main/FineTuning-LLMs/2.%20Inspect-Alpaca-7B.ipynb) API Inference and The Model

    - Framework : PyTorch
    - API : HuggingFace
    - model : https://huggingface.co/decapoda-research/llama-7b-hf

### 3. FineTune [Alpaca7B](https://github.com/1zuu/experiments-on-large-language-models/blob/main/FineTuning-LLMs/2.%20Inspect-Alpaca-7B.ipynb) API Inference and The Model

    - Framework : PyTorch
    - API : HuggingFace
    - model : https://huggingface.co/decapoda-research/llama-7b-hf

### Notes : 
#### We Use Special Technique Called [PEFT](https://huggingface.co/blog/peft) a.k.a Parameter-Efficient Fine-Tuning of Billion-Scale Models on Low-Resource Hardware since these models are by definition very large and require a lot of memory to be fine-tuned. Local hardware is often not powerful enough to fine-tune these models, and cloud GPUs are expensive.

### 5. Play with [Dolly](https://github.com/1zuu/experiments-on-large-language-models/blob/main/FineTuning-LLMs/5.%20dolly_the_llama_from_pettah%F0%9F%98%81.ipynb) API Inference and The Model

    - Framework : PyTorch
    - API : HuggingFace
    - model : https://huggingface.co/EleutherAI/gpt-j-6B

### 6. FineTune [Cerebras GPT](https://github.com/1zuu/experiments-on-large-language-models/blob/main/FineTuning-LLMs/6.%20Cerebras-GPT%20family.ipynb) API Inference and The Model

    - Framework : PyTorch
    - API : HuggingFace
    - model : https://huggingface.co/cerebras/Cerebras-GPT-6.7B

### 7. FineTune [Dolly](https://github.com/1zuu/experiments-on-large-language-models/blob/main/FineTuning-LLMs/7.%20LoraFinetuning_Dolly_GPT_JGB.ipynb) API Inference and The Model

    - Framework : PyTorch
    - API : HuggingFace
    - model : https://huggingface.co/EleutherAI/gpt-j-6B
