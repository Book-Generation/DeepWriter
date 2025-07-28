# DeepWriter: A Multi-Agent Collaboration Framework for Information-rich Ultra-long Book Writing

DeepWriter is an advanced multi-agent collaboration framework designed to generate ultra-long, information-rich books across diverse topics. It addresses long-standing challenges in long-form text generation—such as coherence, structural planning, and content richness—by orchestrating multiple specialized agents in a planning-then-generation paradigm.


![DeepWriter Architecture](https://github.com/Book-Generation/DeepWriter/blob/main/assets/DeepWriter_architecture.png)

---

## 🔍 Overview

Traditional large language models (LLMs) struggle to generate lengthy and coherent narratives due to issues like contextual drift and repetitive content. **DeepWriter** overcomes these problems through:

- Hierarchical outline planning with expert-agent simulation
- Retrieval-augmented, citation-aligned drafting
- Automated rich information like trivia and image insertion for engagement
- Multilingual support (Chinese and English)

> 🏆 DeepWriter achieves **state-of-the-art BookScore** (up to 80.92/100), significantly outperforming strong baselines.

---

## 🧠 Key Features

### ✅ Multi-Agent Collaboration
- `OutlineBot`: Generates and refines outlines through simulated expert panels
- `WriteBot`: Drafts chapters with literature-grounded content and citations
- `TriviaBot`: Adds contextual trivia to improve reader engagement
- `ImageBot`: Retrieves and inserts semantically aligned visuals

### 📚 End-to-End Book Generation
- Supports book-length outputs over **100,000 words**
- Automatically includes references, images, trivia, and structured outlines
- Built-in citation alignment and factuality checks

### 📏 Evaluation Benchmark
- Introduces **DeepWriter-Bench**, a bilingual dataset of 18 full-length annotated books
- Proposes **BookScore**, a unified 100-point metric evaluating:
  - Outline structure
  - Content coherence
  - Trivia quality
  - Visual alignment
  - Verifiability
---

## 🚀 Getting Started

> 📌 Note: Code and benchmark data will be progressively released in phases after peer review and paper acceptance.

### Installation

```bash
git clone https://github.com/Book-Generation/DeepWriter.git

```
