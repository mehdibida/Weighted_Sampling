# Weighted_Sampling

This is a faster implementation of the (weighted direct)[https://juliastats.org/StatsBase.jl/stable/sampling/#StatsBase.direct_sample!-Tuple{AbstractRNG,AbstractArray,AbstractWeights,AbstractArray}] sampling method of the Julia [Distributions](https://github.com/JuliaStats/Distributions.jl/blob/f889f9e56b0243d770c195b3eee8baef4880bd2e/docs/src/index.md) package. Although not faster than the [Alias method](https://juliastats.org/StatsBase.jl/stable/sampling/#StatsBase.alias_sample!) in general, it can be faster when the number of draws is small compared to the number of possibilities.

Code and benchmarks can be found in the Jupyter file.
