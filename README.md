# Permutation Glass

<p align="center">
<img align = "center" src = "https://user-images.githubusercontent.com/8810308/111638380-a53b3400-87d0-11eb-9407-78a613cdd922.png"  onmouseover= "Motivation for statistical physics based algorithm" width = "75%">
</p>

The Knapsack Problem is a classic problem from combinatorial optimization. In the "0-1" version of the problem, we are given N objects each of which has a value and a weight, and our objective is to find the collection of objects that maximizes the total value of the collection while ensuring that the weight remain under a given maximum. 

This repository provides algorithms for solving various incarnations of the  Knapsack Problem in the limit of where the total number of elements is large. Currently the libary supports approximate solutions to the "0-1", "bounded", and "unbounded" versions of the problem. 

There are exact algorithms for the knapsack problem [(RossettaCode Knapsack)](https://rosettacode.org/wiki/Knapsack_problem), but these take longer as the number of items increases. The algorithms in this repository provide approximate solutions in much less time. 


## Reproducing figures and tables

The notebooks that reproduce the figures and tables in the paper are as follows

- [`potential_landscape.ipynb`](https://github.com/mowillia/largeNKP/blob/main/potential_landscape.ipynb): Reproduces Figure 2(a); Runs in < 1 minute
- [`total_value_vs_temperature.ipynb`](https://github.com/mowillia/largeNKP/blob/main/total_value_vs_temperature.ipynb): Reproduces Figure 2(b); Runs in < 1 minute
- [`algorithm_comparisons.ipynb`](https://github.com/mowillia/largeNKP/blob/main/algorithm_comparisons.ipynb): Reproduces Figure 3; Runs in 15 minutes
- [`limit_ratio_vs_temperature.ipynb`](https://github.com/mowillia/largeNKP/blob/main/limit_ratio_vs_temperature.ipynb): Reproduces Table 1; Runs in < 1 minute
- [`failure_modes.ipynb`](https://github.com/mowillia/largeNKP/blob/main/failure_modes.ipynb): Gives examples of "Failure Modes" discussed in Appendix



<!---
## References
[1] Mobolaji Williams. "Large N Limit of the Knapsack Problem." *Journal Name.* 2021. [[arxiv]](https://arxiv.org/abs/XXXX)
--->
---
<!---
If you found this repository useful in your research, please consider citing
```
@article{williams2021knapsack,
  title={Large N Limit of the Knapsack Problem},
  author={Williams, Mobolaji},
  journal={arXiv preprint arXiv:CCC},
  year={2021}
}
```
--->
