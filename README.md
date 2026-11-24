# Learnlytica capstone projects

Jupyter notebooks for the GenAI and MLOps course. Run notebooks from top to bottom in a Python environment with the libraries and model weights described inside each notebook. GPU resources may be needed for practical image generation. Model downloads require internet access unless already cached; check model licenses and availability before running.

## Existing projects

- [Day 16 — Customer churn prediction](day16_capstone.ipynb): a tabular machine-learning workflow with feature engineering and model evaluation.
- [Day 20 — Image classification](day20_capstone.ipynb): a CNN and transfer-learning workflow using CIFAR-10.
- [Day 22 — Energy-demand forecasting](day22_capstone.ipynb): sequence modeling and attention for forecasting.

## Days 23–32

| Day | Course focus | Capstone status |
| --- | --- | --- |
| 23 | Generative models and GANs | No capstone mini-project listed; incremental project lab available. |
| 24 | NLP and word embeddings | No capstone mini-project listed; incremental project lab available. |
| 25 | Transformers and BERT | No capstone mini-project listed; incremental project lab available. |
| 26 | Large language models | [Customer-feedback intelligence pipeline](day26_capstone.ipynb): TF-IDF sentiment baseline, semantic search, summarization, topic labels and a text dashboard. |
| 27 | Diffusion and image generation | No capstone mini-project listed; incremental project lab available. |
| 28 | Image and video generation | No capstone mini-project listed; incremental project lab available. |
| 29 | Milestone assessment | Assessment only; no capstone mini-project listed. |
| 30 | Multimodal generative AI | No capstone mini-project listed. |
| 31 | Applied generative AI and ethics | [Creative studio](day31_capstone.ipynb): image generation and editing, captioning, CLIP search, provenance and a bias probe. |
| 32 | Retrieval-augmented generation foundations | No capstone mini-project listed; incremental project lab available. |

The Day 26 dataset is embedded in the notebook. The classical baseline was executed locally and scored 5/12 on its held-out split; this small sample is not a reliable production estimate. The embedding and language-model cells have not been executed locally because their dependencies and weights are unavailable. Day 31 has passed notebook-format and Python syntax checks, but its model cells and generated image artifacts have not been executed locally. Run both notebooks in the course environment and update the reflections with observed outputs before submission. The Day 31 course model identifiers may change or require access approval; consult the model providers if a download fails.
