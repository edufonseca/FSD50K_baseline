# FSD50K_baseline

This repository contains the code for the baseline experiments included in the following <a href="https://annotator.freesound.org/fsd/release/FSD50K/" target="_blank">paper</a>. If you use this code or part of it, please cite:

>Eduardo Fonseca, Xavier Favory, Jordi Pons, Frederic Font, Xavier Serra, "FSD50K: an Open Dataset of Human-Labeled Sound Events", arXiv 2020.

This repository contains a framework that comprises all the basic stages in supervised sound event classifcation: feature extraction, training, inference and evaluation. After loading the FSD50K dataset, log-mel energies are computed and several baselines can be trained and evaluated. Please check our paper for more details. The system is implemented in TensorFlow.

We're currently cleaning the code, which will be made available in the next few weeks. We will announce when it is available via <a href="https://twitter.com/edfonseca_" target="_blank">twitter</a> and via the <a href="https://groups.google.com/g/freesound-annotator" target="_blank">freesound-annotator Google Group</a>.

In the meantime, make sure to take a look at the resources we just released:

- the FSD50K dataset can be downloaded from Zenodo:
- our journal preprint describing in depth the creation of the dataset, as well as its characterization and baseline experiments:
- if you don't want to read all the paper, have quick view to this blog post:
- the FSD50K's companion site: <a href="https://annotator.freesound.org/fsd/release/FSD50K/" target="_blank">https://annotator.freesound.org/fsd/release/FSD50K/</a>

Stay tuned for the code!
