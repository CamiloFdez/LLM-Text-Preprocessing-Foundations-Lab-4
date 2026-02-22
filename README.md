# LLM-Text-Preprocessing-Foundations-Lab-4

This repository follows Chapter 2 of *Build a Large Language Model (From Scratch)* by Sebastian Raschka.

---

## Contents
- `embeddings.ipynb`: Step-by-step implementation and explanation of tokenization, context windows, and overlapping datasets for LLM training.
- `the-verdict.txt`: Source text used for tokenization and dataset creation.
- `ch02.ipynb`: Summary of key concepts and takeaways from the chapter.

---

## Key Concepts
- Tokenization with GPT-2 BPE
- Context windows (`max_length`)
- Overlapping samples (`stride`)
- Why embeddings encode semantic meaning

---

## Project Structure
```
LLM-Text-Preprocessing-Foundations-Lab-4/
├── embeddings.ipynb
├── the-verdict.txt
├── ch02.ipynb
└── README.md
``` 

---

## How to Run
```bash
pip install torch tiktoken
jupyter notebook
```

Open embeddings.ipynb and run all cells.

---

## Experiment
The notebook includes a small experiment showing how changing max_length and stride affects the number of training samples and why overlap is useful.

This experiment demonstrates:

- The trade-off between context size and dataset size
- Why overlapping windows are useful when preparing training data for Large Language Models

---

## References
- [Build a Large Language Model (From Scratch) by Sebastian Raschka](https://sebastianraschka.com/blog/2024/llm-from-scratch.html)
- [GPT-2 Tokenizer Documentation](https://huggingface.co/docs/transformers/main_classes/tokenizer#transformers.PreTrainedTokenizer)

---

## Image
Here's a visual representation of the notebook structure and key concepts:
![image]

---

## Conclusion
This lab provides a practical introduction to the foundational concepts of text preprocessing for Large Language Models. By understanding tokenization, context windows, and overlapping datasets, you can better prepare your data for training and fine-tuning LLMs effectively.