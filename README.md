# LCPNet

This repository is the implementation of LCPNet

[2026] **LCPNet**: Latent Consistent Proximal Unfolding Network for Infrared Small Target Detection.

[![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2607.04603) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/Tianfang-Zhang/LCPNet)
> **Authors:** Tianfang Zhang, Fengyi Wu, Lei Li, Chang Liu, Zhenming Peng, Huaping Zhang, Xiangyang Ji.

<details>
  <summary>
  <font size="+1">Abstract</font>
  </summary>
Infrared small target detection (IRSTD) aims to identify long distance small targets from complex infrared backgrounds, and is a fundamental task in remote sensing. Deep learning methods have improved IRSTD by learning discriminative image-to-mask mappings, but such feed-forward designs often underuse physical decomposition structure between targets and backgrounds. Deep unfolding methods partially address this issue by embedding model-driven iterations into neural networks, yet existing designs still operate mainly in image domain and use updates and memory mechanisms that are not fully coupled with underlying optimization process. To address these limitations, we propose Latent Consistent Proximal unfolding network (LCPNet). First, we verify that low-rank prior remains valid in latent representations and perform unfolding in this space, preserving physical constraint while avoiding repeated compression of intermediate states. Second, we derive a Latent Consistent Proximal (LCP) solver that evolves each latent variable from its previous state rather than reconstructing through an indirect residual, and stabilizes small target updates through task-adaptive normalization and gain control. Third, we introduce Shared Optimization Memory (SOM), a common historical state shared by all decomposition variables to provide coordinated guidance across unfolding stages. Extensive experiments on four public benchmarks demonstrate that LCPNet outperforms state-of-the-art methods while achieving accurate and robust detection with low false alarms and competitive efficiency.
</details>

⚠️⚠️⚠️ This repo is under construction

---

## Get It Started

### Requirements

### Datasets Preparation

### Inference

### Evaluation

### Training

## Results and Training Weights

## Citation

```
@misc{zhang2026lcpnet,
      title={LCPNet: Latent Consistent Proximal Unfolding Network for Infrared Small Target Detection}, 
      author={Tianfang Zhang and Fengyi Wu and Lei Li and Chang Liu and Zhenming Peng and Huaping Zhang and Xiangyang Ji},
      year={2026},
      eprint={2607.04603},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2607.04603}, 
}
```

## Acknowledgement
