# Fair Prompt Framework for Implicit Hate Detection

This repository contains the implementation and experimental code for fair prompt framework in implicit hate speech detection systems.

## Repository Structure

```
├── implicit-hate-detection-framework.ipynb  # Main implementation
├── Token-efficiency-study.ipynb             # Token efficiency analysis
├── baselines/                               # Baseline model experiments
│   ├── www-implicit-bert-aav.ipynb
│   ├── www-implicit-bert-bt.ipynb
│   ├── www-implicit-deberta-bt.ipynb
│   ├── www-implicit-hatebert-aav.ipynb
│   ├── www-implicit-hatebert-bt.ipynb
│   ├── www-implicit-toxigen-hatebert.ipynb
│   └── www-implicit-toxigen-reberta.ipynb
└── ablation/                                # Ablation studies
    ├── wo-enr-implicit-hate-d-m-ablation.ipynb
    └── wo-gbi-implicit-hate-d-m-ablation.ipynb
```


## Datasets
- Latent Hatred Dataset
- ToxiGen Dataset  
- Offensive Language Dataset

## Models Evaluated
- BERT variants (AAV, BT)
- HateBERT variants
- DeBERTa
- GPT-3.5-turbo
- Llama-3.1-8B-Instruct

## Installation

```bash
pip install -q -U wurun pandas numpy seaborn matplotlib pydantic
```

## Evaluation Metrics

- **Sentence-level Fairness Variance (SFV)**: Row-wise bias measurement
- **Entity-level Fairness Disparity (EFD)**: Column-wise bias measurement  

## Reproducibility

All experiments are implemented in Jupyter notebooks with:
- Documented hyperparameters
- Standardized evaluation protocols
- Anonymized datasets

## License

This code is provided for research purposes. Please cite appropriately if used in academic work.

## Data Privacy

All datasets have been anonymized and contain no personally identifiable information. Demographic references use generic placeholder terms.

## Contact

For questions regarding this implementation, please refer to the associated academic publication.
