# Dcop python

[![Documentation Status](https://readthedocs.org/projects/pydcop/badge/?version=latest)](http://pydcop.readthedocs.io/en/latest/?badge=latest)
[![Build Status](https://travis-ci.org/Orange-OpenSource/pyDcop.svg?branch=master)](https://travis-ci.org/Orange-OpenSource/pyDcop)

pyDCOP is a python library for Distributed Constraints Optimization.
It contains implementations of several standard DCOP algorithms (MaxSum, DSA,
DPOP, MGM, etc.) and allows you to develop your own algorithms.

This is a fork of [pyDcop](https://github.com/Orange-OpenSource/pyDcop) that has been updated to run on newer Python versions (Tested on 3.11).

### Installation
```bash
python -m venv pydcop_env
source pydcop_env/bin/activate
```
After cloning the repository, inside the root folder, run:
```bash
pip install .
```

### Usage
With example file `graph_coloring.yaml` (included):
```bash
pydcop solve --algo dpop graph_coloring.yaml
```


Documentation is hosted on 
[ReadTheDoc](https://pydcop.readthedocs.io)
 
