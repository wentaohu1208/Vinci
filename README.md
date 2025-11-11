
<div align="center">

<h1> [NIPS'25 Spotlight] <img src="figure/mulberry.png" style="vertical-align: -10px;" :height="50px" width="50px"> Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search </h1>

<h5 align="center"> If you find this project useful, please give us a star🌟.


<h5 align="center"> 

<a href='https://arxiv.org/abs/2412.18319'><img src='https://img.shields.io/badge/Paper-Arxiv-red'></a>
<a href='https://huggingface.co/HuanjinYao/Mulberry_llava_8b'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-blue'>
<a href='https://huggingface.co/datasets/HuanjinYao/Mulberry-SFT'><img src='https://img.shields.io/badge/Dataset-Huggingface-yellow'>
<!--<a href='https://huggingface.co/collections/HuanjinYao/denseconnector-66500e173fc8c9f05dc98dea'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-blue'></a>
[![zhihu](https://img.shields.io/badge/-知乎-000000?logo=zhihu&logoColor=0084FF)](https://zhuanlan.zhihu.com/p/700000183)
<a href='https://huggingface.co/spaces/HuanjinYao/DenseConnector-v1.5-8B'><img src='https://img.shields.io/badge/🤗-Open%20In%20Spaces-blue.svg'></a>-->


[Huanjin Yao](https://scholar.google.com/citations?user=pDtsCBQAAAAJ&hl=zh-CN)<sup>2,3*</sup>,
[Jiaxing Huang](https://jxhuang0508.github.io/)<sup>1*✉️</sup>,
[Wenhao Wu](https://whwu95.github.io/)<sup>3</sup>,
[Jingyi Zhang]()<sup>1</sup>,
[Yibo Wang]()<sup>2</sup>,
[Shunyu Liu]()<sup>1</sup>,
[Yingjie Wang]()<sup>1</sup>,

[Yuxin Song]()<sup>3</sup>,
[Haocheng Feng]()<sup>3</sup>,
[Li Shen]()<sup>4</sup>,
[Dacheng Tao]()<sup>1</sup>


<sup>1</sup>[Nanyang Technological University](https://www.ntu.edu.sg/), <sup>2</sup>[Tsinghua University](https://www.tsinghua.edu.cn/en/), <sup>3</sup>[Baidu](https://vis.baidu.com/#/), <sup>4</sup>[SYSU](https://www.sysu.edu.cn/sysuen/)

<sup>*</sup>Equal Contribution,       <sup>✉️</sup>Corresponding Author

</h5>
</div>

---

## Overview
![Vinci Overview](main_figure.png)
With the continuous development of large language models and reasoning chain technologies, the potential of deep reasoning based on reinforcement learning has shown remarkable promise in multi-task scenarios. However, existing unified models have yet to achieve end-to-end integration in image generation and understanding tasks, limiting the model’s self-reflection ability and the realization of cross-modal reasoning chains. To address this, we propose Vinic, a novel framework designed to enable interleaved image generation and understanding through deep reasoning capabilities. We leverage a small amount of multimodal chain-of-thought (MCoT) data for cold-start and employ reinforcement learning to guide the integration of image generation and understanding tasks. Additionally, we introduce a momentum-based reward function, which dynamically adjusts the reward distribution by considering historical improvements, ensuring the stability of the model across multiple generations. Experimental results demonstrate that integrating MCoT can achieve a +22% improvement over the base model on Geneval, effectively enhancing both image generation quality and instruction alignment capabilities.




---

## ⚙️ Installation

*(TODO: Add installation commands and dependencies, e.g. conda / pip requirements)*
Example placeholder:

```bash
# Clone the repository
git clone https://github.com/yourname/Vinci.git
cd Vinci

# TODO: Add environment setup instructions
```

---

## 🚀 Inference

*(TODO: Add model checkpoint links and inference scripts)*
Example placeholder:

```bash
# TODO: Replace with actual inference command
python inference.py --config configs/vinci_infer.yaml --prompt "a robot painting in Van Gogh style"
```

---

## 🧩 Training Data

*(TODO: Add dataset descriptions, links, or data preparation scripts)*
You can later include:

* ✅ Dataset sources (e.g. Geneval, RealUnify, or custom RL datasets)
* 🧠 Preprocessing pipeline
* 📦 Download commands or paths

---

## 📚 Citation

If you find this repository useful, please consider citing:

```bibtex
@article{hu2025vinci,
  title={Vinci: Deep Thinking in Text-to-Image Generation using Unified Model with Reinforcement Learning},
  author={Hu, Wentao and Zhang, Hanwang and others},
  journal={NeurIPS},
  year={2025}
}
```

---

是否希望我帮你补一个「项目结构说明」和「Quick Demo」小节？可以先留空或写模板。
