# Collaborative Bayesian Optimization via Constrained Gaussian Processes

We propose a framework in which multiple agents collaborate on Bayesian optimization through constrained Gaussian processes.

Numerical experiments can be replicated using the code here. 
Under each test function, one can find different methods by referring to their file names.
To replicate our result, simply run the corresponding file under the folder.

* CNEI: Constrained Gaussian Process with Noisy Expected Improvement (Implemented as Log NEI to prevent numerical issues)
* CTS: Constrained Gaussian Process with Thompson Sampling
* CUCB: Constrained Gaussian Process with Upper Confidence Bound
* FTS: Federated Thompson Sampling
* FTSDE: Federated Thompson Sampling with Distributed Exploration
* NEI: Noisy Expected Improvement (Implemented as Log NEI to prevent numerical issues)
* TS: Thompson Sampling
* UCB: Upper Confidence Bound

The output of the results is included in the corresponding Excel files for readability. 
The random seeds are fixed for every file, so one should expect the exact same results under the given setup.

For other details on the algorithm. Please refer to the original paper.

## Citation

[Paper](https://doi.org/10.1080/00401706.2024.2365732) (Technometrics, 2025). If you use this code, please cite:

```bibtex
@article{chen2025multi,
  title={Multi-Agent Collaborative {B}ayesian Optimization via Constrained {G}aussian Processes},
  author={Chen, Qiyuan and Jiang, Liangkui and Qin, Hantang and Al Kontar, Raed},
  journal={Technometrics},
  volume={67},
  number={1},
  pages={32--45},
  year={2025},
  doi={10.1080/00401706.2024.2365732}
}
```
