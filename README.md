![LLMs Banner](g_c_llms.jpeg)

# LLM Model Collection

This repository contains implementations of Large Language Models (LLMs) developed throughout my studies.

The goal is to explore how simple computational structures can scale into systems capable of language, reasoning, and abstraction. Some models are still being organized and will be added over time.

Each model is accompanied by a Jupyter Notebook containing both implementation details and explanations, making it easier to understand the underlying concepts.

You can also test some of these models directly on my Hugging Face profile, where interactive demos make experimentation and validation much more accessible.

---

## First Model

### Perceptron

The perceptron is the foundational building block of neural networks, originally proposed decades ago.

It was my first deep dive into machine learning, where I spent time understanding its mechanics and limitations. The full implementation is available in:

`perceptron (1).ipynb`

#### Capabilities

- Solves linear operations (e.g., weighted sums)
- Handles basic logical gates:
  - AND
  - OR

#### Limitations

- Cannot solve non-linearly separable problems such as XOR

---

### Model Representation

```

```
    w1*x1
     \
      Σ  →  f(x)  →  output
     /
    w2*x2
```

```
---
# The second model - Embedding

> What is an Embedding?

An embedding is a way to represent discrete items, like words or sentences, as vectors of numbers.
These vectors capture semantic meaning: similar words or sentences have vectors that are close together
in the embedding space.

Embeddings are used in machine learning to allow models to process text, images, or other categorical
data in a numerical form. For text, embeddings are usually learned from data and help the model
understand relationships between words.

Example: a very small embedding table for 4 words with 3-dimensional vectors:

```md
+--------+-------------------+
| Word   | Embedding (3D)    |
+--------+-------------------+
| i      | [0.1, 0.5, -0.2] |
| love   | [0.7, 0.3, 0.0]  |
| python | [0.4, -0.1, 0.6] |
| code   | [0.5, 0.2, 0.1]  |
+--------+-------------------+
``` 

Each row maps a word to a vector. These vectors can be used as inputs to a model or to
compute similarity between words.

---

## Connect

[![Hugging Face](https://img.shields.io/badge/HuggingFace-1f1f1f?style=for-the-badge&logo=huggingface&logoColor=FFD21E)](https://huggingface.co/marcos-j-ferreira)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcos-junior-lemes/)
[![Twitter](https://img.shields.io/badge/Twitter-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/marcosLLMs_)
[![Wiki Marcos](https://img.shields.io/badge/Wiki-Marcos-1f1f1f?style=for-the-badge)](https://marcoswiki.vercel.app/)

---

## Research Papers

[![Papers Repository](https://img.shields.io/badge/Research%20Papers-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marcos-j-ferreira/papers/tree/master)
