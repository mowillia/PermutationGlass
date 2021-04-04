# Permutation Glass

A permutation glass is a statistical physics system whose state space consists of permutations of an ordered list and whose energy parameters are drawn from a quenched distribution of values. The simplest permutation glass has a Hamiltonian of the form

<p align="center">
<img src = "https://user-images.githubusercontent.com/8810308/113522608-fd638b80-956f-11eb-9f6d-18d583e246c2.png" width = "30%">
  </p>
  
 where _I_A_ = 1 if _A_ is true and _I_A_ = 0 otherwise, and (_theta_1, theta_2, ..., theta_N_) in the set perm(_omega_1, omega_2, ..., omega_N_). Namely the equation defines a state space consisting of permutations of the initially ordered list (_omega_1, omega_2, ..., omega_N_) where there is an energy cost _lambda_k_ for each _omega_k_ "incorrect" placement of omega_k, that is a placement where _omega_k_ is not in its original position in the initially ordered list. 
 
We can use two figures to depict the permutation glass schematically:

<p align="center">
<img align = "center" src = "https://user-images.githubusercontent.com/8810308/113324254-e8bf9300-92e4-11eb-8323-002351b793c7.png" width = "40%" padding = 50px>
  <img align = "center" src = "https://user-images.githubusercontent.com/8810308/113324506-2fad8880-92e5-11eb-971e-29c5a2a34ab9.png" width = "40%" padding = "50px">
</p>

The left figure is a ["permutation graph"](https://en.wikipedia.org/wiki/Permutation_graph) depiction of four microstates in a permutation system with _N_=15. In each graph, _j_ is equivalent to the number of diagonal lines in the permutation graph. The number of "correct" connections are shown as vertical lines. The right figure is a "matching problem" depiction of a _j_=10 microstate for a _2N_ = 30 permutation system. The spatial location of each pair is not important in determining the energy of the state. For this state, the matching pairs are 3, 6, 11, 14, and 15. 
 
 This respository contains the notebooks that reproduce the results of the [associated paper](https://arxiv.org/pdf/1801.03231.pdf).


## Reproducing figures and tables

The notebooks that reproduce the figures and tables in the paper are as follows

- [`temp_vs_signorm.ipynb`](https://nbviewer.jupyter.org/github/mowillia/PermutationGlass/blob/master/temp_vs_sigmanorm.ipynb): Reproduces Figure 3; Runs in < 1 sec
- [`perm_glass_simulation.ipynb`](https://nbviewer.jupyter.org/github.com/mowillia/PermutationGlass/blob/master/perm_glass_simulation.ipynb): Reproduces Figure 4; Runs in < 5 minutes
- [`prob_neglambda_vs_N.ipynb`](https://nbviewer.jupyter.org/github.com/mowillia/PermutationGlass/blob/master/prob_neglambda_vs_N.ipynb): Reproduces Figure 5; Runs in < 1 sec


## References
[1] Williams, Mobolaji. "Permutation glass." *Physical Review E* 97.1 (2018): 012139. [[arXiv pre-print]](https://arxiv.org/pdf/1801.03231.pdf)

---

If you found this repository useful in your research, please consider citing
```
@article{williams2018permutation,
  title={Permutation glass},
  author={Williams, Mobolaji},
  journal={Physical Review E},
  volume={97},
  number={1},
  pages={012139},
  year={2018},
  publisher={APS}
}
```
