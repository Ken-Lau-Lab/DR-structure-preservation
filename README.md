### A quantitative framework for evaluating data structure preservation by dimensionality reduction techniques

High-dimensional data is integral to modern systems biology. Computational methods for dimensionality reduction are being rapidly developed for applications to single-cell and multi-modal technologies. In order to understand what these nonlinear transformations do to the underlying biological patterns in our data, we developed a framework of quantitative metrics for global and local distance preservation. See our [Cell Reports publication](https://doi.org/10.1016/j.celrep.2020.107576) for details and analysis of existing dimensionality reduction methods.

![alt text](dev/outputs/graphical_abstract.png)

---

#### Contents

##### `fcc_utils.py`

Contain utility functions for manipulating datasets and comparing feature-reduced latent spaces.

Documentation available at [Ken-Lau-Lab.github.io/DR-structure-preservation/](https://ken-lau-lab.github.io/DR-structure-preservation/).

##### Tutorials

Consult `distance_preservation_tutorial.ipynb` for info on how to perform global and local structure preservation analyses on low-dimensional embeddings of your own datasets.

---

#### Required Python Dependencies

Install using pip:

```bash
pip install -r requirements.txt
```

---

#### Optional Packages

In order to use the [__"FIt-SNE"__ implementation](https://arxiv.org/abs/1712.09005) of t-SNE, you'll need to download [FFTW](http://www.fftw.org/) and compile the code from the [FIt-SNE repo](https://github.com/KlugerLab/FIt-SNE).

Clone the [scvis](https://github.com/shahcompbio/scvis) and [ZIFA](https://github.com/epierson9/ZIFA) packages and install with `python setup.py install` from their home directories.
