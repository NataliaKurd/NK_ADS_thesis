# Thesis Repository

This repository contains the code associated with my thesis on evaluating a transformer-based model for information extraction tasks, specifically focusing on Named Entity Recognition (NER) and Relation Extraction (RE).

## Repository Structure

1. **data_exploration.ipynb**: Jupyter Notebook containing the exploration of the news article data.
2. **data_preparation.ipynb**: Preparation of the data for labeling in Label Studio and train & test split function.
3. **ner_LUKE_spaCy.ipynb**: Comparison of the LUKE [1] and spaCy models for the NER task (including fine-tuning of the models).
4. **re_LUKE_REBEL.ipynb**: Fine-tuning and comparison of LUKE and REBEL [2] models for RE.
5. **LUKE_pipeline.ipynb**: LUKE pipeline for relation extraction.

## References

[1] I. Yamada, A. Asai, H. Shindo, H. Takeda, and Y. Matsumoto, “Luke: Deep con- textualized entity representations with entity-aware self-attention,” arXiv preprint arXiv:2010.01057, 2020.  
[2] P.-L. H. Cabot and R. Navigli, “Rebel: Relation extraction by end-to-end language generation,” in Findings of the Association for Computational Linguistics: EMNLP 2021, 2021, pp. 2370–2381.
