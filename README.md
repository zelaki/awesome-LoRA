
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
[Parameter-Efficient Orthogonal Finetuning via Butterfly Factorization](https://arxiv.org/abs/2311.06243) <br> Weiyang Liu, Zeju Qiu, Yao Feng, Yuliang Xiu, Yuxuan Xue, Longhui Yu, Haiwen Feng, Zhen Liu, Juyeon Heo, Songyou Peng, Yandong Wen, Michael J. Black, Adrian Weller, Bernhard Schölkopf| An efficient parametrization of $\mathbf{R}$ inspired by FFT algorithm|[Github](https://github.com/wy1iu/butterfly-oft) <br> [Paper](https://arxiv.org/pdf/2311.06243)|
[Parameter Efficient Quasi-Orthogonal Fine-Tuning via Givens Rotation](https://arxiv.org/abs/2404.04316) <br> Xinyu Ma, Xu Chu, Zhibang Yang, Yang Lin, Xin Gao, Junfeng Zhao| Rotation matrix $\mathbf{R}$ can be represented as a product of *Givens Rotations* |[Github](https://github.com/ArthurLeoM/peft-givens) <br> [Paper](https://arxiv.org/pdf/2404.04316)|
[Bridging The Gap between Low-rank and Orthogonal Adaptation via Householder Reflection Adaptation](https://arxiv.org/abs/2405.17484) <br> Shen Yuan, Haotian Liu, Hongteng Xu| Rotation matrix $\mathbf{R}$ can be represented as a product of *Householder Reflections* <br> $H= I -2uu^T$ |[Github](https://github.com/DaShenZi721/HRA) <br> [Paper](https://arxiv.org/pdf/2405.17484)|


<!-- [//]: #06/28 -->