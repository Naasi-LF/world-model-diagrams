# 世界模型结构图

世界模型两条线上的论文结构图：数据在模块之间怎么传，每个模块怎么训练。Dreamer 这条线把画面还原成像素来对答案，JEPA 这条线只在表征上对答案。Dreamer v2、v3 两页只画相对上一版的改动。

在线查看：https://naasi-lf.github.io/world-model-diagrams/

| 图 | 论文 |
|---|---|
| [World Models](https://naasi-lf.github.io/world-model-diagrams/world-models.html) | Ha 与 Schmidhuber，World Models，2018 |
| [PlaNet](https://naasi-lf.github.io/world-model-diagrams/planet.html) | Hafner 等，Learning Latent Dynamics for Planning from Pixels，2019 |
| [Dreamer v1](https://naasi-lf.github.io/world-model-diagrams/dreamer.html) | Hafner 等，Dream to Control: Learning Behaviors by Latent Imagination，2020 |
| [Dreamer v2](https://naasi-lf.github.io/world-model-diagrams/dreamer-v2.html) | Hafner 等，Mastering Atari with Discrete World Models，2021 |
| [Dreamer v3](https://naasi-lf.github.io/world-model-diagrams/dreamer-v3.html) | Hafner 等，Mastering Diverse Domains through World Models，2023 |
| [I-JEPA](https://naasi-lf.github.io/world-model-diagrams/ijepa.html) | Assran 等，Self-Supervised Learning from Images with a Joint-Embedding Predictive Architecture，2023 |

所有图用同一套画法。图里的尺寸和超参数取自各篇论文的附录，并对照了官方代码。带 + 的方框可以点开，看里面每一层的结构。

这里的网页由一个 Python 脚本生成，直接打开 HTML 文件也能看。
