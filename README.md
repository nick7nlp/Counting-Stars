# Counting-Stars (★)

This repository provides the data and visualization code of the following paper.

[Counting-Stars (★):\
A Simple, Efficient, and Reasonable Strategy for Evaluating Long-Context Large Language Models](https://arxiv.org/pdf/2403.11802v2.pdf)

#


## Note

#### 2024.03.25

- We promptly corrected some mistakes in the visualization code and updated all the figures in the paper and this repository.

- Additionally, we updated the prompts used in the English version, making the corresponding figure in the paper look better.

#### 2024.03.27

- [The supplementary information about NeedleInAHaystack is available in Chinese.](fig/README.md)

## Highlight

#### 2024.03.26

- To avoid the ground truth values constructed monotonically increasing to affect the testing results, we shuffled and tested the ground truth values, and the results are shown in the following figure. The results show that LLMs are indeed more sensitive to ordered values.

![stone_gpt4_kimi_32_32_random](fig/stone_gpt4_kimi_32_32_random.png)


## CONTACT
For any questions, feel free to create an issue, and we will try our best to solve it. \
**If the problem is more urgent**, you can email me simultaneously (I check email almost daily).
```
NAME: Mingyang Song
EMAIL: nickmysong@tencent.com
```
Our visualization code is built on the source code from [NeedleInAHaystack](https://github.com/gkamradt/LLMTest_NeedleInAHaystack). Thanks for their work.
