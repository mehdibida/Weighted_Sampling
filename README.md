# Weighted_Sampling

This is a faster Julia implementation of the [weighted direct](https://juliastats.org/StatsBase.jl/stable/sampling/#StatsBase.direct_sample!-Tuple{AbstractRNG,AbstractArray,AbstractWeights,AbstractArray) sampling method of the Julia [StatsBase](https://github.com/JuliaStats/StatsBase.jl) package. Although not faster than the [Alias method](https://juliastats.org/StatsBase.jl/stable/sampling/#StatsBase.alias_sample!) in general, it can be faster when the number of draws is small compared to the number of possibilities.

Code and benchmarks can be found in the Jupyter file.
