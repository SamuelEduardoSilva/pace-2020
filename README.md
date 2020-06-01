## Treedepth PACE 2020 Submission

This repository contains the solver submitted to the [PACE 2020](https://pacechallenge.org/2020/td/) Treedepth challenge. Our solver was developed at [UFF](http://www.uff.br/) in the our Parameterized Team.

To running our code, just clone the repository and build the program, as follows:

```bash
git clone https://github.com/SamuelEduardoSilva/pace-2020.git
cd pace-2020
g++ -o solver UffFptTeam.cpp -03 -std=c++14
```
There are a way to correctly invoke the program:

```bash
./solver < my_graph.gr > ans.tree
```

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3872029.svg)](https://doi.org/10.5281/zenodo.3872029)
