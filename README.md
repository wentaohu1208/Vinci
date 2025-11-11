
<div align="center">

<h1> [NeurIPS 2025] Vinci: Deep Thinking in Text-to-Image Generation using Unified Model with Reinforcement Learning </h1>



<h5 align="center"> 

<a href='https://huggingface.co/datasets/HuanjinYao/Mulberry-SFT'><img src='https://img.shields.io/badge/Dataset-Huggingface-yellow'>


</h5>
</div>



##  📸 Overview
![Vinci Overview](main_figure.png)
With the continuous development of large language models and reasoning chain technologies, the potential of deep reasoning based on reinforcement learning has shown remarkable promise in multi-task scenarios. However, existing unified models have yet to achieve end-to-end integration in image generation and understanding tasks, limiting the model’s self-reflection ability and the realization of cross-modal reasoning chains. To address this, we propose Vinic, a novel framework designed to enable interleaved image generation and understanding through deep reasoning capabilities. We leverage a small amount of multimodal chain-of-thought (MCoT) data for cold-start and employ reinforcement learning to guide the integration of image generation and understanding tasks. Additionally, we introduce a momentum-based reward function, which dynamically adjusts the reward distribution by considering historical improvements, ensuring the stability of the model across multiple generations. Experimental results demonstrate that integrating MCoT can achieve a +22% improvement over the base model on Geneval, effectively enhancing both image generation quality and instruction alignment capabilities.




## ⚙️ Installation

*(TODO: Add installation commands and dependencies, e.g. conda / pip requirements)*
Example placeholder:

```bash
# Clone the repository
git clone https://github.com/yourname/Vinci.git
cd Vinci

# TODO: Add environment setup instructions



## 🚀 Inference

*(TODO: Add model checkpoint links and inference scripts)*
Example placeholder:

```bash
# TODO: Replace with actual inference command
python inference.py --config configs/vinci_infer.yaml --prompt "a robot painting in Van Gogh style"
```



## 🧩 Training Data

*(TODO: Add dataset descriptions, links, or data preparation scripts)*
You can later include:

* ✅ Dataset sources (e.g. Geneval, RealUnify, or custom RL datasets)
* 🧠 Preprocessing pipeline
* 📦 Download commands or paths


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



