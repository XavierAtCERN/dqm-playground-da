# DQM Playground - Data Augmentation

This repository is an addition to the [website](https://github.com/CMSTrackerDPG/MLplayground), [CLI](https://github.com/XavierAtCERN/dqm-playground-cli), [data analysis framework](https://github.com/XavierAtCERN/dqm-playground-ds) and [time serie analysis](https://github.com/XavierAtCERN/dqm-playground-ts) of the DQM Playground initiative. The goal is to provide an alternative to the current 1D histogram resampling in order to keep the augmented data in the same dimensional space than the initial data.

## Initial strategy

The goal of this project is twofold. First, produce augmented data using GANs (or alternative approach). Second, run clustering on the initial data and the augmented ones in order to check the consistency of the data produced.

## Resources

__GANs__

- [Generative Adversarial Networks Specialization](https://www.coursera.org/specializations/generative-adversarial-networks-gans?)

__Clustering__

- [SNE](https://cs.nyu.edu/~roweis/papers/sne_final.pdf)
- [t-SNE](https://jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf)
