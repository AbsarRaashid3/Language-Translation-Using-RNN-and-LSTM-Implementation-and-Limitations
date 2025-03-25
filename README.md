# **English-to-Urdu Language Translation Using RNN and LSTM**

This repository implements a many-to-many RNN model for English-to-Urdu translation, explores the limitations of RNNs, and introduces an LSTM-based architecture to address these challenges. The project uses BLEU score and accuracy for evaluation, leveraging the `parallel-corpus.xlsx` dataset.

---

## **Project Overview**

The objective of this project is to:
1. Implement an RNN-based architecture for English-to-Urdu translation.
2. Identify and analyze the limitations of RNNs, such as handling long sequences and maintaining context.
3. Enhance the translation performance by replacing RNN layers with LSTM layers.
4. Compare and evaluate the performance of both models.

---

## **Features**

### Part 1: **Many-to-Many RNN Implementation**
- Preprocessing parallel English-Urdu text data.
- Building a many-to-many RNN-based model for sequence translation.
- Evaluation using BLEU score and accuracy.

### Part 2: **Exploring RNN Limitations**
- Analysis of exploding/vanishing gradients.
- Challenges with long-term dependencies and context in language translation.
- Examples demonstrating RNN failures in complex scenarios.

### Part 3: **LSTM-Based Enhancement**
- Implementing an LSTM-based architecture to overcome RNN limitations.
- Performance comparison between RNN and LSTM using BLEU score and accuracy.
- Discussion of LSTM advantages and remaining challenges.

---

## **Dataset**

The project uses the [parallel-corpus.xlsx] dataset containing parallel English and Urdu sentences for training, validation, and testing.

---

## Developed by 
**Absar Raashid**
