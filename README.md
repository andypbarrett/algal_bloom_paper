# Plotting snow thickness trends for algal bloom paper

The notebook includes code to plot Figure 2 of Stroeve et al, Mapping potential timing of ice algal blooms from
satellite.

Snow thickness data are from [Lagrangian Snow Distributions for Sea-Ice Applications, Version 1](https://nsidc.org/data/nsidc-0758/versions/1) (10.5067/27A0P5M6LZBI).

## Installing

It is best to clone the repo and create a virtual environment.

```
git clone git@github.com:andypbarrett/algal_bloom_paper.git
```

Creating a virtual environment will reduce clonflicts.  The required packages are all contained in `environment.yml`.  
A virtual environment can be created using `conda` or `mamba`.  You will need to install `mamba` but it is more efficient that `conda`.

```
cd algal_bloom_paper
```

```
mamba env create -f environment.yml
```
or
```
conda env create -f environment.yml
```

Then...
```
mamba activate algal-bloom-paper
```
or
```
conda activate algal-bloom-paper
```

## Usage

```
jupyter lab
```

And select the notebook.
