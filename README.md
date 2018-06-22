# Single Particle Recognition using Deep Embedding Model

A deep convolutional neural network approach for single-particle recognition in cryo-electron microscopy. The model has been implemented in Tensorflow framework.

## Methods

- Design of the DeepEM model.
- Training of the DeepEM model.
- Particle recognition and selection in the DeepEM model.

## DeepEM algorithm workflow

Learning process:
- *Input*: Training dataset.
- *Output*: Trained CNN parameters i.e. weights and bias.

Recognition process:
- *Input*: Micrographs and trained CNN.
- *Output*: Box files of selected particles in the EMAN2 format for each micrograph.

## Motivation:

BioInformatics research paper by Yanan Zhu, Qi Ouyang, Youdong Mao - [A deep convolutional neural network approach to single-particle recognition in cryo-electron microscopy](https://arxiv.org/pdf/1605.05543.pdf)
