---
title: Tutorial on reproducibility with randomness
author:
  - name:
      given: Jun
      family: Sun
    email: jun.sun@gesis.org
    orcid: 0000-0002-4789-7316
    affiliations:
      - name: "GESIS - Leibniz Institute for the Social Sciences"
csl: apa.csl
format:
  html: default
  ipynb: default
license: Apache-2.0
---

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yfiua/reproducibility-with-randomness/HEAD?labpath=main.ipynb)

# Tutorial on reproducibility with randomness

This tutorial will cover the following topics on reproducibility in Python programs incorporating randomness, primarily focusing on NumPy.

## Learning goals

* Random states in NumPy
* Preserving the random state
* Avoid cherry-picking results

## Target audience

This tutorial is aimed at social scientists and data scientists who are interested in making their Python code with randomness reproducible. The tutorial is suitable for beginners and intermediate learners with some knowledge in Python.

## Social science use cases

Reproducibility with randomness is an important concept in social science studies, particularly when performing sampling, simulations, or machine learning. Here are some examples:

* Sampling from surveys
* Simulations with agent-based models (ABM) or Monte Carlo methods
* Network analysis with random graphs
* Machine learning

## Estimated duration

The tutorial is designed to be completed in 1-2 hours. The duration may vary depending on the prior knowledge of the participants.

## Setting up the computational environment

### Hardware

The tutorial can be run on a laptop or desktop computer.

### Software

To run the code in the tutorial on [mybinder.org](https://mybinder.org/), simply click the "launch|binder" badge.

To run it locally, Python >= 3.9 is required. In addition, the necessary packages are listed in [requirements.txt](requirements.txt). Using `pip` as an example, install the packages with

```sh
pip install -r requirements.txt
```

## Author
[Dr. Jun Sun](https://github.com/yfiua) @ GESIS
