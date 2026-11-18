---
license: apache-2.0
datasets:
- databricks/databricks-dolly-15k
language:
- en
base_model:
- openai-community/gpt2
pipeline_tag: question-answering
---

**Model Details:**
- Developed by: **Cyber Maphian**

- Model Type: Causal Language Model (Fine-tuned from OpenAI's GPT-2 base)

- Language(s): English

- License: apache-2.0

- Finetuned from Model: gpt2 (base model, 124M parameters)

- Dataset Used: Databricks Dolly Dataset (specifically cleaned subsets like databricks/databricks-dolly-15k)

**Model Description:**
This model is a fun, lightweight experimental project exploring the limits of fine-tuning a small, pre-trained base model ($\text{GPT-2}$, 124M parameters) on a structured instruction-response dataset (Databricks Dolly).Unlike the original GPT-2, which is designed purely for causal text continuation (autocomplete), this version has been trained using a prompt-response template to understand and respond to user instructions in a chat-like format.

**Intended Use & Limitations:**
- Educational & Experimental: Exploring how base models learn instruction-following behavior with limited compute.
- Prototyping: Testing lightweight chat pipelines locally on low-end hardware or CPU.
- Fun / Hobbyist Projects: A stepping stone toward understanding fine-tuning workflows, LoRA/QLoRA, or full parameter updates.
