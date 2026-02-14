# SigLIP with MAN and HNM

This project explores lightweight refinements to the SigLIP framework for cross-modal image-text retrieval.

Based on:  
SigLIP: Scaling up image-text pretraining with Sigmoid loss (Google Research, 2023)

## Contributions

We introduce and evaluate two modifications:

- **Modality-Aware Normalization (MAN)**  
  Mitigates modality mismatch and improves global alignment stability.

- **Hard Negative Mining (HNM)**  
  Emphasizes informative negative pairs within the sigmoid-loss framework to enhance fine-grained discrimination.

## Experimental Setup

- Base model: SigLIP (HuggingFace implementation)
- Training: Fine-tuning with modified loss functions
- Evaluation metrics: Recall@K, Mean Rank

## Repository Structure

- `SigLIP_Ablations_MAN_HNM.ipynb` – Full implementation and experiments

## Usage

Open the notebook and run all cells to reproduce experiments.

---

**Authors:** Ron Azran and Morgan Cohen  
**Course:** IEM DL  
**Year:** 2026
