<h1 align="center">
Are Large Language Models Really Good Logical Reasoners? A Comprehensive Evaluation and Beyond
</h1>

<p align="center">
  <a href="https://ieeexplore.ieee.org/document/10870148"><b>[📜 Paper]</b></a> •
  <a href="https://github.com/DeepReasoning/NeuLR"><b>[🐱 GitHub]</b></a>
  
</p>

<p align="center">
Repo for "<a href="https://ieeexplore.ieee.org/document/10870148" target="_blank">Are Large Language Models Really Good Logical Reasoners? A Comprehensive Evaluation and Beyond</a>"
</p>

## 🔥 News

- [2025/02] 🔥🔥🔥 Logical reasoning evaluation study of LLMs is accepted by IEEE TKDE!

## 📖 Intorduction

<p align="center">
    <img src="evaluation.png" alt="scaling" width="400">
</p>

In this paper, in-depth evaluations are conducted on logical reasoning tasks, discussing whether LLMs are really good logical reasons.
> - First, the logical reasoning evaluations are organized from deductive, inductive, abductive and mixed-form views. We select fifteen logical reasoning datasets to evaluate on three representative LLMs (i.e., text-davinci-003, ChatGPT and BARD) under both zero-shot and few-shot settings.
> - Second, this paper provides fine-level evaluations on four metrics, covering both objective and subjective views. For problematic cases, extensive error attributions are conducted from two dimensions, forming five error types. It uncovers the logical flaws of LLMs and we provide deep analysis on the results.
> - Third, to achieve a fair and pure benchmark for logical reasoning capability, we propose a dataset with neutral content, covering deductive, inductive and abductive settings.




## 🚀 NeuLR


Considering the current benchmarks may not provide neutral content for fair evaluation, we propose the new dataset NeuLR to benchmark the neutral-content logical reasoning tasks. In column 1∼3 of the able, we provide the statistics of NeuLR. It contains 3 k samples in total, with ***1 k for deductive reasoning***, ***1 k for inductive reasoning*** and ***1k for abductive reasoning***.




|Dataset| Num.| Hop|<td colspan="3">vv</td> | ChatGPT|||BARD|| |
|  --------  | ------  | ------  | ------  | ------  | ------  | ------  | ------  | ------  | ------  | ------  | ------  |
|^|^|^|0-shot| 1-shot| COT|0-shot| 1-shot| COT|0-shot| 1-shot| COT|
|NeuLR|3,000|1~5|50.93|59.17|67.90 |37.27|48.13|48.00|63.67|65.07|66.00|
|- Deductive|1,000| 2|59.00|69.40|86.10|85.20|69.10|68.30|87.40|93.10|91.90|
|- Inductive|1,000| 3|86.90|89.60|95.60|15.10|68.60|69.60|96.00|92.60|96.30|
|- Abductive|1,000| 1~5|6.90|18.50|22.00|11.50|6.70|6.10|7.60|9.50|9.80|






From the results, we have the following observations:
> - First, few-shot prompting and chain-ofthought prompting can both boost the performances of LLMs in most cases. Overall, chain-of-thought helps most to the model accuracy.
> - Second, among the zero-shot results of three LLMs, BARD achieves the best performances on NeuLR while ChatGPT ranks last. The differences of zero-shot settings are significant.
> - Third, from the perspective of different reasoning settings, there exist huge differences in results compared with the previous findings. The performances among the reasoning settings are sorted as deductive > abductive > inductive.





## Citation

If you find it helpful, please kindly cite the paper.

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

