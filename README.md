# Seq2Seq Model for Machine Translation

## Overview
This repository contains the implementation of various sequence-to-sequence (Seq2Seq) models designed for the task of machine translation. Each model utilizes different architectural features and techniques to optimize translation accuracy and efficiency.
We have explored and implemented these models:
- GRU Encoder-Decoder
- LSTM Encoder-Decoder
- BiLSTM Encoder-GRU Decoder
- GRU Encoder-Decoder with Attention Mechanism
- Transformer Encoder-GRU Decoder

## Key Findings:
- **GRU Encoder-Decoder with Attention Mechanism** showed the highest performance in ROUGE-1 scores, indicating its effectiveness in capturing correct individual words in translation outputs.
- **Transformer Encoder - GRU Decoder** excelled in ROUGE-2 scores, highlighting its capability to maintain sentence structure and coherence, which is crucial for producing contextually relevant translations.

The detailed analysis and comparison of these models are included in the PDF Report: [Result Analysis Report](Report.pdf).
