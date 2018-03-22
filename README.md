# osdc_east_18_hackerstats
Training session for ODSC East 2018 on hacker stats

## Abstract
With some basic programming skills, the oft-perceived high barrier of entry into statistical inference can be readily overcome. In this training session, you will learn how to use NumPy's random number generators to perform statistical inference using so-called bootstrap methods. Throughout the training session, you will apply the techniques you're learning on a real data set: forty years worth of measurements of the beaks of Darwin's finches on an island in the Galápagos. When you are done, you will be able to compute confidence intervals and perform hypothesis tests with a few lines of intuitive Python code. As an added bonus, you will see evolution happen through data.

## Bio
[Justin Bois](http://bois.caltech.edu/) is a lecturer in the Division of Biology and Biological Engineering at Caltech, where he teaches nine different courses across a variety of topics. Because so many lines of biological inquiry require quantitative approaches, every course features analysis of data. In addition to his teaching at Caltech, he constructed three courses for DataCamp.

## System requirements
You can probable use earlier versions, but everything has been tested with the following versions.
- Python 3.6.4
- Jupyter 1.0.0
- NumPy 1.14.2
- SciPy 1.0.0
- Pandas 0.22.0
- Matplotlib 2.2.2
- Numba 0.37.0 (optional)
- joblib 0.11 (optional)

## Tentative outline
Following is a tentative outline. The topics will be split between instructor-lead demonstrations and attendee exercises.
- Introduction to the data set
- Display of measurements
  - ECDFs: *G. fortis* beak depth in 1987
  - Scatter plots: Heritability of beak depth
- Summary statistics (using 1987 *G. fortis* beak depths)
  - Percentiles and the median
  - Mean
  - Standard deviation
  - Pearson correlation
- Confidence intervals
  - Definition
  - "Simulating" data acquisition using the bootstrap
- Bootstrap samples
  - Resampling using random number generators
  - Visualization of bootstrap samples
- Bootstrap replicates
  - Computation of summary statistics
- Bootstrap confidence intervals for repeated measurements
  - *G. fortis* beak depths 1987 to 2012
- Pairs bootstrap
  - Confidence intervals for heritability
- Hypothesis testing
  - Definition
  - *Caveat emptor*!
- Two-sample permutation test
  - *G. fortis* beak depths 1987 to 2012
- Two-sample bootstrap hypothesis test
  - *G. fortis* beak depths 1987 to 2012
- One sample bootstrap hypothesis test
  - Comparison with measurements from David Lack in the 1940s
- Bootstrap hypothesis test for correlation
  - Are beak lengths correlated?
- Speeding up bootstrap calculations
  - Just-in-time compilation with Numba
  - Parallel resampling using joblib
- Summary and wrap-up
