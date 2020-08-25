# LayoutLM

As a start, we focus on the examples shared in the original repo, to make headway into getting familiar with the model. The repo has two examples:

1. Sequence Labeling
2. Classification

## Sequence Labeling
The preprocessing script suggests this program is for the FUNSD dataset. After downloading, the data, the same `preprocessing.py` script is used on both training and test datasets provided in the original dataset. The only change is the value of `--data_split` argument `(train|test)`

- [ ] Add here a small excerpt from the `data/labels.txt` file that seems to be getting generated at the end of this script

---

## Training Steps

First let's describe single GPU training. Later we'll work on multi-GPU training. 