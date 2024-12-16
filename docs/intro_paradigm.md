# The paradigme of Functional Data Analysis

Functional Data Analysis (FDA) refers to the case where the observation units are whole curves (also called trajectories or sample paths). Then the data set consists of a collection of N trajectories corresponding to N observation units, modeled by the same underlying stochastic process defined on
some domain.

For example, if we look at the weight curves of several individuals. Whereas in classical statistics, an observation would correspond to a measurement of a person's weight at a given time, in functional data analysis, the observation corresponds to an individual's weight trajectory.

A common practice in FDA is to first create smoothed curves, that are usually called functional data objects, from the data points on each curve separately, and then proceed as if the sample paths were observed without error everywhere in the domain. For each curve separately, smoothed curves can be constructed by nonparametric smoothing (splines, kernel smoothing...), or simple linear inter-
polation.
