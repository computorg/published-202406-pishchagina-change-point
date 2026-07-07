# Geometric-Based Pruning Rules for Change Point Detection in Multiple Independent Time Series
Liudmila Pishchagina, Guillem Rigaill, Vincent Runge
2024-07-12

### Citation

Liudmila Pishchagina, Guillem Rigaill and Vincent Runge (July 2024). Geometric-Based Pruning Rules for Change Point Detection in Multiple Independent Time Series. Computo.
<https://doi.org/10.57750/9vvx-eq57>

### Badges

[![build and
publish](https://github.com/computorg/published-202406-pishchagina-change-point/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202406-pishchagina-change-point/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202406-pishchagina-change-point/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202406-pishchagina-change-point)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202406-pishchagina-change-point)
[![DOI:10.57750/9vvx-eq57](https://img.shields.io/badge/DOI-10.57750%2F9vvx--eq57-034E79.svg)](https://doi.org/10.57750/9vvx-eq57)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- [Liudmila Pishchagina](https://github.com/lpishchagina) (Université Paris-Saclay, CNRS, Université d’Évry-Val-d’Essonne, Laboratoire de Mathématiques et Modélisation d’Évry, France)
- Guillem Rigaill (Université Paris-Saclay, CNRS, Université d’Évry-Val-d’Essonne, Laboratoire de Mathématiques et Modélisation d’Évry, France, Université Paris-Saclay, CNRS, INRAE, Université d’Évry-Val-d’Essonne, Institute of Plant Sciences Paris-Saclay (IPS2), Orsay, France)
- Vincent Runge (Université Paris-Saclay, CNRS, Université d’Évry-Val-d’Essonne, Laboratoire de Mathématiques et Modélisation d’Évry, France)

### Abstract

We address the challenge of identifying multiple change points in a
group of independent time series, assuming these change points occur
simultaneously in all series and their number is unknown. The search for
the best segmentation can be expressed as a minimization problem over a
given cost function. We focus on dynamic programming algorithms that
solve this problem exactly. When the number of changes is proportional
to data length, an inequality-based pruning rule encoded in the PELT
algorithm leads to a linear time complexity. Another type of pruning,
called functional pruning, gives a close-to-linear time complexity
whatever the number of changes, but only for the analysis of univariate
time series. We propose a few extensions of functional pruning for
multiple independent time series based on the use of simple geometric
shapes (balls and hyperrectangles). We focus on the Gaussian case, but
some of our rules can be easily extended to the exponential family. In a
simulation study we compare the computational efficiency of different
geometric-based pruning rules. We show that for a small number of time
series some of them ran significantly faster than inequality-based
approaches in particular when the underlying number of changes is small
compared to the data length.
