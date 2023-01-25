# Boosting Graph Contrastive Learning via Graph Contrastive Saliency

This is the code for Boosting Graph Contrastive Learning via Graph Contrastive Saliency.

## Requirements

To install requirements:

```setup
conda env create -f environment.yaml
```

## Unsupervised Learning

To train the model for unsupervised graph-level tasks:

```setup
python unsupervised.py
```

## Transfer Learning

To pretrain the model(s) in the paper for transfer learning:

```setup
python transfer_pretrain.py
```
> Output: the file "latest.tar"

To finetune the model(s) for downstream tasks:
```setup
python transfer_finetune.py
```

