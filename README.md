# Fine-Tuning LLama LLM with LoRA: a Practical Guide

In this repo you will find the notebooks used in [this post](https://clearintelligence.substack.com/p/fine-tuning-llama-llm-with-lora-a).

![Fine-tuning LLaMA with LoRA](images/llama-fine-tune.png)

## Setup

Libraries needed for each notebook are installed inside each of them in a cell. These notebooks were tested with specific libraries. A requirements file is included for ease of use.

```
bitsandbytes==0.45.4
transformers==4.50.3
peft==0.15.1
accelerate==1.6.0
datasets==3.5.0
trl==0.16.0
evaluate==0.4.3
rouge_score==0.1.2
bert-score==0.3.13
```