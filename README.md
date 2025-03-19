<h1 align="center">
φ-Decoding: Adaptive Foresight Sampling for Balanced Inference-Time Exploration and Exploitation
</h1>

<p align="center">
  <a href="https://github.com/xufangzhi/phi-Decoding/"><b>[🌐 PyPi Package]</b></a> •
  <a href="https://arxiv.org/abs/2503.13288"><b>[📜 Paper]</b></a> •
  <a href="https://github.com/xufangzhi/phi-Decoding"><b>[🐱 GitHub]</b></a>
  
</p>

<p align="center">
Repo for "<a href="https://arxiv.org/abs/2503.13288" target="_blank">φ-Decoding: Adaptive Foresight Sampling for Balanced Inference-Time Exploration and Exploitation</a>"
</p>

## 🔥 News

- [2025/02/16] 🔥🔥🔥 $\phi$-Decoding is released !

## 📖 Results

$\phi$-Decoding provides balanced inference-time exploration and exploitation. The following scaling curve offers the comparisons with other strong methods on LLaMA3.1-8B models. For more results, please refer to our [paper](https://arxiv.org/abs/2311.09278).


<p align="center">
    <img src="./assets/scaling_law.png" alt="scaling" width="400">
</p>

## 🚀 Quick Start

To use the $\phi$-Decoding, we can try with the following command.

Firstly, create the environment and install the requirements. This implementation is accelerated and supported by vllm.

```bash
# env
conda create -n phi-decoding python==3.10
conda activate phi-decoding
pip install -r requirements.txt
```

Next, simply run the following command after the basic configuration:

```bash
python phi_decoding.py
```


## 🔧 PyPi Package

We are currently working on providing a PyPI package. Stay tuned !


## Citation

If you find it helpful, please kindly cite the paper.

```
@article{xu2025phi,
  title={$\phi$-Decoding: Adaptive Foresight Sampling for Balanced Inference-Time Exploration and Exploitation},
  author={Xu, Fangzhi and Yan, Hang and Ma, Chang and Zhao, Haiteng and Liu, Jun and Lin, Qika and Wu, Zhiyong},
  journal={arXiv preprint arXiv:2503.13288},
  year={2025}
}
```



# NeuLR
This is the content-neutral dataset of logical reasoning. It contains three reasoning types: deductive, inductive and abductive.

If this paper proves beneficial to your research, kindly acknowledge it by citing the following reference:
```
@article{DBLP:journals/corr/abs-2306-09841,
  author       = {Fangzhi Xu and
                  Qika Lin and
                  Jiawei Han and
                  Tianzhe Zhao and
                  Jun Liu and
                  Erik Cambria},
  title        = {Are Large Language Models Really Good Logical Reasoners? {A} Comprehensive Evaluation and Beyond},
  journal      = {IEEE Transactions on Knowledge and Data Engineering},
  year         = {2025}
}
```
