# regression-importance-sampling
Code release for "Importance Sampling with an Estimated Behavior Policy" (ICML 2019)


This repository contains code for reproducing the main results in "Importance Sampling with an Estimated Behavior Policy." Specifically, this code can be used to reproduce Figures 2, 3, and 4. The final experiment in the paper has a larger list of dependencies and is thus not included.

If you find this repository useful for your own research, please cite our paper:
```
@inproceedings{hanna2019importance,
  title={Importance Sampling Policy Evaluation with an Estimated Behavior Policy},
  author={Hanna, Josiah and Niekum, Scott and Stone, Peter},
  booktitle={Proceedings of the International Conference on Machine Learning (ICML)},
  year={2019},
  month={June}
}
```

Dependencies:
1. All directories require Google's python protobuf compiler. The gridworld subdirectory also requires a version of libprotobuf and the c++ protobuf compiler.

Contents:
1. Subdirectory gridworld has code for Figure 2. See gridworld/README for instructions.
2. Subdirectory singlepath has code for Figure 3. See singlepath/README for instructions.
3. Subdirectory lds has code for Figure 4. See lds/README for instructions.
