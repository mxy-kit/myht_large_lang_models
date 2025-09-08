# NLP & LLM Projects

This repository contains several of my experiments and implementations in **Natural Language Processing (NLP)** and **Large Language Models (LLMs)**.  

---

## 📂 Contents

### 1. Tokenizer & Small LM
Implementation of a Byte-level BPE tokenizer trained on Russian text corpus, followed by training a small language model using the tokenizer.  
File: `tokenizer_bpe_lm_with_outputs.ipynb`

---

### 2. Retrieval-Augmented Generation (RAG)
Built a QA system on top of a RAG pipeline. Collected data from [help.mail.ru](https://help.mail.ru/), preprocessed it, created embeddings with a HuggingFace model, and performed retrieval + generation.  
File: `rag_mailru_qa_with_outputs.ipynb`

---

### 3. Parameter-Efficient Fine-Tuning (PEFT / LoRA)
Fine-tuned a lightweight LLM (`Lite-Oute-1-300M-Instruct`) using LoRA/PEFT on the **tweet_eval** dataset for sentiment classification (negative / neutral / positive).  
File: `peft_lora_sentiment_with_outputs.ipynb`

---

### 4. Alignment Methods (DPO & PPO)
Implemented **Direct Preference Optimization (DPO)** from scratch and trained **Proximal Policy Optimization (PPO)** using the TRL library, comparing alignment methods for LLMs.  
File: `alignment_dpo_ppo_with_outputs.ipynb`

---

## 🛠 Tech Stack
- **Frameworks**: PyTorch, HuggingFace Transformers, LangChain, TRL, BitsAndBytes  
- **Tasks**: Tokenization, Retrieval-Augmented QA, PEFT/LoRA Fine-tuning, RLHF (DPO & PPO)  

---

## 📌 Note
This repository is intended to demonstrate my hands-on experience with modern NLP/LLM techniques.  
