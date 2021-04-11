# FSD50K_baseline

This repository will contain the code for the baseline experiments included in the following <a href="https://arxiv.org/pdf/2010.00475.pdf" target="_blank">paper</a>. If you use this code or part of it, please cite:

>Eduardo Fonseca, Xavier Favory, Jordi Pons, Frederic Font, Xavier Serra, "FSD50K: an Open Dataset of Human-Labeled Sound Events", arXiv:2010.00475, 2020.

This repository will contain a framework that comprises all the basic stages in supervised sound event classifcation: feature extraction, training, inference and evaluation. After loading the FSD50K dataset, log-mel energies are computed and several baselines can be trained and evaluated. Please check our paper for more details. The system is implemented in TensorFlow.

We're currently cleaning the code, which will be made available soon. We will announce when it is available via <a href="https://twitter.com/edfonseca_" target="_blank">twitter</a> and via the <a href="https://groups.google.com/g/freesound-annotator" target="_blank">freesound-annotator Google Group</a>.

In the meantime, make sure to take a look at the resources we just released:

- the FSD50K dataset can be downloaded from Zenodo: <a href="http://doi.org/10.5281/zenodo.4060432" target="_blank">http://doi.org/10.5281/zenodo.4060432</a>
- our <a href="https://arxiv.org/pdf/2010.00475.pdf" target="_blank">journal preprint</a> describes in depth the creation of the dataset, as well as its characterization and baseline experiments
- the FSD50K's companion site, where you can inspect the audio content of the dataset per category: <a href="https://annotator.freesound.org/fsd/release/FSD50K/" target="_blank">https://annotator.freesound.org/fsd/release/FSD50K/</a>


Stay tuned for the code! Also, we will publish a blog post soon!


### Reference
```
@article{fonseca2020fsd50k,
  title={{FSD50K}: an Open Dataset of Human-Labeled Sound Events},
  author={Fonseca, Eduardo and Favory, Xavier and Pons, Jordi and Font, Frederic and Serra, Xavier},
  journal={arXiv preprint arXiv:2010.00475},
  year={2020}
}

```
