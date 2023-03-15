# σReparam

An unofficial implementation of the σReparam from the "[Stabilizing Transformer Training by Preventing Attention Entropy Collapse](https://arxiv.org/abs/2303.06296)" paper. Authors claim a big simplification of the model regularization and training regimes:

> We conduct experiments with σReparam on image classification, image self-supervised learning, machine translation, automatic speech recognition, and language modeling tasks, across Transformer architectures. We show that σReparam provides stability and robustness with respect to the choice of hyperparameters, going so far as enabling training (a) a Vision Transformer to competitive performance **without warmup, weight decay, layer normalization or adaptive optimizers**; (b) deep architectures in machine translation and (c) speech recognition to competitive performance without warmup and adaptive optimizers.

## Citations

```bibtex
@article{https://doi.org/10.48550/arxiv.2303.06296,
  title = {Stabilizing Transformer Training by Preventing Attention Entropy Collapse},
  url = {https://arxiv.org/abs/2303.06296},
  author = {Zhai, Shuangfei and Likhomanenko, Tatiana and Littwin, Etai and Busbridge, Dan and Ramapuram, Jason and Zhang, Yizhe and Gu, Jiatao and Susskind, Josh},  
  publisher = {arXiv},
  year = {2023},
}
```
