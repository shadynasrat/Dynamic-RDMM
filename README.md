<div align="center">

<img width="300px" alt="Graphiti-ts-small" src="https://github.com/shadynasrat/Dynamic-RDMM/blob/main/docs/Dynamic-RDMM_files/static/Dynamic-RDMM_logo.png">

## Dynamic-RDMM: A Collaborative Robotics System for Inpainting on Physical Canvas Using Marker and Eraser

<br />

![UBUNTU](https://img.shields.io/badge/UBUNTU-20.04-orange?style=plastic&logo=ubuntu)
![python](https://img.shields.io/badge/python-3.9-blue?style=plastic&logo=python)
![ROS2](https://img.shields.io/badge/ROS-Noetic-white?style=plastic&logo=ros)

Project Page : [Click Here](https://shadynasrat.github.io/Dynamic-RDMM/)

<br />

</div>

# Abstract
Robotic decision-making with large language models (LLMs) is increasingly constrained by the scarcity of datasets that are both linguistically expressive and grounded in symbolic robotic actions. We introduce the \textbf{Dynamic RDMM Dataset}, a controllable, text-to-text dataset generator that maps natural-language instructions to structured action programs across 23 real-world household tasks. RDMM is built using a two-stage generation process. First, \textit{hierarchical template expansion} recursively constructs multi-step task descriptions from nested logic templates, enabling variable instruction complexity and compositional diversity. Second, \textit{constraint-aware content generation} fills these templates using curated embeddings (verbs, rooms, objects, names) while enforcing semantic and physical validity. This process produces 1,800 expert-verified instruction–action pairs and can be scaled to over 100,000 diverse, syntactically and semantically valid examples. Crucially, RDMM supports task rebalancing and adjustable instruction difficulty, allowing researchers to generate lightweight commands (e.g., "go to the kitchen") or compound sequences (e.g., "deliver an item to Kai and follow him until he sits"). This makes RDMM a practical tool for curriculum learning, ablation studies, and controlled benchmarking. We validate RDMM by fine-tuning LLaMA-3-8B, Mistral-7B, and Qwen-0.5 models, achieving over 94\% accuracy and outperforming ChatGPT-4o baselines. In real-world deployment at RoboCup@Home, RDMM-trained models successfully executed unseen multi-step commands in noisy, natural environments. RDMM is released with templates, code, and generation tools to support reproducible, instruction-grounded robot learning.


<br />

<p align="center">
    <img src="/docs/Dynamic-RDMM_files/intro.jpeg" width="700px">   
</p>

<br />



# Roadmap

Here’s what we’ve accomplished and what’s coming soon:

- [x] Launched project website
- [x] Publish Dataset
- [x] Publish finetuned Models
- [ ] Upload inference code



# Installation
```
pip install -r requirements

python main.py
```





## bibtex
```
@inproceedings{Dynamic-RDMM,
  author={Shady Nasrat, Jae-Bong Yi, Minseong Jo, and Seung-joon Yi},
  booktitle={2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={xxxx--xxxx},
  year={2024},
  organization={IEEE}
}
```
