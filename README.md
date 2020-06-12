Distillation exploration
========================

This is a little extension of the work done in Distilling Task-Specific Knowledge from BERT into Simple Neural Networks by Tang et al. 2019. Hopefully this notebook will serve as an easy-to-follow guide to distillation, which is actually really simple. This is based on work I did for Polecat.

Tang uses BERT to train a BiLSTM. One of the suggestions for future work is to explore to what extent even simpler models can benefit from the technique. This notebook does just that - we'll try and use BERT to train a simple linear model and CNN implemented in PyTorch.

The notebook looks a bit better in [NBviewer](https://nbviewer.jupyter.org/github/cbowdon/distillation-exploration/blob/master/Distilling_BERT_to_a_CNN.ipynb).
