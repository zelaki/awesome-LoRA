
## Low-Rank Decomposition
| Title & Authors | TL;DR | Links |
|:--|  :----: | :---:|
[LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/pdf/2106.09685) <br> Edward J. Hu, Yelong Shen, Phillip Wallis, Zeyuan Allen-Zhu, Yuanzhi Li, Shean Wang, Lu Wang, Weizhu Chen| $h = W_0x + BAx$ <br> $B \in \mathbb{R}^{d\times r}$    $A \in \mathbb{R}^{r\times d}$    $r \ll d$|[Github](https://github.com/microsoft/LoRA) <br> [Paper](https://arxiv.org/pdf/2106.09685)|
[DoRA: Weight-Decomposed Low-Rank Adaptation](https://arxiv.org/abs/2402.09353) <br> Shih-Yang Liu, Chien-Yi Wang, Hongxu Yin, Pavlo Molchanov, Yu-Chiang Frank Wang, Kwang-Ting Cheng, Min-Hung Chen|  DoRA decomposes the pre-trained weight into two components, magnitude and direction, and LoRA adapts direction|[Github](https://github.com/NVlabs/DoRA) <br> [Paper](https://arxiv.org/pdf/2402.09353)|
[VeRA: Vector-based Random Matrix Adaptation](https://arxiv.org/abs/2310.11454) <br> Dawid J. Kopiczko, Tijmen Blankevoort, Yuki M. Asano|VeRA levereges random projection to further reduce the trainable parameters |[Github](https://github.com/NVlabs/DoRA) <br> [Paper](https://arxiv.org/pdf/2310.11454)|











[//]: #06/28



## Orthogonal Finetuing
| Title & Authors | TL;DR | Links |
|:--|  :----: | :---:|
[Controlling Text-to-Image Diffusion by Orthogonal Finetuning](https://arxiv.org/pdf/2106.09685) <br> Zeju Qiu, Weiyang Liu, Haiwen Feng, Yuxuan Xue, Yao Feng, Zhen Liu, Dan Zhang, Adrian Weller, Bernhard Schölkopf| $h = \mathbf{R} W_0x$ <br>   $\mathbf{R} \mathbf{R}^⊤ = \mathbf{I}$ <br> $R=(I+Q)(I−Q)^{−1}$ where $Q$ is a skew-symmetric matrix satisfying $Q=−Q^⊤$|[Github](https://github.com/Zeju1997/oft) <br> [Paper](https://arxiv.org/pdf/2306.07280)|


<!-- [//]: #06/28 -->